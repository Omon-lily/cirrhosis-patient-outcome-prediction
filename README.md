# cirrhosis-patient-outcome-prediction
End-to-end machine learning project predicting cirrhosis patient outcomes using Python, Random Forest, XGBoost, GridSearchCV, and Power BI. Includes data preprocessing, exploratory data analysis, model evaluation, and predictive analytics.
# Cirrhosis Patient Outcome Prediction Using Machine Learning & Power BI

**Project Overview**

Developed an end-to-end machine learning project to predict patient outcome categories using a cirrhosis clinical dataset. The project focused on applying data analytics and predictive modelling techniques to explore clinical indicators, identify patterns, and evaluate the potential of machine learning in healthcare analytics.

**Project Objectives and Methodology**

- Performed data cleaning, preprocessing, and exploratory data analysis (EDA) using Python.
- Conducted correlation analysis to understand relationships between clinical and laboratory variables.
- Applied feature selection, excluding ID and N_Days from the final prediction model.
- Developed and compared Random Forest and XGBoost classification algorithms.
- Applied GridSearchCV for hyperparameter tuning.
- Evaluated model performance using accuracy, precision, recall, F1-score, and confusion matrices.
- Investigated class imbalance and the challenges of predicting the minority CL class.
- Developed a new-patient prediction workflow.
- Integrated machine learning prediction results into Power BI for interactive reporting and visualization.

**Model Performance**

- Random Forest: 71% accuracy.
- Tuned Random Forest: 73% accuracy.
- XGBoost: 75% accuracy.

Although XGBoost achieved the highest accuracy, Random Forest demonstrated better minority-class detection, identifying 1 out of 5 CL cases in the test set. This highlighted the importance of evaluating recall and F1-score rather than relying solely on accuracy.

**Tools and Technologies**

Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Random Forest | XGBoost | GridSearchCV | Power BI | Jupyter Notebook

**Key Learning Outcomes**

This project strengthened my practical understanding of machine learning workflows, predictive analytics, model evaluation, feature importance, class imbalance, and data visualization. It also demonstrated how analytical findings can be transformed into meaningful reports to support data-driven decision-making.

**Project Note:** This is an academic machine learning project, not a clinically validated diagnostic tool. Predictions are for research and demonstration purposes only.
