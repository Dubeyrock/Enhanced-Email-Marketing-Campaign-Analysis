# Enhanced-Email-Marketing-Campaign-Analysis
This project optimizes an email marketing campaign for an e-commerce site, predicting click-through rates using Random Forest and XGBoost models. It includes advanced features like hyperparameter tuning, SHAP interpretability, interactive visualizations, A/B testing simulation, and decile analysis.


![pic_1](https://github.com/user-attachments/assets/53065181-d986-4f91-a5ad-b33f6ef26ef4)


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



## demo Graph 

![image](https://github.com/user-attachments/assets/62d3ac4f-aee2-44e3-a9bc-c7664c8aedc0)


![image](https://github.com/user-attachments/assets/53952871-1002-4002-9347-8df31b2bded4)


![image](https://github.com/user-attachments/assets/4eb212c4-1260-4d45-86ef-929caf834658)


![newplot](https://github.com/user-attachments/assets/167622af-22fd-4f7a-b473-7a9544c9d08d)

![image](https://github.com/user-attachments/assets/a80554c0-7c43-4089-90dd-d23fa139d98f)

![image](https://github.com/user-attachments/assets/8ee0d5c4-0eed-47b7-b218-14008440d81a)

![image](https://github.com/user-attachments/assets/4846d800-1d53-478a-ab27-28065db903e9)

![image](https://github.com/user-attachments/assets/c8da3f97-3b86-4dc9-b0eb-f7f37da50eb8)


## Author
[Shivam Dubey]
