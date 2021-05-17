# capstone_2021
This repository will contain all of the necessary files which the project requires.

## Data ##

To see all the dat which was operated upon is within the source located [here.](https://github.com/eric-wisniewski/capstone_2021/tree/main/Files) The folder contains both .xlsx and .csv files, this was done in order to operate on them within R for statistical analysis and forecasting methods. Most sources are from US government agencies, due to many questioning the reliability of sources from the Chinese Government.

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

### Reasoning for Key Points ###

Through research surrounding reports about the tariffs, I found that US automotive, technological, and agricultural industries were impacted the most in the US. Also, China's most affected industries were technological and business goods. Seeing how GDP is a good measure to see where a economy can be measure, this was an easy decision to make in the comparison of the two countries. Looking to examine China's claim was more so a way of deciding who was winning the trade war more. 

## Milestone Tracker ##

![milestone](https://github.com/eric-wisniewski/capstone_2021/blob/main/Files/milestone%20tracker.png)

## Analysis ##

### US Agriculture Exports ###

![Agriculture](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_Exp_Agr_Comp.png)

Getting the data from the United States Department of Agriculutre, a reliable government agency, I wanted to observe the trends two years prior, and two years after the tariffs began. I decided to cut down the main exports from US to China to three main crops. Soybeans, Wheat, and Cotton. To really observe how affected the farmers were, I compared the total exports of the crops in the world to only China. The only missing values are exports of wheat to China in 2018 & 2019 due to China being top 10 in exports for these goods. 

* Soybeans
	> Within the graphic there is a clear decline from 2016 to 2018, with 2018 being the lowest year. Even though the exports to China dropped drastically, the US was still able to find many other suitors for this good, but it still did take a hit. Dropping from 57 million metric tons to 46, the farmers were affected, but still maintained a foothold and were able to recover in the following years. Overall the US economy did not take a massive blow.

* Wheat & Cotton
	> Although wheat exports are much more prevalent then cotton, exports to China for either good are not very high. The wheat crop may have been affected more, dropping from 27 miilion metric tons to 22, the following it year it leveled out around 26. Cotton saw a small but steady increase throught the whole time.

### US Vehicle Domestic Production & Sales ###

![tot](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/Prod_DomSal_tot.png)

![domesProdSales](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_Prod_DomSale_Car.png)

The data is from the Bureau of Trasportation, and contains total production (for passenger cars and commercial vehicles), and total domestic sales (also for passenger cars and commercial vehicles). This dataset spans from 1960 to 2019, but from 1960 to 1990 they only recorded values every 5 years. The visual on the top is a double bar chart which shows the pattern throughout the whole time period, the second graphic depicts a more recent depiction. As you can see there is a clear negative spike around 2008 & 2009, this occured due to great recession. If we compared the great recession to the tariffs in 2018, we can see that the tariffs had little to no impact on domestic sales and production. This is evidence against the claim that China made towards the US. We can see that the lack of imports from China did not have a huge impact towards the domestic US automotive industry.  

### US & China Vehicle Total Market Volumes ###

![carComp](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_Car_Comp.png)

![totCar](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_Car_tot.png)

![carGrowthComp](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_Car_Growth_Comp.png)

Not being satisified with just domestic US automotive data, I wanted to gather car sales data from both countires. These datasets were gathered from car sales base. Data from China in these datasets did not start until 2006 and US data was started in 1970, and both data sets end at 2020. In the first graphic, we can see the total number of vehicles sold from 2008 to 2020. The second figure and are depicted in opposite order, date wise. The second figure is the complete picture from both datasets to see a better overall trend. The third chart is a car sales growth comparison from 2008 to 2020. Since 2009, China's car sales have been greater and most likely will continue beyond this point with the same trend. Since 2018, both the US and China are on the decline with car sales, showing the impact on the overall automotive industry for both countries. Seeing China's sharp rise in sales could cause anxiety for US automotive industries with how quickly they had overtaken the US. This could cause future issues for the future in American automotive businesses if this trend contiues. However, the proof saying the tariffs are hurting America in this case are not supported, seeing both countires faulter after the introduction of said tariffs. 

### US Tech. & Business Imports from China ###

![techImport](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_Tech_11-20.png)

The examination of this data was to see if China was truly hurt by the tariffs. Using United States Census Bureau data on imports from China, a dataset which contains almost every product, I narrowed down my selection to 6 products. The list of products include Computers, Computer accsesories, telecommunications equipment, Business mahcines and equipment, Cell phones and other household goods, and Televisions and video equipment. The data ranges from 2011 to 2020. From the graphic we can conclude since 2018 all but computers took hits and are on the decline. This proof goes against their own claim of the tariffs affecting the US more than to itself, but seeing how China is solely reliant on these goods, we can not assume how great an effect it had on its economy, but there still was a negative effect. 

### US Imports vs. Exports from China (Totals) ###

![1618](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_IM_EX_16-18.png)

![1821](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_IM_EX_18-21.png)

These two graphics split a larger possible graphic into two pieces, one piece ranging form January 2016 to June 2018 to July 2018 to January 2021. These are total values of each month from each year on imports and exports. The difference between the first chart and the second chart (i.e. 2016-2018 & 2018-2021) are not surprising. The first chart shows more trade going on than the second. After the tariffs started in June 2018, the levels dropped to a low in May 2020 and only started picking up after. The differences between Imports and Exports remained at their lowest points between the time of the tariffs and the signing of the Phase 1 deal where sides eased tensions a little bit. This point also goes against China's claim. 

### US vs China GDP ###

![GDP](https://github.com/eric-wisniewski/capstone_2021/blob/main/Graphs/US_CH_GDP_10-21.png)

Looking at GDPs along does not indicate much of a change in eithers economy. They are similar in their trend line with US still having an advantage over China. Once again we see China's claim not holding any weight.

## Forecasting(Not Completed) ##

## Summary(Partial Completetion) ##

* Automotive & Agriculture Industries (US)
	> Looking over all three US industries, I found that the Agricultural Industry had a small affect from the tariffs, but nothing too worrying. China had over half of the imports in 2016 & 2017 in Soybeans, most popular crop, so for the imports to drop a small amount does not mean the affect of the tariffs was terrible for the farmers, yet still had an affect. The domestic US industry was not affected much at all, but total sales of vehicles was affected for both countries negatively. Another trend I found, which was more concerning than the tariffs, was how much more dominant China's sales of vehicles is over the US. This raises other questions on how the US can compete with China in the worldwide automotive industry longterm. 

* Tech & Business Industries (China)
	> The tariffs that were placed have had an effect on the most popular tech and busisness goods from China. Since 2018 all products except computers (from earlier example) have been on the decline. To what degree this is affecting China is unknown to due unreliability of Chinese government sources, but for the top 5 products to be declining in exports must hurt the nation.

* China's Claim: Did US tariffs hurt US more than China?
	> From most singular observations I could see, at least in my research, the US economy was not greatly affected. If we compare it to China's only hurty industry we can partially claim that China must have been hurt the same or more by these tariffs, but with more research and data needed to come to a conclusive answer we can not statistcally make a claim that they are incorrect. In order for China to be correct, not much more than the US could have been affected.    