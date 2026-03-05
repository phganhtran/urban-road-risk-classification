## Project Overview
This project develops a machine learning model to identify high-risk road segments ("Red Zones") using urban infrastructure, demographic, and transport-related features. The goal is to support insurers and city planners in improving road safety through predictive analytics.

## Dataset
The dataset contains urban environment features such as:
- Road infrastructure (intersections, traffic lights)
- Liquor licence density
- Land use types
- Demographic characteristics
- Household vehicle ownership

The target variable classifies areas into:
- **Red Zone** – high road safety risk
- **Standard Zone** – normal road safety conditions

The dataset is imbalanced, with approximately **10.7% Red Zones** and **89.3% Standard Zones**.

## Methods
The analysis followed a typical machine learning workflow:

1. **Exploratory Data Analysis (EDA)** to understand distribution patterns and key risk factors.
2. **Data preprocessing**
   - Dummy encoding of categorical variables
   - Feature standardisation
   - Stratified train-test split
3. **Model development**
   - Decision Tree
   - Logistic Regression
4. **Model evaluation** using accuracy, recall, precision, and F1-score.

## Model Performance

| Model | Accuracy | Recall (Red Zone) | F1 Score |
|------|------|------|------|
| Decision Tree | 91% | 0.54 | 0.56 |
| Logistic Regression | 91% | 0.74 | 0.63 |

Logistic Regression performed better at detecting high-risk zones, which is important for risk-sensitive applications such as insurance pricing and safety interventions.

## Business Impact
The predictive model enables insurers and city planners to:

- Identify high-risk road environments
- Design targeted road safety interventions
- Support risk-based insurance pricing
- Improve driver safety awareness through location-based alerts

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Google Collab
