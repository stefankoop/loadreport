# loadreport.js
[PhantomJS](http://www.phantomjs.org/) 1.6+ is required to run loadreport.js or speedreport.js.

loadreport will write, to csv or json (filmstrip writes to png):
## loadreport Examples
    > phantomjs loadreport.js http://wesleyhales.com performance csv
    > phantomjs loadreport.js http://wesleyhales.com performancecache json
    > phantomjs loadreport.js http://wesleyhales.com filmstrip

speedreport produces a json and html file which will display detailed resource charting
## speedreport Examples
    > phantomjs speedreport.js http://www.wesleyhales.com

