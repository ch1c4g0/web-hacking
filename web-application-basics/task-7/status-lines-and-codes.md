

<p><h1>Status Codes</h1></p>
<p>When you interact with a web server it sends back an HTTP Response.<br>
This informs us of the status of our interaction.</p>

<p>These responses include a status code and a short explaination called the Response Phrase.</p>

<p><h1>Status Line</h1></p>

><p>This is the first three lines of every status line, it provides the following info.</p>
>
>><p>HTTP Version: the version of HTTP used.</p>
>><p>Status Code: a three-digit number showing the outcome of the request.</p>
>><p>Reason Phrase: a short explaination of the status code but human-readable.</p>

<p><h1>Status Codes and Reason Phrases</h1></p>
<p>The status code tells you if the request succeeded or failed,<br>
the Reason Phrase explains what happened.</p>

><p>Here are the categories,</p>
>
> - Informational Responses (100-199)
>These codes mean the server has received part of the request and is waiting for the . It’s a "keep going" signal.
>
> - Successful Responses (200-299)
>These codes mean everything worked as expected. The server processed the request and sent back the requested data.
>
> - Redirection Messages (300-399)
>These codes tell you that the resource you requested has moved to a different location, usually providing the new URL.
>
> - Client Error Responses (400-499)
>These codes indicate a problem with the request. Maybe the URL is wrong,<br>
>or you’re missing some required info, like authentication.
>
> - Server Error Responses (500-599)
> - These codes mean the server encountered an error while trying to fulfil the request.<br>
>These are usually server-side issues and not the client’s fault.

><p><h1>Common Status Codes</h1></p>
>
> - 100 (Continue)
>The server got the first part of the request and is ready for the .
>
> - 200 (OK)
>The request was successful, and the server is sending back the requested resource.
>
> - 301 (Moved Permanently)
> The resource you’re requesting has been permanently moved to a new URL. Use the new URL from now on.
>
> - 404 (Not Found)
>The server couldn’t find the resource at the given URL. Double-check that you’ve got the right address.
>
> - 500 (Internal Server Error)
>Something went wrong on the server’s end, and it couldn’t process your request.
