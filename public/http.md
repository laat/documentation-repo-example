# HTTP Example

> Documenting HTTP endpoints in markdown is cool.

**GET request**

```http
GET /hello.htm HTTP/1.1
User-Agent: Mozilla/4.0 (compatible; MSIE5.01; Windows NT)
Host: www.example.com
```

**Response**

```http
HTTP/1.1 200 OK
Date: Mon, 27 Jul 2009 12:28:53 GMT
Last-Modified: Wed, 22 Jul 2009 19:15:56 GMT
Content-Length: 88
Content-Type: text/html
Connection: Closed
```

```html
<html>
  <body>
    <h1>Hello, World!</h1>
  </body>
</html>
```
