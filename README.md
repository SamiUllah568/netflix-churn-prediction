# Netflix User Analytics and Churn Prediction

This project aims to analyze Netflix user data to gain insights into user behavior, revenue patterns, and predict user churn based on available features. By identifying at-risk customers, this project offers potential strategies for improving user retention and revenue growth.

## Project Overview

- **Objective**: Predict user churn and gain insights into Netflix user behavior.
- **Data**: User data with features such as `Subscription Type`, `Monthly Revenue`, `Join Date`, `Last Payment Date`, `Country`, `Age`, `Gender`, `Device`, and more.

## Key Features and Analysis

1. **Data Analysis**:
   - **Subscription Type Distribution**: Breakdown of different subscription types by country and gender.
   - **Monthly Revenue Analysis**: Distribution of monthly revenue by subscription type, age group, and device type.
   - **Join Date Trends**: Monthly and seasonal sign-up trends.
   - **Device Insights**: Analysis of device popularity among different user demographics.
  
2. **Revenue and Churn Analysis**:
   - **Revenue Growth Trends**: Monthly revenue growth trends across countries.
   - **User Retention**: Average plan duration and churn rate calculations based on a set threshold.
   - **Churn Rate**: Defined as users who haven’t made payments in the last 90 days.

3. **Machine Learning**:
   - **Features**: `Subscription Type`, `Avg Monthly Revenue`, `Age Group`, `Days Since Last Payment`, and `Plan Duration`.
   - **Models**: Tested multiple models (e.g., Logistic Regression, Random Forest) for predicting user churn.

## Project Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SamiUllah568/netflix-churn-predicton.git
   cd netflix-churn-predictont
