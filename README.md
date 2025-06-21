Start Date: May 18 2025

# Econometrics
## Regression
# Assessment of Model Fit
This is based on pages 33-35 of the 2015 book by Frank Harrell "Regression Modeling Strategies". 

Let the general linear regression model be C(Y|X) = \beta_0 + \beta_1 X_1 + \beta_2 X_2 + ... + \beta_k X_k. The assumptions of linearity and additivity need to be verified. We begin with a special case of the general model,

C(Y|X) = \beta_0 + \beta_1 X_1 + \beta_2 X_2, 

where X_1 is binary and X_2 in continuous. There are several ways to check the fits of this model. Method 1: critiques the simple model. 

Model 1- Fit the linear additive model and critically examine residual plots for evidence of systematic patterns. 

- Compute the estimated residuals e = Y - X \hat{\beta}
- Plot the box plots of e stratified by X-1
- Plot the scatterplots of e versus X_1 and \hat{Y} with trend curves.
- If assuming constant conditional variance of Y, calculate the spread of residual distribution against each of the variables.
- If you need normality assumption (for significance tests or confidence limits), compare the distribution of e with a Normal distribution with mean zero. Advantage: simplicity; Disadvantage: we can only compute the standard residuals for continuous uncensored response variables.


Models 2-5: directly estimate the model.

Model 2- Make a scatterplot of Y versus X_2 using different symbols according to values of X_1. 
Advantages: simplicity, possibility of sometimes seeing the regression patterns and sometimes interaction pattens.
Disadvantages: patterns are difficult to see if the relationship is weak or the sample size is very large. Not application for binary, categorical or censored Y.

Model 3- 



# Economic Development
Here I record economic development terms that I encounter in my work. 

### Immiserizing Growth
Immiserizing growth is a long-term phenomenon that occurs when the gain in a country's social welfare arising from economic growth is more than offset by the loss in such welfare associated with an adverse shift in the terms of trade. In one case explored by Jagdish Bhagwati in 1958, immiserizing growth occurs in a developing nation that has started economic growth but faces unfavorable international demand conditions as it increases its traditional exports. In another case explored recently by Paul A. Samuelson, immiserizing growth occurs for the growing industrialized country when its trade partner follows a policy of import substituting growth and, as a result, shifts the terms of trade against the exporting country. Still others have specified a variety of different cases of immiserizing growth. 

Reference: Frederic L. Pryor. (2007). "Immiserizing Growth As Seen By Bhagwati, Samuelson, And Others". Journal Of Economic Education. Volume 38, Issue 2. 208-214. [Link](https://www.jstor.org/stable/30042768)


