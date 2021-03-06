# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

The r^2 value is at .71 which means that roughly 71% of mpg predictions will be correct when using this linear model. This means that the linear model will predict the mpg of MechaCar protoypes effectviely. With a p-value of 5.35e-11 I can say that there is sufficient evidence thst the slope of the linear model is not 0. The variables of vehicle_length and ground_clearance have significant impact on the predicted mpg. Since the intercept is statistically significant, that means that there are other variables that contribute to the variation in the mpg that have not been included in this model. 

![multiple linear reg pic.PNG](https://github.com/JoelS-Pebbles/MechaCar_Statistical_Analysis/blob/main/multiple%20linear%20reg%20pic.PNG)

## Summary Statistics on Suspension Coils

When the lots are averaged together the variance does pass the 100 PSI requirement at 62.29. When the lots are seperated to have their own averages, lots 1 & 2 pass with .979 and 7.469, respectivley. Lot 3 does not pass the requirement becuase the variance for that is 170.286. 

![lot_summary.PNG](https://github.com/JoelS-Pebbles/MechaCar_Statistical_Analysis/blob/main/lot_summary.PNG)

![total summary.PNG](https://github.com/JoelS-Pebbles/MechaCar_Statistical_Analysis/blob/main/total%20summary.PNG)

## T-Tests on Suspension Coils

When looking at all of the lots when they are together, the p-value is higher than .05 so we do not have sifficient evidence to rejst the null hypothesis. Therefore the two means are statistically similar. The p-values for lots 1 and 2 are higher than .05 as well so the same thing can be said about them. The p-value of lot three is .04 so that means we can reject the null hyposthesis and the means are not statistically similar. Below are the t-tests for all lots when together and for the third lot. 

![all lots t-test.PNG](https://github.com/JoelS-Pebbles/MechaCar_Statistical_Analysis/blob/main/all%20lots%20t-test.PNG)
![lot three t-test.PNG](https://github.com/JoelS-Pebbles/MechaCar_Statistical_Analysis/blob/main/lot%20three%20t-test.PNG)

## Study Design: MechaCar vs Competition

The metrics I would use are mpg, horsepower, and safety rating. 

Null Hyp: the slope of a linear model is 0 where there is no corrlation between the dependent and independent variables. 
Alt Hyp: The slope of the linear model does not equal 0. This shows that there is a significatn relationship between the dependent and independent variables. 

I test I would use is a t-test where I would be able to get the statistical differences between the distribution's means and compare that to the competition. Another test I would use is the linear regression model. This is so I would be able to compare the regression curves on the independent variables. 

I would need what the average mpg is for each car. As well as if there have been any modifications to the car such that would affect the mpg. For horsepower I would need the size of the engines per model, fuel types, shape and weight of the frames and types of engines. For safety rating I would need data on accidents, how wekll their airbags work, make sure that the brakes are always working. 
