# quant_api
Abandonned project for now as I must prioritize other tasks. 

Python3/Flask Web API to serve data.

items:

* serving data in multiple form
  * csv
  * json
  * html (maybe an R report)
* serving data from multiple datasources 
  * oracle
  * postgres
  * hadoop
  * files on the system
  * webscraping on request
* offering querylike properties between multiple datasets
  * offering an answer by combining oracle + files + webscraper
* offering security through authentication and SSL
  * api key / password
  * implementing SSL
* creating a cache to simulate minimum data "freshness" and protecting the datasources from abuse
  * some data available fresh on demand
  * some data coming from daily extract
  * some data coming from an external database with a freshness of 15 mins
* offering machine-learning services for models created on the host
  * predict price in 2 weeks with model Y
  * following model J is there a stock to buy right now
* statistical analysis
  * correlated stocks, positive and negative
  * offsetted (choose a number of days) correlated stocks
  * average bull period % gain and \# of days

