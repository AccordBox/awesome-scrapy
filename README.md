# Awesome Scrapy [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) 

> A curated list of awesome packages, articles, and other cool resources from the Scrapy community.
> [Scrapy](https://github.com/scrapy/scrapy) is a fast high-level web crawling & scraping framework for Python.

## Table of Contents

- [Apps](#apps)
    - [Visual Web Scraping](#visual-web-scraping)
    - [Distributed Spider](#distributed-spider)
    - [Scrapy Service](#scrapy-service)
    - [Front-End Scrapy Managers](#front-end-scrapy-managers)
    - [Monitor](#monitor)
    - [Avoid Ban](#avoid-ban)
    - [Data Processing](#data-processing)
    - [Process Javascript](#process-javascript)
    - [Other Useful Extensions](#other-useful-extensions)
- [Resources](#resources)
    - [Articles](#articles)
    - [Exercises](#exercises)
    - [Video](#video)
    - [Book](#book)

## Apps

### Visual Web Scraping

* [Portia](https://github.com/scrapinghub/portia) Visual scraping for Scrapy

### Distributed Spider

* [scrapy-cluster](https://github.com/istresearch/scrapy-cluster) Distributed on demand scraping cluster using Redis and Kafka.
* [scrapy-redis](https://github.com/rmax/scrapy-redis) Redis-based components for Scrapy.

### Scrapy Service

* [scrapyscript](https://github.com/jschnurr/scrapyscript) Run a Scrapy spider programmatically from a script or a Celery task - **no project required.**

* [scrapyd](https://github.com/scrapy/scrapyd) A service daemon to run Scrapy spiders

* [scrapyd-client](https://github.com/scrapy/scrapyd-client) Command line client for Scrapyd server

* [python-scrapyd-api](https://github.com/djm/python-scrapyd-api) A Python wrapper for working with Scrapyd's API.

* [SpiderKeeper](https://github.com/DormyMo/SpiderKeeper) A scalable admin ui for spider service

* [scrapyrt](https://github.com/scrapinghub/scrapyrt) HTTP server which provides API for scheduling Scrapy spiders and making requests with spiders.

### Front-End Scrapy Managers

* [Gerapy](https://github.com/Gerapy/Gerapy) Distributed Crawler Management Framework Based on Scrapy, Scrapyd, Scrapyd-Client, Scrapyd-API, Django and Vue.js

* [SpiderKeeper](https://github.com/DormyMo/SpiderKeeper) admin ui for scrapy/open source scrapinghub.

* [ScrapydWeb](https://github.com/my8100/scrapydweb) Scrapyd cluster management, Scrapy log analysis & visualization, Basic auth, Auto packaging, Timer Tasks, Email notice, and Mobile UI.

### Monitor

* [scrapy-sentry](https://github.com/llonchj/scrapy-sentry) Logs Scrapy exceptions into Sentry

* [scrapy-statsd-middleware](https://github.com/zachgoldstein/scrapy-statsd) Statsd integration middleware for scrapy

* [scrapy-jsonrpc](https://github.com/scrapy-plugins/scrapy-jsonrpc) An extension to control a running Scrapy web crawler via JSON-RPC

* [scrapy-fieldstats](https://github.com/stummjr/scrapy-fieldstats) A Scrapy extension to log items coverage when the spider shuts down

* [spidermon](https://github.com/scrapinghub/spidermon) Extension which provides useful tools for data validation, stats monitoring, and notification messages.

### Avoid Ban

* [HttpProxyMiddleware](https://github.com/kohn/HttpProxyMiddleware) A middleware for scrapy. Used to change HTTP proxy from time to time.

* [scrapy-proxies](https://github.com/aivarsk/scrapy-proxies) Processes Scrapy requests using a random proxy from list to avoid IP ban and improve crawling speed.

* [scrapy-rotating-proxies](https://github.com/TeamHG-Memex/scrapy-rotating-proxies) Use multiple proxies with Scrapy

* [scrapy-random-useragent](https://github.com/cnu/scrapy-random-useragent) Scrapy Middleware to set a random User-Agent for every Request.

* [scrapy-fake-useragent](https://github.com/alecxe/scrapy-fake-useragent) Random User-Agent middleware based on fake-useragent

* [scrapy-crawlera](https://github.com/scrapy-plugins/scrapy-crawlera) Crawlera routes requests through a pool of IPs, throttling access by introducing delays and discarding IPs from the pool when they get banned from certain domains, or have other problems.

### Data Processing

* [scrapy-elasticsearch](https://github.com/knockrentals/scrapy-elasticsearch) A scrapy pipeline which send items to Elastic Search server

* [scrapy-mongodb](https://github.com/sebdah/scrapy-mongodb) MongoDB pipeline for Scrapy.

* [scrapy-mysql-pipeline](https://github.com/IaroslavR/scrapy-mysql-pipeline) MySQL pipeline to persist items in MySQL databases.

* [scrapy-s3pipeline](https://github.com/orangain/scrapy-s3pipeline) Scrapy pipeline to store chunked items into AWS S3 bucket

* [scrapy-sqs-exporter](https://github.com/multiplechoice/scrapy-sqs-exporter) Scrapy extension for outputting scraped items to an Amazon SQS instance

* [scrapy-kafka-export](https://github.com/TeamHG-Memex/scrapy-kafka-export) Scrapy extension which writes crawled items to Kafka

* [scrapy-rss-exporter](https://github.com/ljanyst/scrapy-rss-exporter) An RSS exporter for Scrapy

### Process Javascript

* [scrapy-playwright](https://github.com/scrapy-plugins/scrapy-playwright) Enable scraping dynamic pages using PlayWright.
* [scrapy-puppeteer](https://github.com/clemfromspace/scrapy-puppeteer) Make Scrapy and Puppeteer work together to handle Javascript-rendered pages.
* [scrapy-splash](https://github.com/scrapy-plugins/scrapy-splash) Make Scrapy can understand Javascript

### Other Useful Extensions

* [scrapy-djangoitem](https://github.com/scrapy-plugins/scrapy-djangoitem) Scrapy extension to write scraped items using Django models

* [scrapy-deltafetch](https://github.com/scrapy-plugins/scrapy-deltafetch) Scrapy spider middleware to ignore requests to pages containing items seen in previous crawls

* [scrapy-crawl-once](https://github.com/TeamHG-Memex/scrapy-crawl-once) This package provides a Scrapy middleware which allows to avoid re-crawling pages which were already downloaded in previous crawls.

* [scrapy-magicfields](https://github.com/scrapy-plugins/scrapy-magicfields) Scrapy middleware to add extra fields to items, like timestamp, response fields, spider attributes etc.

* [scrapy-pagestorage](https://github.com/scrapy-plugins/scrapy-pagestorage) A scrapy extension to store requests and responses information in storage service.

* [itemloaders](https://github.com/scrapy/itemloaders) Library to populate items using XPath and CSS with a convenient API.

* [itemadapter](https://github.com/scrapy/itemadapter) Adapter which provides a common interface to handle objects of different types in an uniform manner.

* [scrapy-poet](https://github.com/scrapinghub/scrapy-poet) Page Object pattern implementation which enables writing reusable and portable extraction and crawling code.

## Resources

### Articles

* [Scrapy VS Beautiful Soup](https://blog.michaelyin.info/2017/08/10/scrapy-tutorial-1-scrapy-vs-beautiful-soup/)

* [Scrapy VS Selenium](https://blog.michaelyin.info/2017/11/06/web-scraping-framework-review-scrapy-vs-selenium/)

* [Web Scraping in Python using Scrapy (with multiple examples)](https://www.analyticsvidhya.com/blog/2017/07/web-scraping-in-python-using-scrapy/)

* [Scrapy Tutorial Series: Web Scraping Using Python](https://www.accordbox.com/blog/scrapy-tutorial-series-web-scraping-using-python/)

* [Advanced Web Scraping: Bypassing "403 Forbidden," captchas, and more](http://sangaline.com/post/advanced-web-scraping-tutorial/)

### Exercises

* [Learn and improve web scraping skills with Web Scraping Exercises](https://scrapingclub.com/)

### Video

* [Scrapy: Powerful Web Scraping & Crawling with Python](https://www.udemy.com/scrapy-tutorial-web-scraping-with-python/) Online courses on Udemy

### Book

* [Learning Scrapy](https://www.amazon.com/Learning-Scrapy-Dimitrios-Kouzis-Loukas/dp/1784399787/ref=nosim?tag=where2buyit-20)
