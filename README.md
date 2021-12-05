# MechaCar_Statistical_Analysis

## Overview of MechaCar

### Purpose
The purpose of this analysis is to use R Programming to perform a statistical analysis on MechaCar and it's manufacturing output of the new prototype. 

## Linear Regression to Predict MPG

![Linear Regression](https://github.com/MoKmo176/MechaCar_Statistical_Analysis/blob/8fb3f3405c21b9c7436a2da022eee936aff446a4/Images/Linear%20Regression.png)

Q: Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

A: Spoiler Angle and AWD provide a non-random amount of variance to MPG values in the dataset. 

Q: Is the slope of the linear model considered to be zero? Why or why not?

A: The slope will not be zero in the linear model, because there is a significant relationship between the independent variable and the dependent variable. 

Q: Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

A: No, because the linear model does not have enough variables in the dataset to increase the confidence level in it's prediction of Miles Per Gallon.

## Summary Statistics on Suspension Coils 

![Summary Stats by Lot](https://github.com/MoKmo176/MechaCar_Statistical_Analysis/blob/8fb3f3405c21b9c7436a2da022eee936aff446a4/Images/Summary%20Statistics%20by%20Lot.png)

Q: The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

A: No, because the current manufacturing data meets the design specification for all manufacturing lots in total, although for each individual lot, Lot1 & Lot2 meets the criterion, while Lot3 has a variance that exceeds 100. 

![Summary Stats](https://github.com/MoKmo176/MechaCar_Statistical_Analysis/blob/8fb3f3405c21b9c7436a2da022eee936aff446a4/Images/Summary%20Statistics.png)

## T-Tests on Suspension Coils 

The conclusion of the T-Test has a normal distribution based on the shape of the bell and p-value above 0.05. In 95% Confidence Interval, the T-Tests yield the True Means on all the tests as not equal to 1500. 

![R-Plot](https://github.com/MoKmo176/MechaCar_Statistical_Analysis/blob/8fb3f3405c21b9c7436a2da022eee936aff446a4/Rplot.png)
![T_tests](https://github.com/MoKmo176/MechaCar_Statistical_Analysis/blob/8fb3f3405c21b9c7436a2da022eee936aff446a4/Images/T-Test(2).png)
![T_test](https://github.com/MoKmo176/MechaCar_Statistical_Analysis/blob/8fb3f3405c21b9c7436a2da022eee936aff446a4/Images/T-Test%20(1).png)


## Study Design: MechaCar vs Competition 

A statistical study that can quantify performance of MechaCars versus the competition includes the following metrics: the city and highway fuel efficiency, cost, vehicle specifications, and the maintenance cost. The null hypothesis asks "which car has better resale value?" and the alternate hypothesis asks "which car has better lifetime value?". The statistical tests would include summary statistics and T-tests, because we can determine where MechaCar lies versus competitors in terms of overall depriciation in terms of resale value,  and assesses maintenance cost versus efficiency in terms of lifetime value of owning a vehicle. The data that is needed is every specification of the car exterior, the engnie performance values, and the cost of the vehicle and the most commonly replaced parts. 



