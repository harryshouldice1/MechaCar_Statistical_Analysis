# MechaCar_Statistical_Analysis

## Overview
Using ggplot2, utilize line, bar, and scatter plots to visualize sets of data.
Also use boxplots and heatmaps.
Use simple linear regression and multiple linear regression.
Use one-sample t-tests, two-sample t-tests, and ANOVA models.
Figure out which test makes the most sense to use for a given hypothesis.

## Linear Regression
![Screenshot (61)](https://user-images.githubusercontent.com/109995136/204914263-9258f5c8-6ac9-4f39-8b3a-4aa071802b91.png)

![Screenshot (60)](https://user-images.githubusercontent.com/109995136/204914457-55aab877-26d2-4744-9c44-939d1cac47ff.png)
There was a 95% confidence. Alpha is .05.

## Summary Statistics
### Lot Summary
![Screenshot (62)](https://user-images.githubusercontent.com/109995136/204915012-50f572f8-e631-49cd-bf18-c4bc57952214.png)
The mean is 1498.78 and the population mean was determined to be 1500.
### Lot Number
![Screenshot (63)](https://user-images.githubusercontent.com/109995136/204915227-c887a2dc-fe0d-4423-9c63-4880f01013ac.png)
Similar to population and sample mean.

## T-Tests
### T-Test for all Lots
![Screenshot (64)](https://user-images.githubusercontent.com/109995136/204915615-90d26e7b-99e0-4f49-9444-3b99cb69b6cf.png)
### T-Test for Lot 1
![Screenshot (65)](https://user-images.githubusercontent.com/109995136/204915733-90014500-0838-431a-8f63-c7e5b94a089b.png)
### T-Test for Lot 2
![Screenshot (66)](https://user-images.githubusercontent.com/109995136/204915816-a437cfac-245a-47e6-b7c0-f6e63fd9b471.png)
### T-Test for Lot 3
![Screenshot (67)](https://user-images.githubusercontent.com/109995136/204915933-ea05f6f2-354c-46d2-88ac-5d3afa5e8624.png)
Normal distribution was shown for Lots 1 and 2, meaning that there is not significant evidence to reject the null hypothesis.  The two means are similar.

## Study Design: MechaCar vs Competition
Areas of interest to consumers include cost, city fuel efficiency, highway fuel efficiency, horse power, maintenance cost, and safety rating.
### What would be used to test?
Safety rating, horsepower, and highway fuel efficiency are most important to a consumer's safety concerns.
### Null and Alternative hypothesis
Null hypothesis: The mean of the safety rating is 0
Alternative hypothesis: The mean of the safety rating is not 0
### What Test?
Multiple linear regression would be best because it would show how certain variables affect the saftey ratings for both MechaCar and the competition.
### How do we run it?
Random sample of n > 30 for MechaCar and competition that includes safety ratings, highway fuel efficiency, and horsepower.
Also run data through RStudio.
