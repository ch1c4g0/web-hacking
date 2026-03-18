

<p><h1>Common Request Headers</h1></p>

><p><h3>Host</h3></p>
>
><p>Specifies the name of the web server the request is for.</p>

````
github.com
````

><p><h3>User-Agent</h3></p>
>
><p>Shares information about the web browser the request is coming from.</p>

```
User-Agent: Mozilla/5.0
```

><p><h3>Referer</h3></p>
>
><p>Indicates the URL from which the request came from</p>

```
Referer: https://www.google.com/
```

><p><h3>Cookie</h3></p>
>
><p>Information the web server previously asked the web browser to store is held in cookies.</p>

```
Cookie: user_type=student; room=introtowebapplication; room_status=in_progress
```

><p><h3>Content-Type</h3></p>
>
><p>Describes what type or format data is in the request.</p>

```
Content-Type: application/json
```

<p><h1>Request Body</h1></p>

><p>This is the data from the POST or PUT request, otherwise known as the Request Body.</p>
>
><p>A request body can come in many forms such as URL Encoded, Form Data, JSON, or XML.</p>
>
>><p><h3>URL Encoded (applicaiton/x-www-form-urlencoded)</h3></p>
>
>><p>A format where data is structure in pairs of key and value where(key=value).<br>
>>Multiple pairs are separated by an "&" symbol such as,</p>

```
key1=value&key2=value
```
```
POST /profile HTTP/1.1
Host: github.com
User-Agent: Mozilla/5.0
Content-Type: application/x-www-form-urlencoded
Content-Length: 33

name=Ch1c4g0&age=25&country=NZ
```
<p><h1>Form Data (Multi-Part/Form Data)</h1></p>
<p>Allows multiple data blocks to be sent where each block is separated by a boundary string.</p>

```
POST /upload HTTP/1.1
Host: tryhackme.com
User-Agent: Mozilla/5.0
Content-Type: multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW

----WebKitFormBoundary7MA4YWxkTrZu0gW
Content-Disposition: form-data; name="username"

aleksandra
----WebKitFormBoundary7MA4YWxkTrZu0gW
Content-Disposition: form-data; name="profile_pic"; filename="aleksandra.jpg"
Content-Type: image/jpeg

[Binary Data Here representing the image]
----WebKitFormBoundary7MA4YWxkTrZu0gW--
```

<p><h1>JSON (Application/JSON)</h1></p>
<p>In this format, you send data in JavaScript Object Notation.<br>
Theses are stored like functions within python, (name=value), separated line-by-line, commas, and enclosed<br>
in curly brackets.</p>

```
POST /api/user HTTP/1.1
Host: tryhackme.com
User-Agent: Mozilla/5.0
Content-Type: application/json
Content-Length: 62

{
    "name": "Aleksandra",
    "age": 27,
    "country": "US"
}
```
