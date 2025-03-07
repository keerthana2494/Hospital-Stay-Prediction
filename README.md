# Hospital-Stay-Prediction
# *1. Introduction*
- This report presents an analysis of classification models and hospital patient stay data. We evaluate the performance of various classification models and build a predictive model for estimating the length of hospital stay based on multiple factors.
  
# *2. Classification Model Evaluation*
# *2.1 Logistic Regression*

- Usage: Classification problems.

- Business Relevance: Reliable for operational decision-making with consistent accuracy.

- Performance:

   - Training Accuracy: 82%

  - Testing Accuracy: 82%

 - Observation: Balanced model performance, no overfitting or underfitting.

 - Impact: Useful for predicting patient outcomes with stable generalization.

# *2.2 Decision Tree*

- Usage: Classification and regression problems.

-  Business Relevance: High accuracy in training but prone to overfitting, which may lead to            unreliable operational decisions.

- Performance:

   - Training Accuracy: 99%

   - Testing Accuracy: 75%

- Observation: Overfitting is present as training accuracy is very high compared to testing accuracy.

- Impact: Risk of incorrect predictions affecting hospital resource allocation.

# *2.3 K-Nearest Neighbors (KNN)*

- Usage: Classification and regression problems.

- Business Relevance: Moderate accuracy with scalable implementation.

- Performance:

     - Training Accuracy: 85%

     - Testing Accuracy: 81%

- Observation: Moderate generalization performance.

- Impact: Suitable for predicting patient behavior trends.

# *2.4 Gradient Boosting*

- Usage: High predictive accuracy, flexibility, robustness.

- Business Relevance: Strong performance with consistent predictions.

- Performance:

     - Training Accuracy: 84%

    - Testing Accuracy: 83%

- Observation: Good generalization with minimal overfitting.

- Impact: Ideal for optimizing patient stay predictions and reducing costs.

# *3. Machine Learning Model for Predicting Length of Stay*   
# *3.1 Problem Statement*

Predict the length of stay (in days) of a patient in the hospital based on various admission-related factors.

# *3.2 Features Used*

- Categorical Features: Hospital Type, Region, Department, Ward Type, Admission Type, Severity of Illness, Age.

- Numerical Features: Available Extra Rooms, Visitors with Patient, Admission Deposit.

 Key Business Metrics

- Bed Utilization Rate: Predicting stay duration helps in maximizing bed availability.

- Revenue Forecasting: Longer stays influence hospital revenue streams.

- Patient Satisfaction: Efficient prediction leads to better patient experience.

# *3.3 Model Selection & Training*

- Algorithm Used: Gradient Boosting (Best Performance in Evaluation)

- Preprocessing Steps:

    - Data preprocessing to enhance model accuracy.

    - Handling missing values.
 
    - Encoding categorical variables.

    - Normalizing numerical features.
 
    - Predictive analytics for hospital administration.
 
    - Cost and revenue optimization through forecasting models.

- Performance Metrics:

     - Training Accuracy: 84%

     - Testing Accuracy: 83%

     - Mean Absolute Error (MAE): Evaluates prediction error.
 
     - Business Impact: Reduced operational costs and improved patient flow management.
       
# *3.4 Conclusion*

The Gradient Boosting model provides a well-balanced performance for predicting hospital stay duration. Further tuning and feature engineering may enhance accuracy.

- Optimized Resource Allocation: Predictive insights improve hospital efficiency.

- Financial Planning: Accurate length-of-stay predictions enhance budget planning.

- Future Considerations:

     - Advanced analytics for bed capacity planning.

     - AI-driven decision-making models for hospital administration.
