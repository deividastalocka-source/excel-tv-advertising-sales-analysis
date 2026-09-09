# TV Advertising Sales Analysis

A statistical data analysis project investigating the relationship between **TV advertising expenditure and product sales** using Microsoft Excel.

The project applies data visualisation, correlation, linear regression, residual analysis, confidence intervals and hypothesis testing to a dataset containing 200 observations.

## Research Question

> Is there a linear relationship between the funds allocated to TV advertising and the number of sales of the company's products?

## Project Overview

The dataset contains two primary variables:

- **TV advertising expenditure** — measured in hundreds of pounds.
- **Product sales** — measured in thousands.

The analysis examines the strength of the relationship between these variables and evaluates how effectively TV advertising expenditure can be used to predict product sales.

## Key Results

| Measure | Result |
|---|---:|
| Sample Size | 200 |
| Correlation Coefficient | 0.7822 |
| Coefficient of Determination | 0.6119 |
| Regression Equation | ŷ = 0.0475x + 7.0326 |
| 95% Confidence Interval | £13,499.80 – £15,908.70 |
| 99% Confidence Interval | £13,110.06 – £16,298.45 |
| Hypothesis Test Statistic | ≈ 1.16 |

The analysis identified a **strong positive correlation** between TV advertising expenditure and product sales.

The regression model produced an **R² value of 0.6119**, indicating that approximately **61.19% of the observed variation in sales** is explained by the linear relationship with TV advertising expenditure.

## Scatterplot Analysis

![TV Advertising Scatterplot](screenshots/01%20-%20TV%20Advertising%20Scatterplot.png)

*Scatterplot of TV advertising expenditure and product sales with a linear trendline.*

The regression equation was:

**ŷ = 0.0475x + 7.0326**

The positive slope indicates that higher TV advertising expenditure is associated with higher predicted product sales.

## Residual Analysis

![Residual Plot](screenshots/03%20-%20Residual%20Plot.png)

*Residual plot used to assess the behaviour of prediction errors across TV advertising expenditure.*

The residual analysis identified **heteroscedasticity**, with residual variability increasing at higher levels of advertising expenditure.

This indicates that the simple linear regression model does not fully capture the behaviour of the data and that other factors may also influence sales.

## Hypothesis Testing

A one-sample t-test was used to assess the claim that clients spend an average of **£14,000** on TV advertising.

The analysis produced:

**t ≈ 1.16**

At the 5% significance level, the null hypothesis was **not rejected**.

The sample therefore did not provide sufficient statistical evidence to conclude that the true mean TV advertising expenditure differs from £14,000.

## My Contribution

This was completed as a **group project**.

My individual responsibility was the **scatterplot analysis**, which involved:

- Selecting TV advertising expenditure as the explanatory variable and product sales as the response variable.
- Creating the scatterplot in Microsoft Excel.
- Applying a linear trendline.
- Displaying the regression equation and R² value.
- Interpreting the relationship between advertising expenditure and sales.

The remaining statistical tasks were completed collaboratively as part of the group's overall analysis.

## Documentation

Detailed documentation for each stage of the analysis is available below:

1. [Project Overview](docs/01-project-overview.md)
2. [Scatterplot Analysis](docs/02-scatterplot-analysis.md)
3. [Regression Analysis](docs/03-regression-analysis.md)
4. [Residual Analysis](docs/04-residual-analysis.md)
5. [Confidence Interval Analysis](docs/05-confidence-intervals.md)
6. [Hypothesis Testing](docs/06-hypothesis-testing.md)
7. [Project Conclusion](docs/07-conclusion.md)

## Technologies & Methods

- Microsoft Excel
- Statistical Analysis
- Data Visualisation
- Correlation Analysis
- Linear Regression
- Residual Analysis
- Confidence Intervals
- Hypothesis Testing
- Data Interpretation

## Repository Structure

```text
.
├── README.md
├── docs/
│   ├── 01-project-overview.md
│   ├── 02-scatterplot-analysis.md
│   ├── 03-regression-analysis.md
│   ├── 04-residual-analysis.md
│   ├── 05-confidence-intervals.md
│   ├── 06-hypothesis-testing.md
│   └── 07-conclusion.md
│
└── screenshots/
    ├── 01 - TV Advertising Scatterplot.png
    ├── 02 - Residual Formula.png
    ├── 03 - Residual Plot.png
    └── 04 - Confidence Interval Calculations.png
```

## Project Status

**Completed**

This project was completed as part of university coursework and demonstrates the practical application of statistical analysis techniques to a business-focused dataset.
