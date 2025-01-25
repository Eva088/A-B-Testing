# A/B Testing Analysis - Marketing Campaign

## Objective

The goal of this project is to analyze the effectiveness of ads in a marketing campaign by performing an A/B test. The **experimental group** (ad group) is exposed to ads, while the **control group** (PSA group) is shown public service announcements (PSAs). The main objective is to determine whether the ads led to higher conversions and assess if the difference between the groups is statistically significant.

## Dataset Overview

- **Test group**: Indicates if the user saw an ad ('ad') or a PSA ('PSA').
- **Converted**: Whether the user made a purchase (True/False).
- **Total ads**: The total number of ads seen by the user.
- **Most ads day**: The day with the most ads viewed.
- **Most ads hour**: The hour when the most ads were viewed.

## Key Insights

- **Conversion Rates**: 2.52% of users converted (made a purchase).
- **Most Active Day**: Ads were mostly viewed on Fridays (15.75% of views).
- **Peak Hour**: The most common viewing hour was 1:00 PM (13:00).
- **Test Group Conversion**: Ads showed a higher conversion rate (2.55%) than the PSA group (1.78%).

## Statistical Analysis

- **Chi-squared Tests**: The conversion rates significantly vary based on the test group, day, and hour of viewing.
- **Mann-Whitney U Test**: Since assumptions of normality and equality of variance were violated, a non-parametric test was used to compare the number of ads seen by converters and non-converters. The result showed that the number of ads viewed significantly influenced conversion rates.
