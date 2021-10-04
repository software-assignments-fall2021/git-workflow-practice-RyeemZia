# Git Practice
## My Favorite Website Related to SoftwareEngineering/Engineering
https://hackernoon.com/web-scraping-with-javascript-and-nodejs

This article pertains to websrcraping with node.js. In the past I have worked mainly with Python webscraping, so I was already aware of some of the basic themes. However, as node.js is so important for web development, it only made sense to learn how to do it web sraping with JavaScript. 

From the article, it seems like this task is done by creating code that directly analyzes the html and catches lines we preset as being of interest. Further, we use an asyncronous arrow function to crawl through this html. We import a few libraries to help us, inluding: 
const axios = require('axios');  
const playwright = require('playwright');  
const cheerio = require('cheerio');  

