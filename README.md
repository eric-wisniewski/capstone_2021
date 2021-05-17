# capstone_2021
This repository will contain all of the necessary files which the project requires.

## Data ##

To see all the dat which was operated upon is within the source located [here.](https://github.com/eric-wisniewski/capstone_2021/tree/main/Files) The folder contains both .xlsx and .csv files, this was done in order to operate on them within R for statistical analysis and forecasting methods. 

### Data Manipulation ###

In order to get a more precise collection of data to answer I only used partial amounts of data from some of the sources. I also had to manipulate the columns and rows of sources as well. The sources for which I include in this description are Agriculture, US Production & Sales, US & China Import Export Difference, US Imports by Code, and US/China GDP.

* Agriculture
	> For this data set I needed to dowload multiple years in different CSV files, and then convert the top exports, which include soybeans, wheat, and cotton, from each year into a single file.

* US Production & Sales
	> All of the data was operated upon in this case, but when looking at the dataset in it's original form, it was set up that the rows horiztonally contained most of the data. So I had to rearrange the data so the labels were vertically over the values within the data.

* US Imports by Code
	> In the comparison I was looking at with this dataset was Technology & Business imports from China, so I had only gathered the necessary data from the overall dataset. (Both are Included in /Files)

* US/China GDP
	> Seeing how the comparison between the two nations is dealing with a more recent trade escalation, I only used values from 2010 -2021.

* US & China Import Export Difference
	> In this dataset are monthly figures of the imports and exports to and from China. I contained values from January 2016 to January 2021.


## Sources ##

Links for all the datasets in the folder /files are located, as well as notes on the figures:

* [Agriculture](https://www.ers.usda.gov/data-products/foreign-agricultural-trade-of-the-united-states-fatus/us-agricultural-trade-data-update/)
* [US Production & Sales:](https://www.bts.gov/content/annual-us-motor-vehicle-production-and-factory-wholesale-sales-thousands-units) The values in the dataset are measured in "Thousands of Units".
* [US Total Market Sales Volumes](https://carsalesbase.com/united-states-sales-data-market/)
* [China Total Market Volumes](https://carsalesbase.com/china-car-sales-data-market/)
* [US Imports by Code](https://www.census.gov/foreign-trade/statistics/product/enduse/imports/c5700.html)
* [US GDP:](https://www.census.gov/foreign-trade/statistics/product/enduse/imports/c5700.html) Measured in Billions of USD
* [China GDP:](https://tradingeconomics.com/china/gdp) Measured in Billions of USD
* [US & China Import Export Difference:](https://www.census.gov/foreign-trade/balance/c5700.html#2021) Measured in Millions of USD

## Injuiry Question ##
Using data on GDP and public availablity on Imports/Exports on which tariffs were put on, measure effectiveness for both nations and conclude on overall trends which the data implies. Predict short-term and long-term affects if tariffs are still in place as they were when they began.

### Key Points of Examination ###
* Differences in US Automotive, Tech, and Agriculture Industries

* Differences in Tech & Business Imports from China

* GDP Examination

* Examine China's Claim
	> Claim: "Tariffs are effecting US economy more than its own."

## Analysis ##

### US Agriculture Exports ###

![Agriculture](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_Exp_Agr_Comp.png)

Getting the data from the United States Department of Agriculutre, a reliable government agency, I wanted to observe the trends two years prior, and two years after the tariffs began. I decided to cut down the main exports from US to China to three main crops. Soybeans, Wheat, and Cotton. To really observe how affected the farmers were, I compared the total exports of the crops in the world to only China. The only missing values are exports of wheat to China in 2018 & 2019 due to China being top 10 in exports for these goods. 

* Soybeans
	> Within the graphic there is a clear decline from 2016 to 2018, with 2018 being the lowest year. Even though the exports to China dropped drastically, the US was still able to find many other suitors for this good, but it still did take a hit. Dropping from 57 million metric tons to 46, the farmers were affected, but still maintained a foothold and were able to recover in the following years. Overall the US economy did not take a massive blow.

* Wheat & Cotton
	> Although wheat exports are much more prevalent then cotton, exports to China for either good are not very high. The wheat crop may have been affected more, dropping from 27 miilion metric tons to 22, the following it year it leveled out around 26. Cotton saw a small but steady increase throught the whole time.

### US Vehicle Domestic Production & Sales ###

![domesProdSales](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_Prod_DomSale_Car.png)

The data is from the Bureau of Trasportation, and contains total production (for passenger cars and commercial vehicles), and total domestic sales (also for passenger cars and commercial vehicles)

### US & China Vehicle Total Market Volumes ###

![carComp](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_Car_Comp.png)

![carGrowthComp](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_Car_Growth_Comp.png)


### US Tech. & Business Imports from China ###

![techImport](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_Tech_11-20.png)

### US Imports vs. Exports from China (Totals) ###

![1618](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_IM_EX_16-18.png)

![1821](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_IM_EX_18-21.png)

### US vs China GDP ###

![GDP](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_GDP_10-21.png)

