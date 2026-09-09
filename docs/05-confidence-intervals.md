# Confidence Interval Analysis

## Objective

The purpose of this task was to calculate and interpret the **95% and 99% confidence intervals** for TV advertising expenditure.

This task was completed by **Mustafa Iqbal** as part of the group project.

## Sample Statistics

The analysis used the TV advertising expenditure data from the provided dataset.

The sample contained:

- **Sample size (n):** 200
- **Sample mean (x̄):** 147.0425 hundreds of pounds
- **Sample standard deviation (s):** 85.85424 hundreds of pounds
- **Degrees of freedom (df):** 199

Because the population standard deviation was unknown, the **t-distribution** was used to calculate the confidence intervals.

## Calculating the Confidence Intervals

The margin of error was calculated using:

**Margin of Error = t-critical × (s / √n)**

The confidence interval was then calculated using:

**x̄ ± Margin of Error**

The t-critical values used were:

- **95% confidence:** 1.972
- **99% confidence:** 2.626

![Figure 4 - Calculated Confidence Interval Variables in Excel](../screenshots/04%20-%20Confidence%20Interval%20Calculations.png)

*Figure 4. Calculated confidence interval variables in Microsoft Excel.*

## 95% Confidence Interval

The calculated 95% confidence interval was:

**[134.998, 159.087]**

The values are measured in hundreds of pounds.

Converted to pounds, the interval is approximately:

**£13,499.80 to £15,908.70**

This means that the analysis estimates, with 95% confidence, that the true population mean for TV advertising expenditure lies within this interval.

## 99% Confidence Interval

The calculated 99% confidence interval was:

**[131.10055, 162.98445]**

Converted to pounds, the interval is approximately:

**£13,110.06 to £16,298.45**

This means that the analysis estimates, with 99% confidence, that the true population mean for TV advertising expenditure lies within this interval.

## Comparing the Intervals

The **99% confidence interval is wider** than the 95% confidence interval.

A higher confidence level requires a larger margin of error. This produces a wider interval to provide greater confidence that the interval captures the true population mean.

Therefore:

- **95% CI:** £13,499.80 – £15,908.70
- **99% CI:** £13,110.06 – £16,298.45

## Conclusion

The analysis estimated the range within which the true mean TV advertising expenditure is likely to fall.

The 99% confidence interval was wider than the 95% confidence interval because a higher level of confidence requires a larger range of plausible values.

---

## Next

[← Go Back](04-residual-analysis.md) | [Next →](06-hypothesis-testing.md)
