# Risk Analysis AI-driven Automation

## Background Story

As governments seek to streamline immigration processes, AI systems are increasingly used to assess applications, flag risks, and make eligibility recommendations. But with this promise comes uncertainty: What if the algorithms misclassify risk due to biased training data or lack of transparency? A single mislabeling could mean denial of entry, separation from family, or unjust surveillance. This risk assessment aims to identify, categorize, and evaluate the potential harms and unintended consequences of using AI in immigration, ensuring that innovation does not come at the cost of fairness or human dignity.


## Model Selection for Instructional Purposes

This notebook uses a **Random Forest Classifier** to demonstrate a simple and interpretable approach to risk severity classification using Likelihood and Impact scores.

> **Note:** This modeling choice is intentionally limited to support learning objectives. It is **not optimized for deployment or production use**.

We use `RandomForestClassifier` for the following instructional reasons:

* The dataset is **small**, and the primary goal is to illustrate the **end-to-end pipeline**: from risk scoring to severity prediction and heatmap visualization.
* Random Forests provide a **robust and reliable baseline model** that requires minimal tuning.
* They support **interpretability** through:

  * Feature importance scores
  * Decision rule analysis (e.g., via trees)
* The model handles **non-linear relationships** and works well with mixed feature types (numeric, categorical).

### Educational Context

This example is designed for **practice and instructional use**, such as in data science, risk analytics, or operations research classes. For real-world applications, model comparisons, hyperparameter tuning, and fairness/equity checks are strongly recommended.


