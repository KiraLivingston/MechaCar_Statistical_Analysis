# MechaCar_Statistical_Analysis

## Deliverable 1

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Based on the coffeicients provided by lm, it would appear as though vehicle weight, spoiler angle, ground clearance, and AWD would be major contributing factors to variation in MPG values.

### Is the slope of the linear model considered to be zero? Why or why not?
It is not, as the p-value is much smaller than an assumed significance level of 0.5%, making the linear model not zero.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Based on the R-Squared value of .7149, equalling 71.49% effectiveness in predicting accurate MPG numbers from this model, this linear model is relatively effective.

## Deliverable 2

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Totally, with all three lots' data being used, I would not recommend using any coilsprings manufactured from Lot 3, as they are exclusively over 70psi over acceptable variances in their manufacturing. Otherwise, Lots 1 and 2 would be perfectly fine to use, scoring less than 8psi variance overall.

## Deliverable 3

### In your README, briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

Continuing the thread from the previous question, it's clear that Lot 3's manufacturing process is flawed in some critical way, preventing their coils being used in the MechaCar production.

### T-Tests on Suspension Coils
