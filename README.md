# A Comprehensive Study of Rehoming Duration in Dog Breeds

This repository contains an analysis project focused on understanding and comparing the rehoming durations across different dog breeds. Using statistical techniques, the study examines the rehoming patterns for Mixed Breed, Labrador Retriever, and Border Collie dogs, aiming to identify breed-specific trends.

## Abstract

This project explores dog rehoming durations based on sample data covering factors like health status, visits, age, and breed. The analysis includes data cleaning, statistical modeling (histogram, QQ-plot), hypothesis testing (z-tests and t-tests), and confidence interval analysis. Results reveal that rehoming durations for all three breeds fall between 17 to 24 weeks, without significant differences between breeds.

## Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA) with box plots, histograms, and QQ-plots
- Normality Testing using Shapiro-Wilk and Kolmogorov-Smirnov tests
- Confidence Interval Estimation using z-tests
- Statistical Breed Comparison using t-tests
- Visual summaries with Forest plots and Summary Tables

## Technologies Used

- Python (pandas, matplotlib, scipy, seaborn)
- Statistical Tests: Shapiro-Wilk, Kolmogorov-Smirnov, z-test, t-test
- Data Visualization: Matplotlib, Seaborn
- Report Writing: LaTeX / Word

## Dataset

- **mysample dataset**:
  - Fields: Number of Visits, Rehoming Time (weeks), Health (%), Breed Name, Age Category, Return Status (Yes/No)
  - 849 cleaned observations across three dog breeds.

## Analysis Summary

- **Average Rehoming Time**: 19.2 weeks
- **Average Health Status**: 52.7%
- **Returned Dogs**: 57 instances
- **Rehoming by Breed**:
  - Border Collie: Longer average rehoming time (~20 weeks)
  - Mixed Breed: Slightly faster rehoming (~18 weeks)
  - Labrador Retriever: Intermediate (~19 weeks)

## Statistical Testing

- **Normality**:
  - Mixed Breed: Non-normal distribution (p < 0.05)
  - Border Collie & Labrador Retriever: Near-normal but not perfect (p < 0.05)

- **Confidence Intervals**:
  - All breeds' rehoming times significantly **below 27 weeks**.

- **Breed Comparisons**:
  - No statistically significant difference between breeds based on t-tests (p > 0.05 for all pairs).

## Results

| Test                        | Result |
|------------------------------|--------|
| Kolmogorov-Smirnov (Mixed)   | p = 2.304e-05 |
| Shapiro-Wilk (Labrador)      | p = 0.01219 |
| Shapiro-Wilk (Border Collie) | p = 0.03056 |
| Z-Test Confidence Intervals  | All breeds below 27 weeks |
| Breed Comparison (T-Test)    | No significant differences |

## Visualizations

- Box Plot: Rehoming times by breed
- Histograms: Distribution of rehoming durations
- QQ-Plots: Checking normality of each breed
- Forest Plot: Confidence intervals relative to 27-week threshold

## Discussion

The project highlights similar rehoming patterns across breeds. While slight variations exist, the results suggest no significant breed-based rehoming time differences. Limitations include unequal sample sizes and broader age groups, which may impact findings. Future analysis could integrate factors like health condition and age more precisely to refine predictions.

## Conclusion

The analysis concludes that the average rehoming times for Mixed Breed, Labrador Retriever, and Border Collie dogs fall between **17 to 24 weeks**. No significant difference is found between the rehoming times across these breeds.

## Contributors

- **Naveen Sabarinath Babu**

