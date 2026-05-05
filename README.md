# E-Commerce Cosmetics Consumer Behavior Analytics

## Overview
This project analyzes customer behavior in an e-commerce cosmetics platform using predictive analytics and machine learning techniques to identify the factors influencing whether customers add products to their shopping cart.

## Business Question
What are the top factors that influence a customer to keep a product in their cart?

## Dataset
The dataset contains:
- 3,663,737 observations
- Customer interaction and shopping behavior data from an e-commerce cosmetics platform

### Key Variables
- Event Type Cart
- Product ID
- Category ID
- Category Code
- Brand
- Price
- User ID
- User Session
- Time of Day Variables

## Tools & Technologies
- R
- Logistic Regression
- Decision Tree
- Predictive Analytics
- Marketing Analytics
- Data Visualization
- ROSE Oversampling Technique
- Exploratory Data Analysis (EDA)
- R Markdown

## Data Preprocessing
- Removed outliers
- Handled missing and inappropriate values
- Converted brand variables into binary categories
- Grouped category codes into major product categories
- Created new time-of-day variables:
  - Morning
  - Afternoon
  - Evening

## Data Balancing
The dataset was highly imbalanced:
- Before balancing:
  - 0 (Not Added to Cart): 2,499,650
  - 1 (Added to Cart): 1,164,087

ROSE oversampling technique was used to balance the target variable and improve model performance.

## Models Used

### Logistic Regression
Used to predict the probability of customers adding products to their cart.

### Decision Tree
Used to identify important customer behavior patterns and classification rules.

## Model Performance

| Model | Accuracy | Sensitivity | Specificity |
|------|------|------|------|
| Logistic Regression | 52.5% | 49.4% | 59.1% |
| Decision Tree | 62.0% | 74.7% | 34.7% |

## Key Findings
- Product price was identified as the most influential factor affecting cart behavior.
- Time of day significantly impacted customer engagement patterns.
- Brand recognition influenced purchasing behavior.
- Decision Tree model achieved better predictive performance compared to Logistic Regression.

## Business Recommendations
- Offer discounts to frequent users to improve retention and conversions.
- Perform customer lifetime value analysis for targeted marketing.
- Optimize promotions based on customer activity time periods.
- Improve product categorization and brand grouping for better analytics.

## Business Impact
This project demonstrates practical applications of:
- Customer behavior analytics
- Predictive modeling
- Marketing analytics
- E-commerce optimization
- Customer segmentation

## Repository Contents

| File | Description |
|------|-------------|
| ecommerce_cosmetics_behavior_analysis.Rmd | Main predictive analytics and modeling code |
| ecommerce_cosmetics_behavior_output.html | Rendered project analysis output |
| Ecommerce_Cosmetics_Consumer_Behavior_Report.pdf | Final project report |
| Ecommerce_Cosmetics_Analytics_Presentation.pptx | Project presentation |

## Authors
- Trilok Dhanekula
- Deekshita Chithajhallu
