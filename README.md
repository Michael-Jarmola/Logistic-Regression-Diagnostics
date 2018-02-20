# Logistic-Regression-Diagnostics
This function reviews the diagnostic tests of a logistic regression. 

We print:
* The logistic model.
* The Breusch-Pagan Test checking for heteroskedasticity to make sure the variance in the errors of the regression is not related to independent variables of the regression. 
* A logistic regression where the coefficients are converted into marginal effects instead of odds ratios or log of odds ratios. This model also has standard errors corrected for heteroskedasticity, if present. 
* A calculated pseudo-R^2 (McFadden R^2) to judge goodness of fit.
* The Hosmer-Lemeshow Test to varify ranking of the output.
* A Confusion Matrix to gauge precision and accuracy.

