# Statistical-Data-Analysis
## Calgary & Edmonton Weather Comparison

### Purpose/Motivation:
There are several reasons to investigate the weather change in Calgary vs. Edmonton:  
- To determine if Alberta’s local environment is trending the same way as the global warming over the past 30 years. Earth’s temperature has risen by 0.08° C per decade since 1880 (Lindsey, R and Dahlman, L., 2021). Global warming is a serious threat that will cause things such as a rise in warm temperature extremes, an increase in heatwaves occurring more naturally, risks of floods and droughts (depending on the location), negative impacts on biodiversity and ecosystems, and less food availability (Buis, A. (2019)). This leads us to the first question we want to answer: Is Alberta’s local weather trending the same way as the global warming over the past 30 years?  
- To investigate Calgary’s local weather patterns. For example, this information can be used to provide educated advice (like travel tips, what to pack, what to expect) for different seasons in Calgary. This leads us to the second question we want to answer: What are Calgary’s local weather patterns like? What advice would be suggested to travelers coming to Calgary for each season?  
- To investigate if Calgary and Edmonton have similar weather. Since the two cities are geograph- ically closed to each other, it is likely that there is the belief that they are theoretically quite correlated in terms of weather. As such, the strength of this association will be explored to see if data in one location can be used to to predict the other. This leads us to the third question we want to answer: How do Calgary and Edmonton’s weather compare?  
- To investigate the questions above, the populations analyzed will be the temperature and precipitation in Calgary and Edmonton over the past 30 years. The parameters to be investigated related to these questions are the true mean, max, and min of temperature and precipitation for each city. It is important to note that the data set contains mean temperatures over a 24 hour period. Although some days can reach temperatures of -30 degrees or +30 degrees, it is rare that the entire 24 hour period would experience such temperatures. The report will consider days with a mean temperature of >20 degrees and <-20 degrees as hot and cold days, respectively.

### Statistical Analysis:
#### To gain an understanding of the data, the following visualizations were created:
- Box plot to show the spread of each city’s temperature and precipitation • Scatter plot to explore nature of the relationship between variables
- Histogram to show underlying distribution
- Barplot to show the values in the categorical variable

#### To answer Question 1, the following visualizations and statistical methods were used:
- Calculated table and scatter plot difference to show the the temperature/precipitation change overtime
- Linear Regression Model for Calgary & Edmonton temperature change over time
#### To answer Question 2, the following visualizations and statistical methods were used:
- 95% confidence interval for Calgary’s mean temperature and precipitation (estimation of one population mean)
- 95% confidence interval for Calgary’s mean precipitation (bootstrap)
- Bar plot to compare the mean value of cities
- P-value test for Calgary’s true mean temperature in its hottest and coldest months (estimation of
one population mean)
- 95% confidence interval for mean number of days in a year that are below -20 degrees and above
+20 degrees each year
#### To answer Question 3, the following visualizations and statistical methods were used:
- Line plots to show the min and max temperatures for each city during summer and winter
- Simple linear regression to determine if there is a correlation between each city’s mean temperature • Pairwise plot to show temperature association between cities
- qqplot to check normality assumption for linear regression model
- Hypothesis testing:
  * To determine which city will have a colder winter or warmer summer (two-sample mean test (mean_coldest_calgary - mean_coldest_edmonton) or (mean_hottest_calgary - mean_hottest_edmonton) )
  * To determine which city has a higher proportion of days above 0 degrees (two sample population p1-p2 test)
  * To determine if there is a difference between each city’s mean temperature (estimation of two population difference (mean_calgary - mean_edmonton))
  * To determine if each city’s variance in precipitation and temperature is equal (test of equal variances)

