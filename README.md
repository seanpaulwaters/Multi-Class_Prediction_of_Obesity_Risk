# Obesity Risk Prediction - Kaggle Competition

## Overview
This project is my submission for the 2024 Kaggle Playground Series focused on predicting obesity risk in individuals. The dataset was synthetically generated and the competition evaluated submissions based on accuracy.

Result Summary:
> My models achieved top-tier scores, with the best model reaching a private score of 0.90968. Although slightly below the winning score of 0.91157, they demonstrate strong predictive power and potential for further improvement with additional tuning and experimentation.

Citation:
> Walter Reade, Ashley Chow. (2024). Multi-Class Prediction of Obesity Risk. Kaggle. [Kaggle Competition Link](https://kaggle.com/competitions/playground-series-s4e2)

## Repository Contents
- `obesity_prediction.ipynb`: Jupyter Notebook containing the analysis and modeling.
- `train.csv`: The training dataset used for model building (not included in the repo due to size constraints, available on Kaggle).
- `test.csv`: The testing dataset used for predictions (not included in the repo due to size constraints, available on Kaggle).
- `submission_xgb.csv`: Submission file for the XGBoost model predictions.
- `submission_lgb.csv`: Submission file for the LightGBM model predictions.
- `requirements.txt`: List of libraries required to run the notebook.

## Models
- XGBoost Classifier
- LightGBM Classifier

## Scores
- XGBoost:
  - Public Score: 0.90634
  - Private Score: 0.90968
- LightGBM:
  - Public Score: 0.90281
  - Private Score: 0.90823

## Usage

jupyter notebook obesity_prediction.ipynb


## License

MIT License

## Installation
Instructions on how to set up the project environment:

```bash
git clone https://github.com/your-github-username/obesity-risk-prediction-kaggle.git
cd obesity-risk-prediction-kaggle
pip install -r requirements.txt

