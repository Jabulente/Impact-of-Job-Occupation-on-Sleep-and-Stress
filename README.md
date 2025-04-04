# **Occupational Impact on Sleep Disorders and Stress Levels**

## **Project Overview**

This project explores the relationship between **job occupation** and its influence on two major health indicators: **sleep disorders** (including Insomnia and Sleep Apnea) and **stress levels**. By analyzing real-world data using statistical and machine learning techniques, this project aims to uncover patterns and associations that can inform health-focused workplace interventions and policy-making.

---

## **Objectives**

- Identify which occupations are more strongly associated with sleep disorders.
- Compare each occupation against a baseline (Accountant) using **logistic regression and odds ratios**.
- Explore how job occupation affects **stress levels** using **linear regression**, interpreting coefficients relative to a baseline job.
- Use **Chi-Square analysis** and **standardized residuals** to determine the strength and significance of associations.
- Demonstrate the real-world implications of findings for improving workplace wellness and mental health.

---

## **Techniques & Tools Used**

- **Python (Pandas, Statsmodels, Scikit-learn, Seaborn, Matplotlib)**
- **Chi-Square Test of Independence**
- **Standardized Residuals**
- **Cramér’s V & Phi Coefficient**
- **Logistic Regression**
- **Linear Regression**
- **Interaction Effects**

---

## **Key Insights**

- **Nurses** and **Salespeople** showed significantly higher-than-expected rates of **Sleep Apnea** and **Insomnia**.
- **Teachers** and **Engineers** appeared to have lower-than-expected occurrences of sleep disorders.
- Logistic regression revealed that compared to **Accountants** (baseline), some jobs had **2–3x higher odds** of developing specific sleep issues.
- Linear regression showed that stress levels varied significantly between occupations, with interaction effects suggesting compounding factors.
- **Standardized residuals** provided precise indications of where observed outcomes deviated strongly from what was expected, highlighting critical areas of concern.
- **Cramér’s V** helped quantify the strength of the association between occupation and sleep disorder status.

---

## **Real-World Implications**

These findings have actionable implications for **human resource departments**, **health practitioners**, and **policy-makers**. Organizations can use this information to:

- Design **targeted wellness programs** for high-risk occupations.
- Implement stress management strategies where needed.
- Monitor sleep health as a component of workplace productivity and employee retention.

---

## **How to Use This Repository**

1. Clone the repository:  
   `git clone https://github.com/your-username/job-sleep-stress-analysis.git`

2. Install required libraries:  
   ```
   pip install -r requirements.txt
   ```

3. Explore the analysis notebooks:
   - `01_data_cleaning.ipynb`
   - `02_chi_square_analysis.ipynb`
   - `03_logistic_regression.ipynb`
   - `04_linear_regression_stress.ipynb`
   - `05_interaction_effects.ipynb`
   - `06_visualizations.ipynb`

4. View results summary in the attached PDF report.

---

## **Project Structure**

```
job-sleep-stress-analysis/
│
├── data/
│   └── sleep_stress_data.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_chi_square_analysis.ipynb
│   ├── 03_logistic_regression.ipynb
│   ├── 04_linear_regression_stress.ipynb
│   ├── 05_interaction_effects.ipynb
│   └── 06_visualizations.ipynb
│
├── results/
│   └── summary_report.pdf
│
├── README.md
└── requirements.txt
```

---

## **Contributing**

Feel free to fork this repository and submit a pull request if you want to:
- Extend the analysis to include more health indicators.
- Add new visualizations or data sources.
- Improve statistical modeling.

---

## **Contact**

**Author:** Jabulente  
**LinkedIn:** [Your LinkedIn Profile]  
**Email:** [Jabulente@hotmail.com]

---

## **License**

This project is open-source and available under the [MIT License](LICENSE).
