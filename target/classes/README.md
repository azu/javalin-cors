# javalin CORS

## Usage

- Start HelloWorld server

## Test

```shell
$ curl -vv -H "origin: https://example.com" http://localhost:7070/
*   Trying 127.0.0.1:7070...
* Connected to localhost (127.0.0.1) port 7070 (#0)
> GET / HTTP/1.1
> Host: localhost:7070
> User-Agent: curl/7.79.1
> Accept: */*
> origin: https://example.com
>
* Mark bundle as not supporting multiuse
< HTTP/1.1 200 OK
< Date: Mon, 01 Aug 2022 15:03:21 GMT
< Content-Type: text/plain
< Access-Control-Allow-Origin: https://example.com
< Access-Control-Allow-Credentials: true
< Vary: Origin
< Content-Length: 11
<
* Connection #0 to host localhost left intact
Hello World%

```