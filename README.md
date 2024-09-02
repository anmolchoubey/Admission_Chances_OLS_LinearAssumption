# Admission_Chances_OLS_LinearAssumption

Linear regression is a fundamental tool in data science, essential for predicting outcomes and exploring relationships between variables. However, its predictive power is contingent on several critical assumptions. Whether you're a startup founder examining market trends or a VC assessing portfolio performance, understanding and validating these assumptions can elevate your analysis from insightful to transformative.
Here’s a closer look at the key assumptions and how to verify them:
1.	Linearity: The relationship between independent and dependent variables should be linear. To assess this, plot a scatter plot of the independent versus dependent variables to visually inspect whether the linearity assumption holds.
2.	No Multicollinearity: Independent variables should not be highly correlated with each other, as this can lead to redundancy and instability in your model. Use the Variance Inflation Factor (VIF) to identify and address multicollinearity. Generally, a VIF > 10 indicates very high multicollinearity (consider removing these variables), 5 ≤ VIF ≤ 10 suggests high multicollinearity (consider giving a thought before removing), and VIF < 5 indicates low multicollinearity.
3.	Normality of Residuals: Residuals (errors) should follow a normal distribution to ensure valid inferences about the model coefficients. Use a QQ-plot and the Shapiro-Wilk test to check for normality.
4.	Homoscedasticity: Residuals should have constant variance across all levels of the independent variables. Plot the residuals against the dependent variable and check for any patterns or changes in variance across the range.
5.	No Autocorrelation: Observations, especially in time series data, should be independent of each other to avoid bias.

Implemented a project to predict the admission chances based on different variables, have used OLS (Ordinary Least Square) as the name suggests minimizes the sum square error to estimate the best coefficient. Look how using assumptions, made model more efficient. 
