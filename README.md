# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/92553694/152703239-105421ff-0356-4ee2-8a4b-e3a4430df475.png)


From the above picture we can see that: 

* The vehicle length, and vehicle ground clearance are likely to provide non-random amounts of variance to the model. The vehicle length and vehicle ground clearance have a significant impact on miles per gallon on the MechaCar prototype.
* The p-Value for this model is 5.35e-11 which is smaller than the assumed significance level of 0.05%. Which means although the slope of the line is very close to 0 the slope of this linear model is not zero.
* This model has an r-squared value of 0.7149, which means that approximately 71% of all mpg predictions will be determined by this model. This multiple regression model does predict mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/92553694/152705539-a8aa78b9-b3af-4e99-8411-c00356c3dbf1.png)

![image](https://user-images.githubusercontent.com/92553694/152705547-74d737bd-5619-46f9-8536-c09c8781c313.png)

With the understanding that the design specifications for the MechaCar suspension coils mandate that the variance of the suspension coils cannot exceed 100 pounds per square inch (PSI) . When looking at production lot, the variance of the coils is 62.29 PSI, which is within the 100 PSI variance requirement. Lot 1 and Lot 2 are well within the 100 PSI variance requirement, with variances of 0.98 and 7.47 respectively. However, it is Lot 3 that is showing much larger variance in performance and consistency, with a variance of 170.29.

## T-Tests on Suspension Coils

![image](https://user-images.githubusercontent.com/92553694/152707685-4a45d2ab-4650-458f-a6d8-679119e52818.png)

We can see the true mean of the sample is 1498.78, which we also saw in the summary statistics above. With a p-Value of 0.06, which is higher than the common significance level of 0.05, we could say there is not enough evidence to support rejecting the null hypothesis. That is to say, the mean of all three of these manufacturing lots is statistically similar to the presumed population mean of 1500.

![image](https://user-images.githubusercontent.com/92553694/152707703-2fd9e5f7-65bb-4df5-acae-a9627472bd91.png)

Lot 1 sample actually has the true sample mean of 1500. With a p-Value of 1, clearly we cannot reject the null hypothesis that there is no statistical difference between the observed sample mean and the presumed population mean (1500).
Lot 2 has essentially the same outcome with a sample mean of 1500.02, a p-Value of 0.61. The null hypothesis cannot be rejected, and the sample mean and the population mean of 1500 are statistically similar.
However, Lot 3, not surprisingly is a different scenario. Here the sample mean is 1496.14 and the p-Value is 0.04, which is lower than the common significance level of 0.05. We should reject the null hypothesis that the sample mean and the presumed population mean are not statistically different.

## Study Design: MechaCar vs Competition
Looking at all of this we have yet to look at the competition for the MechaCar. When it comes to the competition there are a few things to look at such as "Which vehicles will be in competiton with the MechaCar?", "What makes them comparable?", and "What factors to look at to determine the relevancy of the selling price?". A metric that would be of interest to a consumer is the Engine (hybrid, gas, electric, size, etc.). Another metric that can be looked at is the average annual cost of ownership or maintenance. Another metric we can look at is the selling price of the vehicles. These are just a few things to look at especially the pricing because this is normally one of the first things to look at when going to purchase a car. A null hypothesis for this is the MechaCar is not priced correctly based on performance and sustainability. The alternative hypothesis would be that the MechaCar is priced correctly based on performance and sustainability. A multiple linear regression would be used to determine the factors that have the highest correlation and/or predictability with the selling price.
