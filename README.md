# Logistic Regression
Logistic regression is a statistical technique for binary classification. It models the probability of a binary outcome (in this case, diabetes: yes or no) as a logistic (sigmoid) function of a weighted sum of predictors (age, BMI, glucose levels, etc.) 
The model outputs a probability between 0 and 1. , 
A common threshold is 0.5: above → predicts diabetes (1); below → no diabetes (0)

* In this dataset There are 9 columns and 768 rows.
* Algorithm Used: Logistic Regression
* Libraries: scikit-learn, pandas, matplotlib, seaborn

🔍 Feature Insight 
* In logistic regression models on the Diabetes dataset, glucose levels are the most powerful predictor of diabetes risk, closely followed by BMI, number of pregnancies, age, and genetic predisposition, while insulin, blood pressure, and skinfold thickness show minimal predictive power.”

✅ Model Accuracy 
* "Achieved 75% accuracy using Logistic Regression, indicating good model performance in classifying target variables with moderate precision. Further tuning or feature engineering could enhance results." Logistic  regression yields solid baseline performance on this dataset—typically classifying correctly about 3 out of every 4 instances.

Conclusion : 
* Logistic Regression on the Diabetes dataset achieved 75% accuracy. Key drivers are glucose > BMI > pregnancies > age > family history.
 Logistics works well as an interpretable baseline that highlights which features matter most in estimating risk.
