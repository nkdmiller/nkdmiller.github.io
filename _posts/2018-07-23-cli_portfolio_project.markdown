---
layout: post
title:      "CLI Portfolio Project"
date:       2018-07-23 18:59:31 -0400
permalink:  cli_portfolio_project
---


For my CLI project, I decided to do something a little bit different. I wanted to work with XML files to actually save the activity of the user. This proved to be difficult but I learned a ton. My project is a stock report app that allows the user to check the price of any stock on NASDAQ.com. It also allows the user to see a list of the most active stocks for the day and then see the details of any of those stocks. The cool thing is that the user can actually add stocks to a portfolio. They can modify that portfolio, see a list of their stocks and the current of value their stocks. If you're familiar with the stock market you know that stocks change in value every second. So whenever the user wants to look up a price, a freshly scraped price is given to them. For this reason, the portfolio does not save stock prices just the information that can be used to scrape the price when need be. I did my best to adhere to good Object-Oriented design and refactored several times. I made a total of five classes to avoid redundant code and avoid using hashes.

XML stands for eXtensible Markup Language and is used as a container for data. It is not a programming language and is a lot like HTML. At first glance you would probably think it is HTML. It is very readable to humans and computers if formatted correctly. For more information on XML visit this link:

[](https://www.w3schools.com/xml/default.asp)


Nokogiri has the power to scrape XML. So far in the course we have used this awesome gem to scrape HTML. Scraping XML is similar but has very different syntax. The process of adding, scraping and removing XML took up the bulk of my time with this project. Luckily, a very knowledgeable github user put together this list of Nokogiri's XML syntax:

[](https://github.com/sparklemotion/nokogiri/wiki/Cheat-sheet)

Despite those initial frustrations my CLI app which I call "Stock Report" was a great learning experience and a good start to my professional portfolio. 

