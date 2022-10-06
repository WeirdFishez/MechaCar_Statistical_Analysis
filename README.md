# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/107438816/194428933-bbd3d8d0-ea77-4d4a-9189-c1aacf77d66f.png)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
 - Ground Clearance (p-value 0.0000000521) and vehicle length (p-value 0.00000000000260) are the two variables with the closest correlation to MPG

Is the slope of the linear model considered to be zero? Why or why not?
 - The **p-value** for the model is 5.35e-11 which is far below the .001 significant code. This means that the NULL hypotheses is rejected and  

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
 - The **r-squared** value for our linear regression is .7149 which means the model is able to explain 71% of vehicles MPG accurately with the given variables, however the **Residual Standard Error** is 8.774 which means that values fall an average of 8.8 units from the regression line, which does bear weight when the mean MPG in our data is 45.12.



![image](https://user-images.githubusercontent.com/107438816/194435637-47c14849-aecd-487b-a0ac-eda4d3a27364.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

As a whole, all lots are meeting the suspension coil PSI variance with a 62.29 on a goal of 100. However, when the lots are split up into seperate groups the data shows that Lot #3 has a variance of 170.2 and makes up the majority of variance and does not meet the 100 PSI requirements.
