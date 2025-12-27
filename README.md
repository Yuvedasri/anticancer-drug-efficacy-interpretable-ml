# Predicting Anticancer Drug Efficacy using Interpretable Machine Learning

## Overview
Cancer drugs often show varied effectiveness across different tumors.
This project predicts anticancer drug efficacy by analyzing tumor
characteristics using interpretable machine learning models.

Rather than focusing only on prediction accuracy, the project emphasizes
understanding which tumor features influence treatment response.

---

## Dataset Description
A synthetic dataset representing 500 tumor samples was generated.
Each tumor is described by:
- Immune activity level
- Hypoxia (low oxygen) level
- Growth rate
- Stromal density
- Angiogenesis (blood vessel support)

The target variable indicates whether the drug is effective (1) or not (0).

---

## Methodology
- Feature standardization using StandardScaler
- Logistic Regression for interpretable prediction
- Feature importance analysis using model coefficients
- Visualization of feature influence

---

## Results & Interpretation
The model identifies immune activity and angiogenesis as strong positive
contributors to drug efficacy, while hypoxia and high growth rates
negatively impact treatment response.

These results align with biological intuition and demonstrate the value
of interpretable machine learning in biomedical decision support.

---

## Project Structure
Anticancer-Drug-Efficacy-Prediction/
├── data/
├── notebooks/
├── results/
├── README.md


---

## How to Run
1. Install dependencies using `pip install -r requirements.txt`
2. Open the notebook in the `notebooks/` folder
3. Run all cells sequentially

---

## Tools & Technologies
Python, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## Author
Yuveda
