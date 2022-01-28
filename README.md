# MechaCar_Statistical_Analysis

## Overview



## Results
## Linear Regression to Predict MPG
### 1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

![image](https://user-images.githubusercontent.com/90416094/150705141-291d7bbc-8bce-48dd-a828-fae5ea71a6c0.png)

#### The image above shows the variables/coefficents' p-values (Pr(>|t|)) are as follows:

- vehicle length (2.60e-08)
- vehicle weight(0.0776)
- spoiler angle(0.3069)
- ground clearance(5.21e-08)
- AWD(All Wheel Drive)(0.1852)

#### The following variables/coefficients provided a non-random amount of variance to the mpg values:
- vehicle weight(0.0776)
- spoiler angle(0.3069)
- AWD(All Wheel Drive)(0.1852)
- --
### 2. Is the slope of the linear model considered to be zero? Why or why not?

![image](https://user-images.githubusercontent.com/90416094/150705261-6eb65016-6df1-411d-bb73-1878473fcccf.png)

As seen in the image above, the p-value of the linear model is 5.35e-11. This is smaller than the assumed significance level of 0.05%. The slope of the linear model is therefore not considered to be zero because the p-value is less than 0.05. This gives sufficient evidence to reject the null hypothesis.
- ---

### 3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The r-squared value for this linear model 0.7149. This predicts that approximately, 71% of  mpg predictions will be correct . it can be concluded therefore that this linear model predicts mpg of MechaCar prototypes effectively
- ---
## Summary Statistics on Suspension Coils
### 1. Total summary statistics
![Total_summary statistics_df](https://user-images.githubusercontent.com/90416094/150705357-2b9cef19-5ab1-4623-b9a0-29aeda4ce097.png)

- The image above depicts the mean, median, variance and Standard deviation for the suspension coil. The mean and median have a very small difference leading to the conclusion that dataset has a normal distribution. 

- According to the summary, the variance is roughly 62 pounds, this is below the MechaCar suspension coils design specifications which states that the variance of the suspension coils must not exceed 100 pounds per inch. 

- In conclusion therefore, the current manufacturing data meets the  design specification for all manufacturing lots in total and each lot individually 
- --
The T test results reveals that the p value for all the lots is 0.06028. This is above the assumed significant level of 0.05. Based on this information, there is no sufficient evidence to reject the null hypothesis the analysis. This deduction will lead us to conclude that the suspension coils dataset statistically represents the population mean.

### 2.  T-test on suspension coil
![One sample t-test](https://user-images.githubusercontent.com/90416094/150705472-fc38d243-8c7b-44de-985c-835aa608b51f.png)



### 3. T-test on suspension coil for Lot 1
![T-test  susp_coils for Lot 1](https://user-images.githubusercontent.com/90416094/150705553-adfa1a28-b54e-4032-9d8a-f4a64f4a2e61.png)


### 4. T-test on suspension coil for Lot 2
![T-test  susp_coils for Lot 2](https://user-images.githubusercontent.com/90416094/150705581-fca51613-3461-424a-a587-6ae1040f3030.png)



### 5. T-test on suspension coil for Lot 3

![T-test  susp_coils for Lot 3](https://user-images.githubusercontent.com/90416094/150705674-e0018780-d909-49e9-89c1-25fe74562c79.png)
- --
## Study Design: MechaCar vs Competition.







