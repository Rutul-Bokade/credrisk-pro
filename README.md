# credrisk-pro
💼 Credit Risk Classification Using Logistic Regression — Cred Risk Pro
🚀 Executive Summary
In the world of high-stakes finance, risk isn't an option—it's a metric. RiskLens is a purpose-built, high-performance credit risk classification engine designed to separate high-risk loan applicants from financially sound borrowers with ruthless precision. This isn’t just another academic model. It’s a data-driven underwriting weapon, trained to protect capital, flag hidden liabilities, and redefine creditworthiness in real time.

🎯 Purpose
Banks don’t get second chances. This model was created with a singular goal: eliminate misclassified risk. Using key borrower metrics—loan size, interest rate, income, DTI ratio, credit history, and derogatory marks—we built a machine learning solution that distinguishes healthy loans from high-risk ones before the ink dries. If default prediction is the game, this model is playing to win.

⚙️ Process
We engineered two variants of the Logistic Regression model:

Model 1 – Raw Reality: Trained on an imbalanced dataset (75k+ healthy vs. 2.5k high-risk loans). Real-world skew, real-world challenge. Despite the imbalance, this model performed exceptionally well in flagging default risk, exposing high-risk patterns hidden in noise.

Model 2 – Resampled Precision: To maximize recall for high-risk cases, we rebalanced the data (56k each) and trained a second model. The result? Symmetrical accuracy across classes, reducing false positives and maximizing protection against bad lending decisions.

We rigorously validated both using:

Confusion Matrices

ROC-AUC

Precision, Recall, F1-Score

SHAP for explainability

📈 Results
Metric	Model 1 (Original Data)	Model 2 (Resampled Data)
Balanced Accuracy	99%	99%
Precision (High-Risk Loans)	85%	99%
Recall (High-Risk Loans)	91%	99%

📊 Interpretation:
Model 1 is a sniper—laser-focused on healthy loans but occasionally misses risk.

Model 2 is a fortress—equally accurate but better armored against high-risk loan applicants.

In lending, the cost of a false negative (missing risk) is massive. Model 2 plays offense and defense.

🧠 Why It Matters
This model isn’t theoretical—it’s practical. It gives fintechs and banks an edge in underwriting, letting them:

Slash default rates

Tighten approval pipelines

Justify lending decisions with explainable AI (via SHAP)

When you're managing millions, gut feeling isn’t enough. RiskLens brings the analytics muscle to your credit decisioning desk.
