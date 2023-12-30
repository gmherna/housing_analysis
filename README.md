# Housing Analysis
Thinkful capstone exercise #2.

I work for a fictional banking institution who has allocated additional funds to invest in mortgaged-backed securities. My team has been tasked to analyze housing data and provide recommendations on the type of houses to invest.
My specific task was to conduct statistical analysis, with Microsoft Excel, on the effects of two housing factors on sale price and create a presentation with a recommendation on future investment.

Using a housing database from Kaggle.com, it consisted of 1460 residential homes in Ames, Iowa, with 80 specific data points.
Houses were built from 1872 - 2010 with a sales price ranging from $34,900 - $755,000.
Cleaned, used pivot tables, and conducted statistical analysis to calculate a one-tail p-test to statistically determine if age of houses and pool present had a significant impact on housing prices.

The first factor considered was age of the home.
"New" houses were determined to be between 2006 - 2010.
There are 158 new and 1302 older homes.
The null hypothesis is no statistical significant difference in prices of new and older homes.
The alternate hypothesis is average price of newer homes is significantly higher than older homes.
The result of the analysis was a rejection of the null hypothesis due to a difference of <0.05 p-value.

The second factor considered was if the house had a pool.
The data only provided size of an existing pool, so a house with a pool had any size while a house without a pool has value 0.
There were 7 houses with and 1453 houses without pools.
The null hypothesis is no statistical significant difference in price of houes with or without pools.
The alternate hypothesis is average price of homes with a pool is significantly higher than without a pool.
The result of the analysis was a failed rejection of the null hypothesis, the difference is not significant at the 0.95 level.

Created a presentation with PowerPoint showing statistical analysis with recommendations to key stakeholders on how to invest money in mortgage-backed securities.
