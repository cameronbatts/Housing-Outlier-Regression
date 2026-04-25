# Housing Market Outlier Detection & Regression Analysis

**Tools:** R · tidyverse · ggplot2 · ggfortify · gridExtra · Linear Regression

---

## Problem

Housing sale price data contained missing values, anomalous records, and outliers that could distort predictive model accuracy before and after the 2009 market shift.

## Approach

Built linear regression models in R on Ames housing data split by pre and post-2009 periods, conducting NA analysis across 82 variables and applying diagnostic plots for outlier detection. Used density plots to identify fraudulent price clustering in specific neighborhoods, then applied a regression-based correction with random noise to simulate realistic market values.

## Impact

Achieved an adjusted R-squared of 0.88, identifying neighborhood, exterior quality, and floor square footage as significant price drivers. Successfully detected and masked fraudulent price patterns in the NAmes and Gilbert neighborhoods, confirming the correction through residual diagnostics.

---

## Files

| File | Description |
|------|-------------|
| `housing_outlier_regression.Rmd` | R Markdown source file with full analysis |
| `housing_outlier_regression.html` | Rendered HTML output |

---

*Part of my data & analytics portfolio — [cameronbatts.github.io](https://cameronbatts.github.io)*
