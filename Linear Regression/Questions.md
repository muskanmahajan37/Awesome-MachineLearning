#### Linear Regression  
> Predicting the value of Y(numerical) from X(numerical or categorical).  

Q . How to Decide Best fit line  
A. Least Squares. Minimize sum of squared errors  

#### Linear Regression Assumptions  
Link: http://statisticsbyjim.com/regression/ols-linear-regression-assumptions/  

Assumption 1: The regression model is linear in the coefficients and the error term. 

Assumption 2: The error term has the population mean of zero.  
              >> Error term Accounts for the variation in Y not explained by X.  
              
Assumption 3: All independent variables are uncorrelated with the error term.  

Assumption 4: Observations of the error term are uncorrelated with each other.(no autocorrelation)  

Assumption 5: The error term has constant variance(no heteroescdasticity). Residuals vs fitted value  

Note: If condition 4 and 5 exists then error tehrm is IID(Independent and Identically Distributed)  

Assumption 6: No independent variable is perfect linear function of other explanatory variables.(No Multicollinearity)  

Assumption 7: The error term is normally distributed(optional)  


Negative R2:  
If the regressors do not include a constant but (as some regression software packages do) you nevertheless calculate R2 by the formula

R2=1−∑ni=1e2i∑ni=1(yi−y¯)2
then the R2 can be negative. This is because, without the benefit of an intercept, the regression could do worse than the sample mean in terms of tracking the dependent variable (i.e., the numerator could be greater than the denominator).
