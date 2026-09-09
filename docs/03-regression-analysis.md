# Regression Analysis

## Objective

The purpose of this task was to quantify the relationship between TV advertising expenditure and product sales using correlation and linear regression.

This task was completed by **Silvia Botoaca** as part of the group project.

## Correlation Coefficient

The correlation coefficient was calculated in Microsoft Excel using:

`CORREL(A2:A201, B2:B201)`

The resulting correlation coefficient was:

**r = 0.7822**

This indicates a strong positive correlation between TV advertising expenditure and product sales.

As TV advertising expenditure increases, product sales generally tend to increase.

## Regression Equation

The slope and intercept were calculated using Excel's `SLOPE` and `INTERCEPT` functions.

The resulting regression equation was:

**ŷ = 0.0475x + 7.0326**

where:

- **x** represents TV advertising expenditure in hundreds of pounds.
- **ŷ** represents predicted product sales in thousands.

### Slope

The slope of the regression line is:

**0.0475**

For every additional £100 spent on TV advertising, the model predicts an increase of approximately **0.0475 thousand sales**, equivalent to approximately **47.5 sales**.

### Intercept

The intercept is:

**7.0326**

According to the regression model, when £0 is spent on TV advertising, predicted product sales are approximately **7.0326 thousand**, or approximately **7,033 sales**.

## Making Predictions

The regression equation can be used to estimate product sales for different levels of TV advertising expenditure.

### Interpolation

Interpolation involves making a prediction using a value within the range of the observed dataset.

For an advertising expenditure of **£14,325**:

**x = 143.25**

Substituting this into the regression equation:

**ŷ = 0.0475(143.25) + 7.0326**

This gives predicted sales of approximately:

**13.84 thousand sales**

or approximately **13,840 sales**.

### Extrapolation

Extrapolation involves making a prediction using a value outside the observed range of the dataset.

For an advertising expenditure of **£55,000**:

**x = 550**

Using the regression equation gives predicted sales of approximately:

**33.16 thousand sales**

Because this value lies outside the range of the observed data, the prediction should be interpreted with greater caution.

## Coefficient of Determination

The coefficient of determination was calculated by squaring the correlation coefficient:

**R² = 0.6119**

This indicates that approximately **61.19% of the observed variation in product sales** is explained by the linear relationship with TV advertising expenditure.

The remaining **38.81%** is not explained by the model and may be associated with other factors affecting sales.

## Conclusion

The regression analysis identified a strong positive association between TV advertising expenditure and product sales.

The regression equation provides a method for estimating sales based on advertising expenditure, while the correlation coefficient and R² value demonstrate that TV advertising expenditure explains a substantial proportion of the observed variation in sales.

---

## Next

[← Go Back](02-scatterplot-analysis.md) | [Next →](04-residual-analysis.md)
