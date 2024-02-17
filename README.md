# Mock-Product-Analysis-by-R

A hands-on project analyzing simulated user interaction and demographic data to uncover insights into engagement patterns and product performance, mirroring analytics practices for Meta-like platforms.

## Overview

This repository contains a mock analysis project simulating the process of analyzing product usage and user engagement within a digital platform similar to Meta's products. Using fabricated datasets, this project aims to provide insights into how data analytics can be applied to understand user behavior, improve product features, and drive strategic decisions.

## Datasets Overview

The `data/` directory contains simulated datasets that mimic user interactions and demographics on a social media platform. These datasets have been created for illustrative purposes to demonstrate data analysis techniques.

### `meta_products.csv`

Simulated data representing user interactions with various platform products, including columns for:

- **date**: Interaction date (YYYY-MM-DD).
- **user_id**: Unique user identifier.
- **product**: Platform product interacted with (e.g., "Groups", "Pages", "News Feed").
- **time_spent**: Interaction duration in minutes.
- **user_type**: User categorized as 'new' or 'returning'.
- **user_region**: User's geographical region.
- **engagement_score**: User's engagement level score from 1 to 10.
- **device_type**: Type of device used for interaction.
- **transactions**: Number of transactions made during interaction.
- **transaction_value**: Total value of transactions made.
- **user_state**: Indicates if interaction was on user's first action date.
- **acquisition_cohort**: Month and year of user's first platform interaction.

### `meta_demographic_data.csv`

Provides demographic details for a subset of users, including:

- **user_id**: Links to `meta_products.csv` dataset.
- **age**: User's age.
- **gender**: User's gender (Male, Female, Other).
- **occupation**: User's occupation.
- **user_region**: User's geographical region.
- **country**: User's country of residence.

## Implementation Overview

This section outlines the methodology and steps taken in the mock product analysis, simulating real-world data analysis workflows in product analytics with a focus on user engagement and demographic insights.

### Methodology

The analysis follows key phases:

1. **Data Cleaning and Preparation**: Addressing missing values, outliers, and data type conversions.
2. **Exploratory Data Analysis (EDA)**: Understanding data patterns through distribution analysis and segmentation.
3. **Engagement Analysis**: Evaluating user engagement by calculating engagement scores and identifying trends.
4. **Demographic Insights**: Analyzing demographic data to identify factors influencing product usage.
5. **Visualization**: Using histograms, bar charts, and scatter plots for intuitive presentation of findings.

### Tools and Technologies

- Utilized **R and RStudio** with `tidyverse`, `lubridate`, and `ggplot2`.
- Documentation and reproducibility facilitated through **Markdown** and R Markdown.

### Challenges and Solutions

- Overcame data simulation challenges by designing datasets that reflect real-world user interaction patterns.
- Developed a weighted scoring system for meaningful engagement analysis.

### Reproducibility

All code, datasets, and documentation are available in this repository, encouraging users to explore, replicate the analysis, and apply the methods to similar datasets.

### Conclusion

This project demonstrates the application of data analysis techniques to derive insights from user interaction and demographic data, showcasing how analytics can inform product development and marketing strategies in a digital platform context.
