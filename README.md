# Comparing ESG scores for companies by industry sector
Exploratory data analysis of ESG ratings and stock data for companies in the Industrials sector 

![truck](https://github.com/Jenkir/EDA-ESG-ratings-Industrials/assets/75215001/935cfb87-23db-4ddd-80d5-542f83127e2d)

When comparing ESG scores of different companies, it's important to compare a company against its peers in the same sector or industry. One framework used for classifying companies is the [Global Industry Classification Standard (GICS)](https://www.msci.com/our-solutions/indexes/gics)  which includes 11 overarching sectors, and then further narrows down the classfication to 25 industry groups, 74 industries, and then into 163 subindustries. The way that a company is classified primarily depends on its main revenue source. 

Each industry has different **material issues** that are the most pertinent to how it conducts business as well as the most important to stakeholders.  ESG metrics will vary depending on what a company considers its material issues to be. Each industry or sector will have similar material issues. For example, the material issues of a bank (Financial sector) will be different than that of a company that produces cleaning products (Consumer Staples sector). A bank will track different ESG metrics than a cleaning products company although some metrics will be the same (such as how the board of directors is governed).

In this project, we explore the ESG ratings of companies in the GICS Industrials sector. The data was primarily pulled from [ESGAnalytics.io[(https://www.esganalytics.io/) and [Finazon.io](https://finazon.io/). ESG Analytics extracts over 1 million data points per month to "to deliver a third-party perspective on company ESG performance." Using AI, they generate ESG scores based on analyzing unstructured text from media stories, press releases, and other publicly available information. They provide data for over 10,000 companies (mostly public and some private). Finazon is a "marketplace for global financial data APIs"providing real-time stock market data.

This project also includes ESG scores from other ratings providers such as Sustainalytics, S&P Global, and MSCI. 

The EDA for this project includes discovering the mean and median ESG scores for companies in this sector, which subindustries are included in this sector (such as Industrial Machinery, Trucking, and Commercial Printing), the frequency of ESG ratings for companies in this sector, and which companies in the trucking subindustry have the highest and lowest scores.



![trucking-chart](https://github.com/Jenkir/EDA-ESG-ratings-Industrials/assets/75215001/8dc3da1f-9d02-4884-ac5c-6fef33f033d6)



**If you would like to do your own exploratory data analysis of ESG ratings, please see [esgdatashop.io](https://esgdatashop.io/).**
