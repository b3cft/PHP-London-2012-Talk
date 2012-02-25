PHP London Conference 2012 24/25 Feb
====================================

My talk entitled "Monitoring your backend for speed and profit"

You can either clone this repo or click on these two links for the downloadable copies of this talk.

[PDF Version of the talk](http://www.kingkludge.net/MonitoringYourBackendForSpeedAndProfit.pdf) 35Mb
[PowerPoint Version of the talk](http://www.kingkludge.net/MonitoringYourBackendForSpeedAndProfit.pptx) 22Mb.

Please review my talk on [Joind.in](http://joind.in/4964) if you saw it in person.

Synopsis:
---------
At the BBC we are preparing for the some big events in the coming year (the Olympics amongst them), as we don't have to cash to splash on new hardware in the current economic climate and our frozen license fee.

The BBC runs approximate 300 websites all contained with bbc.co.uk and running on the same hardware. This means that a spike in traffic on /weather affects /iplayer and all other sites hosted on our platform.

This talk will show some of the things we've been doing to benchmark our platform (the PHP, ZF portion anyway) and highlight poor performing sections of our site and address them.

I will explain some of the tools we've written and technologies we've used to achieve this on a relatively short timescale with limited budget.

This will cover our experience of using XHProf for the first time and augmenting Zend Framework to generate HAR (Http Archive) format files to expose the service calls our platform makes and how we’ve approached optimising them.

I will then cover, briefly, how we’ve modified our platform to make it as cacheable as possible and the use of Varnish to offset the hits directly on the platform by adding device detection and GeoIP look ups into the caching layer.


