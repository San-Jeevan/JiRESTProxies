You can host your own proxies. Remember you need to make sure you setup SSL or the proxy will not work as browser will block "insecure" requests.

Currently we have proxy in following languages:
* [C#](https://github.com/San-Jeevan/jirest-proxy-csharp)
* [Azure Functions (C#)](https://github.com/San-Jeevan/jirest-proxy-azurefunc)
* [Node.js (this one is not properly tested, I hired a freelancer.com coder)](https://github.com/San-Jeevan/jirest-proxy-node)
* [Java](https://github.com/San-Jeevan/jirest-proxy-java/)

* Python (planned)
* Go (planned)


![How the proxy works](https://github.com/San-Jeevan/JiRESTProxies/raw/master/JirestIllustration.png)

The JiRest will send the query information to the proxy which executes it and sends back the response raw.
The proxy is necessary due to limitation in todays browsers. There are restrains:

- Cors (cross origin resource sharing) problem
- Setting of cookie in a header
- Certain packet headers in request and response are not visible to the browser.


### Do you have a free proxy for use?
Yes, https://apiendpoint.gressquel.com/api/CorsProxy
It is hosted in Azure cloud in Europe.
We can Azure you that the proxy logs no requests and your privacy is the most important concern for us.



