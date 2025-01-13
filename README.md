# Predicting 30-Day Hospital Readmissions in Diabetic Patients

## Overview
This project focuses on predicting whether diabetic patients will be readmitted to the hospital within 30 days. Hospital readmissions are a critical indicator of healthcare quality and resource utilization. Using classification machine learning models and a comprehensive dataset from the UCI Machine Learning Repository, we aimed to improve healthcare outcomes by identifying high-risk patients.

---

## Project Objectives
1. Analyze diabetic patient records to identify patterns associated with readmissions.
2. Develop and compare machine learning models to predict 30-day readmissions.
3. Optimize recall to minimize false negatives and ensure critical patients are identified.

---

## Methodology
1. **Data Processing:**
   - Data cleaning: Handling missing values and duplicates.
   - Data transformation: Changing data types and encoding categorical features.
   - Feature engineering: Exploring relationships and adding new features.

2. **Model Training and Evaluation:**
   - Models used: Logistic Regression, Decision Tree, Gradient Boosting, XGBoost.
   - Data split: Training (70%) and testing (30%).
   - Hyperparameter tuning with GridSearchCV for optimal performance.
   - Metrics: Accuracy, Recall, Precision, F1 Score.

3. **Challenges:**
   - Long execution times for Random Forest and KNN models led to their exclusion.
   - Balancing complexity and efficiency during hyperparameter tuning.

---

## Results
- Gradient Boosting emerged as the most optimal model, achieving high recall, ensuring high-risk patients were identified, and balancing overall performance.
- SHAP analysis revealed key features impacting predictions, enhancing interpretability.
- Model improvements directly support reduced readmissions, improved patient care, and cost efficiency for hospitals.

---

## Future Work
- Explore additional features and datasets to enhance predictive performance.
- Test alternative models like deep learning for potential improvements.
- Optimize computational efficiency to handle larger datasets.

---

## Acknowledgments
This project was completed as part of **IMSE 586 - Big Data Analytics and Visualization (Fall 2024)**. Special thanks to our instructor for guidance and the UCI Machine Learning Repository for providing the dataset.
