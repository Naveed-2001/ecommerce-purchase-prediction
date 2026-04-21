# E-Commerce Purchase Prediction (Python, Scikit-learn)

An end-to-end machine learning project predicting whether an online shopper will complete a purchase, based on browsing behaviour across 12,330 sessions.

## Key Results
- Final model: Extra Trees Classifier with 93.9% accuracy
- Compared 4 classification models: Logistic Regression, Decision Tree, Random Forest, Extra Trees
- Top purchase predictor: PageValues (35.1% feature importance)
- Class imbalance handled using SMOTE oversampling
- Precision: 94% | Recall: 94% | F1-Score: 94%

## Tech Stack
- Python (Pandas, NumPy, Scikit-learn, Imbalanced-learn)
- Matplotlib, Seaborn
- Jupyter Notebook
- Git and GitHub

## Project Structure
- data/ -- Raw dataset (UCI Online Shoppers Intention)
- notebooks/ecommerce_prediction.ipynb -- Full analysis and modelling notebook
- outputs/ -- Charts and key results

## Charts Generated
1. Purchase vs No Purchase Distribution
2. PageValues by Purchase Outcome
3. Bounce Rates vs Exit Rates
4. Feature Importance Chart
5. Confusion Matrix

## Key Findings
- PageValues is the strongest predictor of purchase conversion (35.1% importance)
- Extra Trees outperformed Random Forest by 1.7 percentage points
- SMOTE improved minority class recall from ~60% to 96%

## How to Run
1. Clone the repo
2. Create virtual environment: python -m venv venv
3. Activate: venv\Scripts\activate
4. Install dependencies: pip install -r requirements.txt
5. Open: jupyter notebook notebooks/ecommerce_prediction.ipynb