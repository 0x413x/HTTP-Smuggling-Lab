#	HTTP-Smuggling-Lab

You can learn more in [Help you understand HTTP Smuggling in one article](https://blog.zeddyu.info/2019/12/08/HTTP-Smuggling-en/) or the chinese version [一篇文章带你读懂 HTTP Smuggling 攻击](https://blog.zeddyu.info/2019/12/05/HTTP-Smuggling/).



This repo is about learning HTTP Smuggling.



In Lab1, we will chain some Reverse Proxy relations, Nginx will be the final backend, HaProxy the front load balancer, and between Nginx and HaProxy we will go through ATS6 or ATS7 based on the domain name used (dummy-host7.example.com for ATS7 and dummy-host6.example.com for ATS6).



Lab2 uses ATS as front server and uses LAMP and LNMP as backend servers.



Jetty is jetty v9.4.9. You will get more information in [Jetty-README](./jetty/README.md).



Websocket Lab is about the websocket http smuggling. You will get more information in [Websocket-README](./websocket/lab1/README.md).



Thanks to @regilero and mengchen@Knownsec 404 Team.

Hope u enjoy it!