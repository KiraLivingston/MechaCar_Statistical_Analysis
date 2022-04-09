# MechaCar_Statistical_Analysis

## Deliverable 1
![images/Deliverable_1.png](https://github.com/KiraLivingston/MechaCar_Statistical_Analysis/blob/main/images/Deliverable_1.png)

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Based on the coffeicients provided by lm, it would appear as though vehicle weight, spoiler angle, ground clearance, and AWD would be major contributing factors to variation in MPG values.

### Is the slope of the linear model considered to be zero? Why or why not?
It is not, as the p-value is much smaller than an assumed significance level of 0.5%, making the linear model not zero.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Based on the R-Squared value of .7149, equalling 71.49% effectiveness in predicting accurate MPG numbers from this model, this linear model is relatively effective.

## Deliverable 2
![images/Deliverable_2.1.png](https://github.com/KiraLivingston/MechaCar_Statistical_Analysis/blob/main/images/Deliverable_2.1.png)
![images/Deliverable_2.2.png](https://github.com/KiraLivingston/MechaCar_Statistical_Analysis/blob/main/images/Deliverable_2.2.png)
### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Totally, with all three lots' data being used, I would not recommend using any coilsprings manufactured from Lot 3, as they are exclusively over 70psi over acceptable variances in their manufacturing. Otherwise, Lots 1 and 2 would be perfectly fine to use, scoring less than 8psi variance overall.

## Deliverable 3
![images/Deliverable_3.png](https://github.com/KiraLivingston/MechaCar_Statistical_Analysis/blob/main/images/Deliverable_3.png)
### In your README, briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

Continuing the thread from the previous question, it's clear that Lot 3's manufacturing process is flawed in some critical way, preventing their coils being used in the MechaCar production.

## Deliverable 4

### Metric to test
To narrow down our test, we should evaluate MechaCar's miles per gallon, in comparison to various competitors' vehicles.

### Null and Alternate Hypothesis
Null Hypothesis: MechaCar prototypes' average MPG is similar to competitor's vehicles in the same vehicle class 
Alternate Hypothesis: MechaCar prototypes' average MPG is statistically above or below that of competitor vehicles.

### Statistical Test Used
The best statistical test for this would be two-sample t-tests.

### What data is needed
We would need to gather cubic space data from the carrying compartments of all MechaCar prototypes, as well as from all major competitor vehicles.
