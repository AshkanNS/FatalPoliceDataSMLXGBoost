
# Supervised Machine Learning with XGBoost

This project involves using **XGBoost** to analyze and classify data on fatal police shootings. The model has been optimized and evaluated for high accuracy and is designed to provide insights for data-driven decisions.

## Summary

The model achieved 100% accuracy, with the most important features being:
- Age
- Race
- Body Camera usage

### Key Features:
- **Optimization**: Hyperparameters were optimized using GridSearchCV.
- **Model Evaluation**: Accuracy, precision, recall, and F1-score metrics were used to evaluate performance.
- **Feature Importance**: The model shows that age, race, and body camera usage had the greatest influence on predictions.

### Improvements:
While the model shows high accuracy, further cross-validation and feature selection could improve robustness and generalization to new data.

## Business Value:
The model provides actionable insights that allow:
- Better **predictive insights** into future incidents.
- More **strategic resource allocation** by identifying key factors in fatal incidents.
- **Data-driven decision making** that saves time and enhances accuracy in analysis.

The model can evolve with new data, making it a long-term asset for continuous improvement.

## Instructions for Usage:
1. Run the `model.ipynb` notebook to train, evaluate, and optimize the XGBoost model.
2. Use cross-validation and further hyperparameter tuning for improvements.
3. Feature importance can be visualized to gain insights into the factors affecting the outcomes.
4. Ensure the dataset is preprocessed properly before feeding into the model.
