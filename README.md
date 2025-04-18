# Enhanced-Email-Marketing-Campaign-Analysis
This project optimizes an email marketing campaign for an e-commerce site, predicting click-through rates using Random Forest and XGBoost models. It includes advanced features like hyperparameter tuning, SHAP interpretability, interactive visualizations, A/B testing simulation, and decile analysis.

## Project Structure
- `Enhanced_Email_Campaign_Analysis.ipynb`: Main Jupyter notebook with analysis.
- `email_table.csv`: Email metadata.
- `email_opened_table.csv`: Emails opened.
- `link_clicked_table.csv`: Emails with link clicks.
- `*.png` / `*.html`: Visualizations (e.g., SHAP plots, interactive lift chart).

## Features
1. **Data Analysis**: Calculates open and click-through rates.
2. **Modeling**: Uses tuned Random Forest and XGBoost models with GridSearchCV.
3. **Interpretability**: SHAP plots explain feature impacts.
4. **Visualizations**: Interactive lift chart with Plotly, decile analysis.
5. **A/B Testing**: Simulates personalized vs. generic email performance.
6. **Insights**: Segment analysis by country, hour, email version, and purchase history.

## How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/drive/1blXsY0GRF4GG7kMBHT8Nk_HQ2Q1jvWGZ?usp=sharing).
2. Upload the three CSV files.
3. Install dependencies: `!pip install xgboost shap plotly`.
4. Run all cells to generate results and visualizations.

## Requirements
- Python 3
- Libraries: pandas, numpy, scikit-learn, xgboost, shap, plotly, matplotlib, seaborn

## Key Findings
- XGBoost outperforms Random Forest in ROC AUC and AUPRC.
- User past purchases and send hour are top predictors.
- Personalized emails may improve click-through rates (A/B test results).
- Targeting top deciles captures most clicks efficiently.

## Author
[Shivam Dubey]
