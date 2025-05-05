# -Diabetes-Prediction-Using-Machine-Learning
This project aims to predict whether an individual is likely to have diabetes using machine learning models. We use the Pima Indian Diabetes Dataset, a widely-used benchmark for medical prediction tasks, containing 768 records with 8 health-related features (like glucose level, BMI, and age) and a binary outcome (1 = diabetic, 0 = non-diabetic).
To evaluate performance, we compare three supervised learning algorithms:

✅ Logistic Regression
A linear classification model ideal for baseline comparisons. It’s simple, interpretable, and effective for datasets with linear relationships. However, it may not capture complex patterns in the data.

🌲 Random Forest
An ensemble of decision trees that improves accuracy and reduces overfitting. It captures non-linear relationships and ranks feature importance but is less interpretable than logistic regression.

⚡ XGBoost
A powerful gradient boosting algorithm that excels in handling structured/tabular data. It provides the best performance through regularization and advanced tree boosting techniques, but it requires careful hyperparameter tuning.

📊 Evaluation Metrics
We assess the models using:

Accuracy: Overall correctness

Precision: Correct positive predictions

Recall: Ability to find actual positives

F1-Score: Balance of precision and recall

AUC-ROC: Classifier's ability to distinguish classes

📈 Results (Example)
Model	Accuracy	Precision	Recall	F1-Score	AUC-ROC
Logistic Regression	77.5%	0.72	0.65	0.68	0.82
Random Forest	81.0%	0.76	0.71	0.73	0.86
XGBoost	84.5%	0.81	0.75	0.78	0.89

✅ Conclusion
XGBoost outperforms the other models in accuracy and AUC, making it the most suitable for diabetes prediction in this study. However, logistic regression remains a strong choice when interpretability is key.
