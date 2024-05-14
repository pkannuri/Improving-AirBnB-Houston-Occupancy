# Improving-AirBnB-Houston-Occupancy

## Project Overview
This project analyzes the Airbnb market in Houston, focusing on enhancing host satisfaction, optimizing occupancy rates, and ultimately driving up revenue. By analyzing data from the `airbnb_Houston.csv` dataset, this study aims to predict overall guest ratings and occupancy rates to empower hosts with actionable insights for improving service quality and competitive positioning in the market.

## Business Problem
The project addresses two main challenges in the Airbnb Houston market:
1. **Predicting Overall Guest Ratings:** Identifying key factors that enhance guest satisfaction and influence ratings, which are crucial for hosts to improve their service and maximize revenue.
2. **Predicting Occupancy Rates:** Developing a model to forecast occupancy rates based on variables like number of reviews, reservations, and nightly rates, assisting hosts in strategically managing their listings for optimal revenue.

## Data Summary
- **Source:** `airbnb_Houston.csv`
- **Size:** Approximately 146MB
- **Contents:** 118,677 rows and 111 columns, mixing 103 numerical and 7 categorical columns. The dataset includes detailed information on listings, host properties, and guest reviews in Houston.

## Modelling Approach
- **Feature Selection:** Identifying the most influential factors affecting ratings and occupancy.
- **Model Development:** Using machine learning techniques like Random Forest, Lasso Regression, and Gradient Boosting to predict outcomes.
- **Validation:** R-squared and RMSE metrics are used to evaluate model performance on training and test datasets.

### Key Models
1. **Overall Ratings Prediction:** Utilizes features like previous ratings, number of reviews, and host responsiveness.
2. **Occupancy Rate Prediction:** Focuses on variables such as number of reservations, booked days, and guest reviews.

## Business Insights
- **Service Enhancement:** Emphasizing the importance of maintaining high service quality through consistent ratings and positive guest reviews.
- **Revenue Optimization:** Demonstrating how occupancy rates correlate with revenue, suggesting strategies for hosts to enhance earnings.
