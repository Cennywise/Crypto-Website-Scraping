# Crypto Web Scraping

CoinMarketCap.com is a website that displays up-to-date information on cryptocurrencies such as Bitcoin, Ethereum, and Dogecoin. They also provide an API that allows users to scrape this data and use it themselves.

In my script, I incorporate the API into a function, run_api(). It scrapes the site data and records it in a CSV file. It also has a 1-minute sleep timer built in, and the idea is to run the program continuously in the background for it to collect data. I have it set for testing purposes, though, so it stops after running for 5 min. Then from this data, I extract the top 10 cryptocurrencies and plot their recorded growth over various time periods.

![Crypto Graph](Growth_Graph.png)
