# 🛡️ Family Service Centre (FSC) Triage Application: Domestic Violence Risk Predictor

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) 

### The Mission
Social workers at Family Service Centres face immense caseloads, making it difficult to instantly identify which families are at the highest immediate risk of domestic violence. This project provides a machine-learning-driven triage application to help prioritize cases, ensuring that vulnerable families receive proactive, life-saving interventions faster.

### The Solution
I built an end-to-end predictive model and application designed for ministry-level stakeholders. By analyzing historical case data and demographic indicators, the application assigns a "Risk Probability Score" to new intakes.

### Technical Methodology
- **Data Privacy:** Handled highly sensitive case data with strict anonymization protocols. *(Note: Raw data is excluded from this repository to protect PII. Synthetic data is provided for code execution).*
- **Modeling:** Evaluated multiple classification algorithms, ultimately selecting **Random Forest** and **kNN** for their ability to handle non-linear relationships and provide interpretable feature importance for social workers.
- **Deployment:** Packaged the model into a user-friendly application interface for non-technical caseworkers.

### Key Insights
* **Feature Importance:** Identified that [Insert Feature, e.g., frequency of past police visits] was the strongest predictor of escalation, overriding traditional socioeconomic indicators.
* **Model Accuracy:** Achieved an F1-score of [Insert Metric]% in predicting high-risk minority classes, minimizing false negatives (which carry a high human cost).

### How to Run Locally
1. Clone the repo: `git clone [your-link]`
2. Install dependencies: `pip install -r requirements.txt`
3. Launch the app: `python app/triage_app.py`
