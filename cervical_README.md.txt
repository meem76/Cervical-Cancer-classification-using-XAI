# Interpretable Boosted Models for Cervical Cancer Risk: SHAP Selection and Bayesian Tuning

## Overview  
Cervical cancer remains a significant global health challenge. This project presents an explainable AI pipeline designed to improve the accuracy and interpretability of cervical cancer risk prediction. We combine gradient-boosted tree models (XGBoost, LightGBM, CatBoost) with SHAP-based feature selection and Bayesian hyperparameter tuning to prioritize clinically meaningful predictors. The approach balances high accuracy with transparency, supporting clinical trust and practical deployment.

## Key Features  
- Use of advanced gradient boosted models for risk classification  
- SHAP values to rank and select the most important predictors, reducing features to a compact subset  
- Bayesian optimization for efficient hyperparameter tuning  
- Handling of imbalanced classes with SMOTE and missing data imputation using KNN-Imputer  
- Model validation through 10-fold cross-validation and thorough evaluation  
- Transparent explanations at the global and patient-specific levels  

## Results  
- Achieved accuracies of 97.50%, 97.82%, and 98.13% using XGBoost, LightGBM, and CatBoost respectively  
- Comparable performance with both the full 34-feature set and a reduced top-5 feature subset  
- Provides a practical and interpretable cervical cancer screening approach for resource-limited healthcare settings  

## Getting Started  

### Prerequisites  
- Python 3.x  
- Libraries: scikit-learn, xgboost, lightgbm, catboost, shap, bayesian-optimization, imblearn, pandas, matplotlib  

### Installation  
git clone https://github.com/yourusername/cervical-cancer-boosted-models.git
cd cervical-cancer-boosted-models
pip install -r requirements.txt


### Usage  
Run the scripts to preprocess data, train models, perform SHAP analysis, and evaluate results.  

python preprocess.py
python train.py
python interpret.py


## Contribution  
Contributions and feedback are welcome. Please open issues or submit pull requests.

## License  
Specify your license here, e.g., MIT License.
