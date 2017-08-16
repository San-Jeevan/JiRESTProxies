
![How the proxy works](https://github.com/San-Jeevan/JiRESTProxies/raw/master/JirestIllustration.png)

The JiRest will send the query information to the proxy which executes it and sends back the response raw.
The proxy is necessary due to limitation in todays browsers. There are restrains:

- Cors (cross origin resource sharing) problem
- Setting of cookie in a header
- Certain packet headers in request and response are not visible to the browser.


You can host your own proxies. Remember you need to make sure you setup SSL or the proxy will not work as browser will block "insecure" requests.

Currently we have proxy in following languages:
* C#
* Azure Functions (C#)
* Node.js
* Java


We are working on python version and Go.

