Story: 
Banks are losing customers due to churn, which directly impacts revenue. Retaining an existing customer is significantly cheaper than acquiring a new one.
In this project, we aim to predict which customers are likely to churn based on their demographic and financial behavior.
By identifying high-risk customers early, the bank can take proactive actions such as offering incentives or improving services to retain them.

Goal: who will leave?

Outcome: 
Predict churn (0 or 1)
Evaluate model performance
Understand what factors drive churn

Methods:
- Logistic Regression (feature importance/coef): which features increase churn risk?
- Neural Network (nonlinear relationships): Can a more complex model do better?
- Decision Tree (if-else rules): What decision patterns lead to churn?
- KNN (similarity-based learning, instance-based model): Do customers behave like others who churned? If customers with similar profiles churned, this one might too

With those methods, we have a pipeline: start simple - add complexity- add interpretability - compare with a different learning approach. 