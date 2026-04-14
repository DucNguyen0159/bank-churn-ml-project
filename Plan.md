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
- **Logistic Regression** (feature importance / coef): which features increase churn risk?
- **Neural Network** (nonlinear relationships): can a more complex model do better?
- **Tree-based method:**
  - **Decision tree** — if–else rules; what decision patterns lead to churn?
  - **Random forest** — ensemble of trees; often stronger accuracy and stability than a single tree, with feature importances that summarize many trees.
- **KNN** (similarity-based learning): do customers behave like others who churned? If similar profiles churned, this one might too.

Pipeline: start simple (logistic) → add complexity (neural net) → **tree-based models (decision tree + random forest)** → similarity-based comparison (KNN).