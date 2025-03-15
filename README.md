# Boosting-Yulu-s-Revenue-Through-Weather-Analysis-

Rental Bikes Analysis

Overview

This repository contains the statistical analysis of rental bike usage based on various factors such as weekdays, weekends, seasons, and weather conditions. The analysis employs hypothesis testing techniques including t-tests, ANOVA, Levene's test, and Chi-Square tests to derive meaningful insights from the dataset.

Statistical Findings

Two-Sample t-test:

The test suggests that we should accept the null hypothesis (H₀) statistically at a 5% significance level, as the p-value (0.22) > 0.05.

This indicates that there is no significant difference in the mean count of rental bikes on weekends/holidays compared to working days.

ANOVA Test:

The ANOVA test shows that season and weather have a significant impact on Yulu bike counts at a 5% significance level.

Additionally, Levene's test confirms that the variances are not equal for all weather conditions and seasons.

Chi-Square Test:

There is a significant relationship between season and weather conditions.

Seasonal Analysis:

Among the four seasons, Season 3 (Fall) had the highest rental bike count (~950), followed by Season 4, Season 2, and Season 1.

Weather Condition Analysis:

Weather condition 1 (Clear/Few Clouds) had the highest mean rental bike count (205.24), followed by conditions 2, 3, and 4.

Peak Usage Insights:

In summer, during weekends/holidays, the highest rental count recorded was 1893 bikes.

In the fall season, under weather condition 1 (Clear/Few Clouds), the highest rental count recorded was 1930 bikes.

Repository Contents:

Data: Raw dataset used for analysis.

Scripts: Python/R scripts for performing statistical tests.

Results: Outputs and visualizations of the analysis.
