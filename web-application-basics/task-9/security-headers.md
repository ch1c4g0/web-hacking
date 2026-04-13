

<p><h1>Security Headers</h1></p>

<p>Security headers help improve the overall security of the web application by providing mitigations against attacks like XSS, clickjacking, and others.</p>

<p>The following are all examples of security headers,</p>

> - Content-Security-Policy(CSP)
> - Strict-Transport-Security(HSTS)
> - X-Content-Type-Options
> - Referrer-Policy

https://securityheaders.io/

<p><h2>Content-Security-Policy(CSP)</h2></p>

<P>A CSP Header is an additional security layer to mitigate attacks like XSS. A CSP dictates what domains are considered safe and provides a layer of mitigation to attacks.</P>

<p>You may see default-src or script-src defined in these headers. Each of these provide options to administrators as well as granularity and what domains are allowed for certain kinds of content.</p>

<P>Example:</P>

```
Content-Security-Policy: default-src 'self'; script-src 'self' https://github.com; style-src 'self'
```

<p><h2>CSP Option Headers:</h2></p>

<P>default-src: specifies default policy of self (only the current website)</P>

<p>script-src: specifies policy for where scripts can be loaded from, which is self along with scripts hosted on https://github.com</p>

<p>style-src: specifies the policy for where style CSS style sheets can be loaded from the current website(self)</p>
