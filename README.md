# Mock-Product-Analysis-by-R
A hands-on project analyzing simulated user interaction and demographic data to uncover insights into engagement patterns and product performance, mirroring analytics practices for Meta-like platforms.

## Overview
This repository contains a mock analysis project that simulates the process of analyzing product usage and user engagement within a digital platform similar to Meta's products. Using fabricated datasets, this project aims to provide insights into how data analytics can be applied to understand user behavior, improve product features, and drive strategic decisions.

## `data/` Directory

Contains the simulated datasets that mimic user interactions and demographics on a social media platform. These datasets have been created for illustrative purposes to demonstrate data analysis techniques.

### `meta_products.csv`

Simulated data representing user interactions with various platform products. It includes the following columns:

- **date**: The date of the interaction (YYYY-MM-DD), indicating when the user interacted with the product.
- **user_id**: A unique identifier for each user, allowing us to track user activity across different sessions.
- **product**: The name of the platform product (e.g., "Groups", "Pages", "News Feed") the user interacted with, showing the variety of platform features used.
- **time_spent**: The duration of the interaction in minutes, providing insights into user engagement with each product.
- **user_type**: Categorizes users into 'new' or 'returning', helping to analyze user retention and attraction strategies.
- **user_region**: The geographical region of the user, useful for regional analysis and localization strategies.
- **engagement_score**: A score from 1 to 10 representing the user's engagement level, quantifying how interactively users engage with the product.
- **first_action_date**: The date of the user's first interaction on the platform, important for cohort analysis and understanding user lifecycle.
- **device_type**: Specifies the type of device (e.g., mobile, desktop, tablet) used for the interaction, indicating device preferences among users.
- **transactions**: The number of transactions made during the interaction, if applicable, to track monetization and purchasing behavior.
- **transaction_value**: The total value of transactions made, providing insights into revenue generation from user interactions.
- **user_state**: Indicates whether the interaction was on the user's first action date, helping to differentiate between initial and subsequent user behavior.
- **acquisition_cohort**: The month and year when the user first interacted with the platform, useful for tracking user acquisition trends over time.

### `meta_demographic_data.csv`

Complements the user interactions data by providing demographic details for a subset of users, including:

- **user_id**: Links to the `meta_products.csv` dataset, ensuring consistency in user identification across datasets.
- **age**: The age of the user, allowing for age-specific analysis and targeting.
- **gender**: The user's gender (Male, Female, Other), useful for gender-specific insights and product personalization.
- **occupation**: Specifies the user's occupation (e.g., Student, Professional, Retired, Unemployed), offering a glimpse into the user base's professional diversity.
- **user_region**: Mirrors the `meta_products.csv` dataset, facilitating combined analysis of user behavior and demographics.
- **country**: Provides the country of residence, adding an additional layer of geographical granularity to the analysis.

These datasets serve as the foundation for a comprehensive mock analysis, aiming to replicate the kinds of insights that might be derived from real-world product analytics in a social media context.
