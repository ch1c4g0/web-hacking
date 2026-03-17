

<p><h1>What is a URL?</h1></p>
<p>A web address that lets you access all kinds of content,<br>
this may be a webpage, a video, a photo, or other media.</p>

<p><h3>A URL can be broken down into 8 categories all serving a different function,</h3></p>

![url-componenets](https://github.com/ch1c4g0/web-hacking/blob/5c76ba6749135278e490bf4382495f8258555a27/web-application-basics/screenshots/Screenshot%202026-03-15%20at%2012-02-49%20TryHackMe%20Web%20Application%20Basics.png)

<p><h3>Scheme's</h3></p>
<p>This is the protocol used to access the resources most commonly HTTP and HTTPs</p>

<p><h3>Usernames and Credentials</h3></p>
<p>This is lest common as putting credentials within a URL is a security risk.<br>
It is important to bring up as it has been done in the past and you may rarely see it now.</p>

<p><h3>The Host / Domain</h3></p>
<p>This is the name of the website your visiting, each domain name is unique.</p>

<p><h3>Port</h3></p>
<p>The port number helps your browser find the right service hosted on the web-server,<br>
most commonly 80 and 443 for HTTP and HTTPs</p>

<p><h3>Path</h3></p>
<p>The directory within the web server you are trying to reach.</p>

<p><h3>Query Strings</h3></p>
<p>These are the strings that start with "?" often used for search terms or forms of input.</p>

<p><h3>Fragments</h3></p>
<p>These point to a specific resource within a web page. This, like query strings, are subject to user input.</p>

<p><h1>HTTP Requests / Responses</h1></p>

<p>An HTTP request is sent by yourself a HTTP Response is sent by the Web Server.<br>
These requests/responses can be broken down into four categories,</p>

<p><h3>Start Line</h3></p>
<p>Provides information such as, request / response identificaiton, and how the message should be handled.</p>

<p><h3>Headers</h3></p>

<p>A lot is covered here, security, content type, instructions for both client and server, and more.</p>

<p><h3>Empty Line</h3></p>

<p>This separates the header and the body. It shows where the header stops, and where actual content begins.</p>

<p><h3>Body</h3></p>

<p>This is stored data, it may be sent, or requested.</p>
