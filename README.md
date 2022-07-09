# MechaCar_Statistical_Analysis

# Linear Regression to Predict MPG

*	Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

o Vehicle length and ground clearance are statistically significant and provide a non-random amount of variance. 
  
  
  
*	Is the slope of the linear model considered to be zero? Why or why not?

![Coefficients](https://user-images.githubusercontent.com/102333060/178116002-2f041115-852d-4442-8bd2-695df8b57f81.png)

The slope of the linear model is not zero. 



* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

o R-squared value is .7149, which means there is a strong correlation for the dataset. 


# Summary Statistics on Suspension Coils

•	The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lot summary for all manufaction lots


![total_summary](https://user-images.githubusercontent.com/102333060/178116068-a0bea771-6862-417a-95d4-4f0fdaccf352.png)

Lot summary for indivdual lots


![lot_summary](https://user-images.githubusercontent.com/102333060/178116097-e36d7070-f7aa-446f-9311-4a35a71556be.png)

o	The current manufacturing data for all manufacturing lots meet the requirements of less than 100 PSI. However, the individual lots data, Lot3 with 170.29 Variance failed to meet the requirements. 

# T – Tests on Suspension Coils
  
T-test for all manufacturing lots

![T-Test for all Lots](https://user-images.githubusercontent.com/102333060/178116218-c5db9c97-3a76-4b8d-8732-2c5a25fe3df1.png)

P Value of > 0.05 doesn't have a significant variance from the normal distribution and should considered normal/acceptable.

# T-test summary for each individual lots

T-test results for individual lots. Lot 3 has a P-Value of .04 and falls outside the normal distribution.  
![T-Test Lot_1](https://user-images.githubusercontent.com/102333060/178116420-e6124771-52d9-46ab-a94e-c03a14ec6982.png)
![T-Test Lot_2](https://user-images.githubusercontent.com/102333060/178116425-eb45741a-83e1-4938-ba00-5be4f7cfa0d0.png)
![T-Test Lot_3](https://user-images.githubusercontent.com/102333060/178116428-7d962ea6-e094-4fa5-96f6-950eebf73b23.png)


# Study Design: MechaCar vs Competition

This study will consider metrics such as cost, fuel efficiency, safety rating data against the competition. Null hypothesis will be to determine if these metrics will have statistically significant variance from the competition. 

