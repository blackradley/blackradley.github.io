---
layout: default
tags:
- Collins
---
# {{ page.title }}

By Joe Collins

Our [Insight](https://insight.blackradley.com) web application needs to use SSL (Secure Sockets Layer) because the data we are gathering is valuable and needs to be protected.  But also, Google deliberately favors websites that use SSL as part of company policy to make the internet safer, so using SSL will improve the web applications search ranking.

Traditionally setting up SSL certificates has always been a rather irksome task.  There are a number of arcane steps that need to be taken to acquire and set up an SSL certificate on the web server.  For this reason the web application developers had been avoiding the task and pushing it back to nearer the go live date.

The web application is deployed on the Windows Azure cloud platform.  Along with all the major cloud vendors the platform is rapidly developing.  So our web application developers have been attending seminars to ensure that they remain aware of how the cloud offering is changing.  At a seminar lead by [Mark Rendle](http://blog.markrendle.net/), a UK based Windows Azure MVP, Mark mentioned that he was using [Cloud Flare](http://cloudflare.com/) as a CDN (Content Delivery Network) which had the side benefit of providing free and convenient SSL as well.  All for free.

I set up CloudFlare on our live web application in a matter of hours.  Using CloudFlare provides SSL resolving the projects need for security and an improved search ranking and has the side effect of improving the performance of the web application. 

![Insight Logo](/img/InsightLogo.jpg)
