# Insurance Data Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Key objectives](#key-objectives)
- [Dataset](#dataset)
- [Models Evaluated](#models-evaluated)
- [Installation & Setup](#installation--setup)
- [Usage](#usage)
- [Key findings](#Key-Findings)
- [Conclusion](#Conclusion)
---

## Project Overview
This project focuses on analyzing medical insurance data to understand the factors that influence healthcare premium costs. Using exploratory data analysis (EDA) and predictive modeling, the goal is to uncover patterns related to age, BMI, smoking habits, region, and other demographic factors, and to build models that can predict insurance charges. The insights derived from this analysis can help insurance companies make informed business decisions and optimize premium pricing strategies.

---

## Key objectives:
- Perform exploratory data analysis (EDA) on medical insurance data to uncover meaningful patterns.
- Understand how demographic and lifestyle factors affect insurance premium charges
- Analyze the impact of smoking status on healthcare costs across different age groups
- Examine relationships between age, BMI, number of children, region, and insurance charges
- Identify the most influential features contributing to higher medical insurance premiums
- Build and evaluate predictive models to estimate insurance costs
- Support data-driven decision-making for insurance pricing and risk assessment
- Compare performance of CNN and transfer learning models.
- Use data augmentation to improve model accuracy and generalization.

---

## Dataset

**Source:** Insurance Dataset (insurance.csv)
**Domain:** Healthcare
**Records:** Policyholder-level data

---

## Models Evaluated
## The following models were evaluated to predict medical insurance costs:
- Linear Regression
- Multiple Linear Regression
-Regularized Regression Models
- Performance comparison based on regression metrics such as: R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE)
  
---

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Shabeha31/medical-insurance-cost-analysis-python.git
   cd medical-insurance-cost-analysis-python
2. Install dependencies:
   pip install -r requirements.txt
3. Ensure you have Jupyter Notebook or a Python IDE installed.

---

## Usage
1. Open the Jupyter Notebook:
   jupyter notebook Brain_Tumor_Detection.ipynb
2. Follow the notebook cells to:
   - Load the dataset and perform exploratory data analysis (EDA)
   - Visualize relationships between features and insurance charges
   - Train regression models to predict insurance costs
   - Compare model performance and interpret results

---

## Key Findings
- Age shows a strong positive correlation with insurance charges
- Insurance charges increase sharply with age for smokers compared to non-smokers
- Regional differences exist but have less impact than lifestyle factors
- BMI and number of children have limited standalone influence on premium cost
- Combining demographic and lifestyle features improves prediction accuracy

---

## Conclusion
This project highlights how lifestyle choices, particularly smoking, significantly affect medical insurance costs. Through EDA and predictive modeling, the analysis demonstrates that insurers can better estimate premiums by incorporating behavioral and demographic factors. The findings emphasize the importance of risk-based pricing and provide actionable insights for healthcare insurance providers to improve policy design and cost forecasting.

