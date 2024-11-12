
# Credit Risk Prediction with Machine Learning
## A Portfolio Project for Demonstration
This project uses machine learning to predict credit risk based on the German Credit dataset. The objective is to classify applicants as "Good" or "Bad" credit risks and provide interpretable insights into the factors influencing these predictions. This project incorporates model training, evaluation, and interpretability techniques, making it suitable for responsible decision-making in finance.

## Project Overview

### Key Objectives
1. Develop a machine learning model to classify credit risks.
2. Handle class imbalance to improve performance on minority class ("Bad" credit risks).
3. Use interpretability tools (SHAP and LIME) to understand the model’s predictions, providing transparency in credit risk assessment.

### Dataset
- **Name**: Statlog (German Credit Data)
- **Source**: UCI Machine Learning Repository
- **Description**: The dataset contains information on applicants with attributes like checking account status, credit history, loan duration, and more. The target variable indicates whether each applicant is a "Good" or "Bad" credit risk.

## Project Structure

- `data`: https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)
- `notebooks`: Jupyter notebooks for data exploration, model training, and evaluation.
- `README.md`: Project documentation.
- `requirements.txt`: Python dependencies.

## Installation

1. Clone the repository:
2. Navigate to the project directory:
3. Install dependencies:

## Methodology
### 1. Data Preprocessing and Exploration
   - Load and explore the dataset to understand feature distributions and address class imbalance.
   - Preprocess the data by encoding categorical features, scaling numerical features, and using SMOTE for oversampling the minority class.

### 2. Model Training
   - Train multiple machine learning models (Random Forest, Gradient Boosting, XGBoost, LightGBM) to classify credit risk.
   - Use `GridSearchCV` for hyperparameter tuning to improve model performance.

### 3. Model Evaluation and Comparison
   - Evaluate models using metrics like ROC AUC, Precision-Recall AUC, and F1-scores.
   - Visualize and compare model performance through ROC and Precision-Recall curves.

### 4. Interpretability with SHAP and LIME
   - Use **SHAP** to understand global and local feature importance for the best model.
   - Use **LIME** to interpret individual predictions, providing detailed explanations for why certain applicants are classified as "Good" or "Bad."

## Results
- **Best Model**: The **Random Forest** model achieved the highest ROC AUC (0.80) and demonstrated a good balance of precision and recall.
- **Key Features**: Checking account status, credit history, savings account level, and loan duration were the most influential features in predicting credit risk.
- **Interpretability**: SHAP and LIME visualizations provided transparency, showing how specific features contribute to individual predictions.

## Conclusion
This project successfully developed an interpretable model for predicting credit risk, with a focus on handling class imbalance and providing explanations for predictions. This approach can support financial institutions in making data-driven, transparent lending decisions.

## Requirements
See `requirements.txt` for a complete list of dependencies.

## License
This project is licensed under the MIT License.

## Contact
For any questions or further information, please contact me.

