

<p><h1>What is an HTTP Request?</p></h1>

<p>An HTTP Request is what a user sends a web srver to interact with a web application.<br>
These are the first points of contact between the user and the web server.</p>

![http-request-image](https://github.com/ch1c4g0/web-hacking/blob/c517b5831aaff9cbbee47a47a19310315b6b93d0/web-application-basics/screenshots/http-requests.png.png)

<p><h1>The moving parts,</h1></p>

><p><h3>Request Line</h3></p>
><p>This is the first part of an HTTP Request, it tells the server what kind of request it's dealing with.</p>
>
>><p>It has three main parts,
>
>HTTP Method, URL Path, and HTTP Version.</p>

```
Example: METHOD/path HTTP/version
```

<p><h3>HTTP Methods</h3></p>
<p>HTTP Methods tell the server what action the user wants to perform.</p>

<p>The most common methods,</p>

><p><h3>GET</h3></p>
>
><p>Used to fetch data from the server without making any changes.</p>
<p>Note, passwords, token, and other sensitive data should not be sent in GET requests.</p>

><p><h3>POST</h3></p>
>
><p>Used to send data to the server.</p>
<p>Input validation and sanitization is super important here.</p>

><p><h3>PUT</h3></p>
>
><p>Used to replace or update data on the server</p>
<p>Note, ensuring user is authorised to make changes before allowing the request.</p>

><p><h3>DELETE</h3></p>
>
><p>Used to remove data from the server.</p>
<p>Just like PUT, only authorised users should be able to send DELETE requests.</p>

<p><h1>Less Common HTTP Requests,</h1></p>
