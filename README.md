# Predicting-the-Development-of-Obesity-Based-on-Lifestyle
Predicting the Development of Obesity Based on Lifestyle

This repository contains the project files for predicting obesity using demographic, health, and lifestyle data. The goal of this project is to identify key factors contributing to obesity and to build a machine learning model for early detection and intervention.

## Project Overview
Obesity is a major global health concern associated with chronic diseases such as diabetes, cardiovascular conditions, and hypertension. This project leverages machine learning to analyze correlations between key variables and predict obesity risks, enabling targeted public health interventions.

### Key Objectives
- Build predictive models for obesity using health and lifestyle data.
- Identify significant factors contributing to obesity.
- Provide actionable insights for public health policies and interventions.

## Project Structure
- **data/**: Contains the cleaned and processed dataset.
- **notebooks/**: Jupyter Notebooks with code for data preprocessing, analysis, and model building.
- **results/**: Outputs, including model evaluation metrics and visualizations.
- **README.md**: Overview of the project (this file).

## Methodology
1. **Data Preparation**:
   - Cleaned and addressed missing values.
   - Handled outliers using box plots for key predictors (e.g., Weight, Height).
   - Transformed categorical variables using binary transformations and one-hot encoding.
2. **Modeling**:
   - Selected Logistic Regression and Random Forest for predictive modeling.
   - Split data into training (80%) and testing (20%) sets.
   - Evaluated models using accuracy, precision, recall, F1-score, and ROC-AUC.

## Results
- **Random Forest Model**:
  - Accuracy: 96.2%
  - Precision: 97.0%
  - Recall: 98.6%
  - F1-Score: 97.8%
  - ROC-AUC: 90.4%
- **Logistic Regression Model**:
  - Accuracy: 84.6%
  - ROC-AUC: 52.9%

The Random Forest model significantly outperformed Logistic Regression in predictive performance.

## Key Insights
- Factors strongly correlated with obesity include:
  - Weight
  - Physical activity frequency
  - Family history of overweight
  - Fast-food consumption
- Promoting physical activity and healthy eating habits are critical recommendations to combat obesity.

## Ethical Considerations
- Ensure no stigmatization of individuals based on health or weight.
- Use data responsibly and ethically, avoiding unfair discrimination in insurance or employment.

## Future Work
- Conduct controlled experiments to explore causal relationships.
- Improve model robustness by expanding the dataset.
- Develop tools to integrate these findings into public health policies.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/obesity-prediction.git
