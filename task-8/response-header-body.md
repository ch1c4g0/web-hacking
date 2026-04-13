

<p><h1>Response Headers</p></h1>

<p>This is when a web-server respondes to an HTTP request, they provide key details about the response and inform the client how to handle it.</p>

<p><h1>Crucial HTTP Response Headers</h1></p>

<p>This information is crucial for the client-server communication. Below are a few examples of those required headers.</p>

<p><h2>Date</h2></p>

<P>This shows the exact date and time wehn the response was generated.</P>

```
Date: Fri, 23 Aug 2024 10:43:21 GMT
```
<p><h2>Content-Type</h2></p>

<p>What kind of content it is getting (HTML, JSON, or something else). It will also include the character set (UTF-8) to help properly display the content</p>

```
Content-Type: text/html; charset=utf-8
```

<p><h2>Server</h2></p>
<p>What kind of server software is handling the request. This is often obscured as it gives information into possible attack vectors.</p>

```
Server: nginx
```

<p><h1>Other common Response Headers</h1></p>
<p>These give additional instructions to the client or browser and help control how response is handled.</p>

<p><h2>Set-Cookie</h2></p>
<p>This one sends cookies from the server to the client, which the client will return for future requests. To ensure cookies are secure they should be set with the "HttpOnly" flag(this doesn't allow JavaScript to access them) and the "Secure" flag so they are sent over HTTPs.</p>

```
Set-Cookie: sessionId=38af1337es7a8
```

<p><h2>Cache-Control</h2></p>
<p>Tells the client how long it can cache the response before checking back in with the server. It can also prevent sensitive info from being cached if needed using the (no-cache) flag.</p>

```
Cache-Control: max-age=600
```

<p><h2>Location</h2></p>

<p>Used in redirection (3xx) responses. It tells the client where to go next if the resource has moved. If these are not properly sanitsed, it could lead to open redirect vulnerabilities allow attackers to redirect users to harmful sites.</p>

<p><h1>The Response Body</h1></p>

<p>This is where the actual data lives, HTML, JSON, images, ect. The server sends that back to the client, always sanitise and escape this kind of data (especially user-generated content to prevent injection attacks.</p>
