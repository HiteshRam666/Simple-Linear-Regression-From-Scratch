# Simple-Linear-Regression-From-Scratch

**Simple Linear Regression**

### Overview

Simple linear regression is a statistical method used to model the relationship between two variables: one independent variable and one dependent variable. It aims to find the best-fitting straight line that describes the relationship between the variables. This method is often employed to understand how changes in the independent variable affect the dependent variable.

Sure, here's the formula for simple linear regression:

The equation of a simple linear regression model can be represented as:

\[ Y = β₀ + β₁X + ε \]

Where:
- \( Y \) is the dependent variable (response variable),
- \( X \) is the independent variable (predictor variable),
- \( β₀ \) is the intercept,
- \( β₁ \) is the slope,
- \( ε \) represents the error term (residuals), which captures the difference between the observed and predicted values of the dependent variable.

The goal of simple linear regression is to estimate the coefficients \( β₀ \) and \( β₁ \) such that the regression line minimizes the sum of squared differences between the observed and predicted values of the dependent variable.

The coefficients \( β₀ \) and \( β₁ \) are estimated using the least squares method, which involves minimizing the sum of the squared residuals:

\[ \sum_{i=1}^{n} (Y_i - (β₀ + β₁X_i))^2 \]

Where:
- \( n \) is the number of observations,
- \( Y_i \) and \( X_i \) are the observed values of the dependent and independent variables, respectively.

Once the coefficients are estimated, they can be used to predict the value of the dependent variable (\( Y \)) for any given value of the independent variable (\( X \)).

### Key Concepts

- **Independent Variable (X)**: This is the variable that is manipulated or controlled by the researcher. It is also referred to as the predictor variable.
  
- **Dependent Variable (Y)**: This is the variable that is observed and measured. It is influenced by changes in the independent variable. It is also known as the response variable.

- **Regression Line**: The regression line represents the best-fit line through the data points. It is determined by minimizing the sum of the squared differences between the observed and predicted values of the dependent variable.

- **Slope (β₁)**: The slope of the regression line indicates the rate of change in the dependent variable for a one-unit change in the independent variable.

- **Intercept (β₀)**: The intercept is the value of the dependent variable when the independent variable is zero. It represents the baseline value of the dependent variable.

- **Residuals**: Residuals are the differences between the observed values of the dependent variable and the values predicted by the regression line. A residual plot is often used to assess the adequacy of the regression model.

### Assumptions

- **Linearity**: There is a linear relationship between the independent and dependent variables.

- **Independence**: The observations are independent of each other.

- **Homoscedasticity**: The variance of the residuals is constant across all levels of the independent variable.

- **Normality**: The residuals are normally distributed.

### How It Works

1. **Data Collection**: Gather data on both the independent and dependent variables.
2. **Model Specification**: Choose a suitable model that represents the relationship between the variables (in this case, a simple linear model).
3. **Parameter Estimation**: Use statistical methods to estimate the slope and intercept of the regression line.
4. **Model Fitting**: Fit the regression line to the data by minimizing the sum of squared residuals.
5. **Model Evaluation**: Assess the goodness-of-fit of the model and check whether the assumptions are met.
6. **Prediction**: Use the fitted model to make predictions about the dependent variable based on new values of the independent variable.

### Applications

Simple linear regression is widely used in various fields, including:

- Economics: Analyzing the relationship between variables such as income and expenditure.
- Finance: Predicting stock prices based on factors like interest rates or market indices.
- Medicine: Studying the effects of a drug dosage on patient recovery time.
- Marketing: Predicting sales based on advertising expenditure or market size.

### Conclusion

Simple linear regression provides a useful tool for understanding and quantifying the relationship between two variables. By fitting a regression line to the data, researchers can make predictions and draw insights about the behavior of the dependent variable based on changes in the independent variable. However, it is essential to carefully assess the assumptions of the model and interpret the results within the appropriate context.
