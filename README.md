
# MechaCar_Statistical_Analysis
### Overview

The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle.Goal of the Analysis of 1 is to get the Linear Regression to get MPG.

## ## Linear Regression to Predict MPG


![image](https://user-images.githubusercontent.com/100485119/173167150-7ab001b8-5aee-4c3c-b7d4-f575d4787275.png)

### Non-random amount of variance to the mpg values in the dataset on the MPG of the MechaCar are the Vehicle Length and the Ground Clearance.  linear regression model run on these variables against figures for MPG, resulted in p-values of 2.6x10-12 and 5.21x10-8, respectively. The intercept was also statistically significant, indicating that there are likely other factors, not included in our dataset, that have a strong impact on the MPG. resulted in p-values of 2.60e-12 and 5.21e-08 respectively.

### The slope of the linear model is not considered as zero. P value is 5.35e-11 is lower than even an extreme level of significance, and thus the null hypothesis must be rejected. 

### As per the R value which is 0.7149, this linear model predict mpg of MechaCar prototypes effectively 71%. Which could do better but as it is 71% we can say it is effective.

## Summary Statistics on Suspension Coils
### Suspension.csv into table
![image](https://user-images.githubusercontent.com/100485119/173209208-5a4ce0e3-fce1-4bd3-bc27-e1e0be953f47.png)
### Lot_summary

![image](https://user-images.githubusercontent.com/100485119/173209098-0aa9e511-a3a4-4bc5-9586-926d6c07af93.png)
### Total_summary

![image](https://user-images.githubusercontent.com/100485119/173209096-66a7c6be-ca65-47bc-9fe7-1ed3537e28e1.png)

Based on the results, the manufacturing lots when grouped together meet the design specification as the variance on PSI is 62.29356

However if we take varience of the suspensions coils seperately as lot1,lot2,lot3, then individually, lot 1 and lot 2 are meeting the design specifications as they have the variance on PSI as 0.9795918 and 7.4693878 respectively. But, with variance on PSI as 170.2861224, lot 3 does not meet the design specification.

