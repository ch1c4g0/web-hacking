

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
