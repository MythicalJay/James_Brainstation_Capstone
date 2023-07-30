# Flight Delay Prediction using Supervised Machine Learning

## Introduction

This project focuses on predicting flight delays using supervised machine learning techniques. The objective is to build models that accurately classify and identify the key factors affecting flight delays in three categories: 'Long Delay', 'Minor Delay', and 'No Delay'. The analysis aims to provide valuable insights for airlines and airports to optimize their operations, manage resources efficiently, and enhance customer satisfaction.

## Data Preprocessing

The initial dataset comprised 6.5 million data points from the Bureau of Transportation Statistics and National Centers for Environmental Information. To efficiently analyze the problem, a subsample of 300k data points was taken, with equal representation of the three classes to avoid model bias. Outliers and missing data were removed to ensure data quality.

## Modeling Approach

Five supervised machine learning algorithms were tested to predict flight delays:

1. Logistic Regression
2. Decision Tree Classification
3. Random Forest Classification
4. Support Vector Machines (SVM)
5. XGBoost Classification

The models were evaluated based on accuracy and recall scores for each class, with additional scoring methods, hyperparameter tuning, and feature visualization techniques, such as PCA and thresholding.

## Model Performance

The logistic regression model served as the base model with an accuracy of 46.58%. The decision tree classification model achieved an accuracy of 46.80% after hyperparameter tuning. The random forest model outperformed other models with an accuracy of 48.33% and a remarkable recall of 59.28% for 'Long Delay' predictions. SVM with the RBF kernel achieved an accuracy of 42.61% and a recall of 51.16% for 'Long Delay' on a 60% subsample. The XGBoost classification model showed promise with an accuracy of 49.93% and a recall of 49.32%, though hyperparameter tuning revealed a wide range of accuracy scores.

## Insights and Implications

The flight delay prediction models provided valuable insights into the factors affecting flight delays:

- Weather-Related Factors: Heavy rain, wind, and high temperatures significantly influence flight delays.
- Passenger Count Impact: The average monthly passenger count at the airport affects delays and resource allocation.
- Airline-Specific Patterns: Certain airlines exhibit patterns that influence flight delays, requiring targeted strategies for operational optimization.

## Future Directions

- Addressing Data Noise: Investigate and mitigate the effects of noise in the dataset to enhance model performance.
- Optimizing Airline Operations: Implement targeted strategies to reduce delays and enhance customer satisfaction based on airline-specific patterns.
- Enhancing Resource Allocation: Explore the relationship between passenger count and delays to optimize resource allocation during peak times.

## Conclusion

The flight delay prediction models provide airlines and airports with valuable information for operational optimization and better customer service. The Random Forest model, with threshold adjustment, achieved a good balance of recall and accuracy for 'Long Delay' predictions. Going forward, refining the models, addressing data noise, and exploring airline-specific patterns will lead to more accurate and reliable flight delay predictions. This proactive approach will help airlines manage delays, minimize passenger inconvenience, and enhance overall flight operations.

---

*Note: This project is part of a data science exploration, focusing on supervised machine learning. The insights and models provided are based on the available dataset as of the specified date and may not reflect real-time conditions. The report is intended for informational purposes only and should not be used as a sole basis for decision-making in the aviation industry.*

## Author

James Church

## Date

August 2023

---

*Note: This project is part of a data science exploration, focusing on supervised machine learning. The insights and models provided are based on the available dataset as of the specified date and may not reflect real-time conditions. The report is intended for informational purposes only and should not be used as a sole basis for decision-making in the aviation industry.*