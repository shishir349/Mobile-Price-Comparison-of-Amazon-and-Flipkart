# Mobile Price Comparison of Amazon and Flipkart


Web scraping has become an effective way of extracting information from the web for decision making and analysis. It has become an essential part of the data science toolkit. Data scientists should know how to gather data from web pages and store that data in different formats for further analysis.

Any web page you see on the internet can be crawled for information and anything visible on a web page can be extracted [2]. Every web page has its own structure and web elements that because of which you need to write your web crawlers/spiders according to the web page being extracted.

Scrapy uses spiders, which are self-contained crawlers that are given a set of instructions [1]. In Scrapy it is easier to build and scale large crawling projects by allowing developers to reuse their code.


Scrapy Vs. BeautifulSoup
In this section, you will have an overview of one of the most popularly used web scraping tool called BeautifulSoup and its comparison to Scrapy.

Scrapy is a Python framework for web scraping that provides a complete package for developers without worrying about maintaining code.

## Creating a Scrapy project and Custom Spider
Web scraping can be used to make an aggregator that you can use to compare data. For example, you want to buy a tablet, and you want to compare products and prices together you can crawl your desired pages and store in an excel file. Here you will be scraping aliexpress.com for tablets information.

Now, you will create a custom spider for the same page. First, you need to create a Scrapy project in which your code and results will be stored. Write the following command in the command line or anaconda prompt.
