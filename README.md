# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/107438816/194428933-bbd3d8d0-ea77-4d4a-9189-c1aacf77d66f.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
 - Ground Clearance (p-value 0.0000000521) and vehicle length (p-value 0.00000000000260) are the two variables with the closest correlation to MPG

Is the slope of the linear model considered to be zero? Why or why not?
 - The **p-value** for the model is 5.35e-11 which is far below the .001 significant code. This means that the NULL hypotheses is rejected and  

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
 - The **r-squared** value for our linear regression is .7149 which means the model is able to explain 71% of vehicles MPG accurately with the given variables, however the **Residual Standard Error** is 8.774 which means that values fall an average of 8.8 units from the regression line, which does bear weight when the mean MPG in our data is 45.12.



# PSI Variance
![image](https://user-images.githubusercontent.com/107438816/194436003-12643f43-a658-44a4-a531-8c85fd1f81a4.png)

![image](https://user-images.githubusercontent.com/107438816/194435637-47c14849-aecd-487b-a0ac-eda4d3a27364.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

As a whole, all lots are meeting the suspension coil PSI variance with a 62.29 on a goal of 100. However, when the lots are split up into separate
 groups the data shows that Lot #3 has a variance of 170.2 and makes up the majority of variance and does not meet the 100 PSI requirements.


# T-Tests
 - The combined T-test shows us an overall p-value of .06028. Assuming our significance level was 0.05 percent, our p-value is above our significance level. Therefore, we do not have sufficient evidence to reject the null hypothesis, and we would state that the two means are statistically similar.
 - However, when we break down the data by Manufacturing lot again, we can see that lot1 has a p-value of 1 which means there is no statistical difference between Lot1 and the overall data. Lot3 is the only group hitting below the .05 pvalue significance, with a .04168.

### All Lots
![image](https://user-images.githubusercontent.com/107438816/194438720-54677e36-b6c5-406b-9a6f-6285dac37cf6.png)


### Lot 3
![image](https://user-images.githubusercontent.com/107438816/194438608-89f75e70-b296-46e4-9bb2-09a46910a2e8.png)

### Lot 2
![image](https://user-images.githubusercontent.com/107438816/194438639-ee1d2eb0-5821-42e9-9d1a-92c911815ef5.png)

### Lot 1
![image](https://user-images.githubusercontent.com/107438816/194438666-97262fbf-983f-43ca-8820-ab609066bc35.png)

## Study Design: MechaCar vs Competition

