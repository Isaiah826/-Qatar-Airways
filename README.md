# Qatar Airways Customer Review Analysis

This project presents the analysis of customer reviews for Qatar Airways, scraped from a popular airline review site. The primary goal of the analysis is to identify key factors influencing customers' likelihood to recommend the airline to others. Insights derived from this analysis aim to provide actionable recommendations to improve Qatar Airways' service quality and overall customer satisfaction.

## Data Overview

The data consists of over 2,000 reviews spanning eight years (2014-2023), covering the following aspects:

- Flight quality
- Seat comfort
- Food and beverage
- Staff service
- Entertainment
- Value for money
- Overall rating

## Analytical Methods

The analysis was performed using various statistical and machine learning techniques, including:

- Descriptive statistics
- Correlation analysis
- Machine learning algorithms

## Key Findings

The findings reveal how different service quality aspects contribute to customer satisfaction and loyalty, highlighting opportunities for improvement.

### Machine Learning Models

A model was trained and evaluated to predict whether a customer would recommend or not recommend the airline based on the scraped variables. The machine learning algorithms used are:

- Logistic Regression
- Random Forest
- Support Vector Classification (SVC)
- LightGBM
- XGBoost
- CatBoost

### Evaluation Metric

Given the imbalanced nature of the dataset, the **F1 score** was used as the primary evaluation metric. The F1 score balances precision and recall, making it suitable for the goal of accurately predicting whether Qatar Airways will be recommended by a customer.

### Model Performance

All six models developed achieved an F1 score of 92% or higher, indicating their robustness and ability to predict the likelihood of a customer recommending the airline. Notably:

- **LightGBM** had the highest F1 score of 95%.
  
  The confusion matrix for LightGBM shows:
  - 493 correct predictions for those who would recommend the airline
  - 116 correct predictions for those who would not recommend the airline
  - 18 incorrect classifications for those who recommended the airline
  - 31 incorrect classifications for those who would not recommend the airline

## Conclusion

This project analyzed customer reviews of Qatar Airways, identifying factors that influence customers' willingness to recommend the airline. Key findings include:

- Flight quality, seat comfort, food and beverage, and value for money are strong determinants of customer recommendations.
- Other factors like Wi-Fi connectivity, inflight entertainment, and cabin staff service also contribute but are less significant.

The data revealed a steady decline in the number of flights taken between 2014 and 2023, except for a surge in 2022. To increase customer recommendations, service quality across different seat types must improve with a goal of achieving a 4-star rating across all services rendered.

## Recommendations for Qatar Airways

1. **Maintain and enhance flight quality**, the core aspect of its service delivery and customer loyalty.
2. **Invest in staff training and motivation** to improve staff service and customer relations.
3. **Offer more competitive prices and discounts** to increase the value for money perception and attract more customers.
4. **Upgrade seat comfort and design** to enhance the customer experience.
5. **Diversify food and beverage options** to cater to different tastes and preferences.
6. **Provide more entertainment choices** to enrich the customer experience.

By implementing these recommendations, Qatar Airways can further improve its service quality and customer satisfaction, increasing its rate of recommendation amidst other airlines.
