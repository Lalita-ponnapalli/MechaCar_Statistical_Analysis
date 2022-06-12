
# MechaCar_Statistical_Analysis
### Overview

The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle.Goal of the Analysis of 1 is to get the Linear Regression to get MPG.

## ## Linear Regression to Predict MPG


![image](https://user-images.githubusercontent.com/100485119/173167150-7ab001b8-5aee-4c3c-b7d4-f575d4787275.png)

#### Non-random amount of variance to the mpg values in the dataset on the MPG of the MechaCar are the Vehicle Length and the Ground Clearance.  linear regression model run on these variables against figures for MPG, resulted in p-values of 2.6x10-12 and 5.21x10-8, respectively. The intercept was also statistically significant, indicating that there are likely other factors, not included in our dataset, that have a strong impact on the MPG. resulted in p-values of 2.60e-12 and 5.21e-08 respectively.

#### The slope of the linear model is not considered as zero. P value is 5.35e-11 is lower than even an extreme level of significance, and thus the null hypothesis must be rejected. 

#### As per the R value which is 0.7149, this linear model predict mpg of MechaCar prototypes effectively 71%. Which could do better but as it is 71% we can say it is effective.

## Summary Statistics on Suspension Coils
MechaCarChallenge.R
![image](https://user-images.githubusercontent.com/100485119/173209266-50539a9c-4e75-497d-bd9d-56d2b6f67215.png)

### Suspension.csv into table
![image](https://user-images.githubusercontent.com/100485119/173209208-5a4ce0e3-fce1-4bd3-bc27-e1e0be953f47.png)
### Total_summary

![image](https://user-images.githubusercontent.com/100485119/173209098-0aa9e511-a3a4-4bc5-9586-926d6c07af93.png)
### Lot_summary

![image](https://user-images.githubusercontent.com/100485119/173209096-66a7c6be-ca65-47bc-9fe7-1ed3537e28e1.png)

#### Based on the results, the manufacturing lots when grouped together meet the design specification as the variance on PSI is 62.29356.
#### However if we take varience of the suspensions coils seperately as lot1,lot2,lot3, then individually, lot 1 and lot 2 are meeting the design specifications as they have the variance on PSI as 0.9795918 and 7.4693878 respectively. But, with variance on PSI as 170.2861224, lot 3 does not meet the design specification.

##  T-Tests on Suspension Coils
#### Suspension Coils Cumulative T-test
![image](https://user-images.githubusercontent.com/100485119/173209472-107f592d-0bf0-47a0-bd67-3d466095f4e4.png)
#### T-test on lot1
![image](https://user-images.githubusercontent.com/100485119/173209487-68c095da-8ebd-4f3d-939c-465b0d4520ca.png)
#### T-Tests on lot2
![image](https://user-images.githubusercontent.com/100485119/173209498-95c7c2c9-d8f7-46e1-a921-05257670f850.png)
#### T-Tests on lot3
![image](https://user-images.githubusercontent.com/100485119/173209502-6556efc3-16e0-4011-978d-f2e72917e90f.png)

#### Based on results of T-test for the suspension coils across all manufacturing lots shows that they are not statistically different from the population mean, and the p-value is not low enough (0.0603) for us to reject the null hypothesis.
#### Based on results of T-test for the suspension coils for Lot 1 shows that they are not statistically different from the population mean, and the p-value is not low enough for us to reject the null hypothesis.
#### Based on results of T-test for the suspension coils for Lot 2 shows that they are not statistically different from the population mean, and the p-value is not low enough (0.6072) for us to reject the null hypothesis.
#### Based on results of T-test for the suspension coils for Lot 3 shows that they are slightly statistically different from the population mean, and the p-value is just low enough (0.0417) for us to reject the null hypothesis. This lot may be need to be discarded, or at least more closely evaluated.

#### Overall the p value of T-test for Cumulative and individual is not low enough for us to reject the null hypothesis.





