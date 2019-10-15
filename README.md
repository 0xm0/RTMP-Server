# RTMP-Server
Just a small RTMP server (client side implementation)

## Requirements

- GoLang
- OBS or streaming platform

## Installation 

```bash
go get -u -v github.com/gnet0/RTMP-Server

~/go/bin/rtmp-server  -l :8089 -k  longSecurityKey
```


## Usage

you can use obs to push the stream to the RTMP server

Or if you wanna stream on your URL ```rtmp://sub.domain.tld/live?key=longSecurityKey```

See the demo at:
```
http://sub.domain.tld:8089/
```
Port 8089 is the default listner for http rtmp, you can change it to whatever you want yourself/

```
Usage of .\RTMP-Server.exe:
  -k string
        Stream key with a key
  -l string
        host:port of the RTMP-Server (default ":8089")
```

