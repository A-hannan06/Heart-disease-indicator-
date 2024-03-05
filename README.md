## Heart Disease Prediction with Resampling Techniques

##### Overview
The project aims to estimate the probability of a patient suffering from heart disease based on various health metrics. The data used is from the Behavioral Risk Factor Surveillance System (BRFSS), spanning all 50 states in the United States.

##### Highlights
- The dataset is imbalanced (91% no heart disease, 9% yes), prompting the application of resampling techniques to ensure model performance across both classes.
Utilized Random Under Sampling (RUS), Synthetic Minority Over-sampling Technique (SMOTE), and ADASYN in combination with Random Forest Classifier, XGBoost Classification, and ADABoost classification.
- Tuned XGBoost model achieved a recall of 0.82, offering better performance than a generic logistic regression model.
- Adjusting the threshold from 0.5 to 0.4 increased recall to 0.88, with precision improving from 0.22 to 0.72.

##### Future Work
- Implement SHAP values for a forward approach to interpreting predictions.
- Collect additional medical history data for more comprehensive risk assessment.
- Use Bayesian Optimization to compute counterfactual cases and understand the impact of changes on predicted probabilities.
