# Residual Analysis

## Objective

The purpose of this task was to use residual analysis to assess the validity of the linear regression model between TV advertising expenditure and product sales.

This task was completed by **Baurneegan Kanesalingam** as part of the group project.

## Calculating Predicted Values

Predicted sales values were calculated using the regression equation:

**ŷ = 0.0475x + 7.0326**

where:

- **x** represents TV advertising expenditure.
- **ŷ** represents the predicted sales value.

## Calculating Residuals

A residual represents the difference between the actual sales value and the value predicted by the regression model.

The residuals were calculated using:

**Residual = Actual Value − Predicted Value**

In Excel, this was calculated by subtracting the predicted sales value from the corresponding actual sales value.

![Figure 2 - Formula for Calculating Residuals](../screenshots/02%20-%20Residual%20Formula.png)

*Figure 2. Formula used to calculate residuals from actual and predicted sales values.*

## Residual Plot

The calculated residuals were plotted against TV advertising expenditure to assess how the prediction errors behaved across different levels of advertising expenditure.

![Figure 3 - Residual Plot Graph of TV Ads Data](../screenshots/03%20-%20Residual%20Plot.png)

*Figure 3. Residual plot graph of TV advertising expenditure against the calculated residuals.*

## Heteroscedasticity

The residual plot showed that the variability of the residuals increased as TV advertising expenditure increased.

Instead of maintaining a relatively constant spread across the explanatory variable, the residuals became more dispersed at higher advertising expenditure values.

This pattern indicates **heteroscedasticity**, meaning that the variance of the residuals is not constant.

## Interpretation

The presence of heteroscedasticity suggests that the simple linear regression model does not fully capture the behaviour of the data.

Other variables not included in the model may also influence product sales.

The original analysis suggested that factors such as the timing of advertising campaigns could potentially affect sales performance.

## Conclusion

Although the regression model identified a positive relationship between TV advertising expenditure and product sales, the residual analysis identified a limitation in the model.

The presence of heteroscedasticity means that predictions from the regression model should be interpreted with caution, particularly as advertising expenditure increases.

---

## Next

[← Go Back](03-regression-analysis.md) | [Next →](05-confidence-intervals.md)
