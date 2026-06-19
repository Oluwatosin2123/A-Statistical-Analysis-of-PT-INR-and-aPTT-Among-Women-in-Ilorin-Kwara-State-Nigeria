# A-Statistical-Analysis-of-PT-INR-and-aPTT-Among-Women-in-Ilorin-Kwara-State-Nigeria
Effects of Selected Oral Contraceptives on Coagulation Parameters

---

## Project Overview

This project presents a quantitative statistical analysis examining whether oral contraceptive (OC) use affects key blood coagulation parameters—Prothrombin Time (PT), International Normalized Ratio (INR), and Activated Partial Thromboplastin Time (aPTT)—among women in Ilorin, Kwara State, Nigeria.

The study analyzed data from 80 participants consisting of 35 oral contraceptive users and 45 non-users, using descriptive statistics, One-Way ANOVA, and multivariate regression techniques.

The analysis was conducted to evaluate:

1. The relationship between sociodemographic/lifestyle factors and coagulation parameters.
2. Differences in coagulation parameters between OC users and non-users.
3. The effect of duration of oral contraceptive use on coagulation parameters.

---

## Dataset Summary

Detail| Value
Total Participants| 80 (35 OC users, 45 non-users)
Oral Contraceptive Types| Levofem (COC) – 74.3%; Postinor (POP/E) – 25.7%
Variables Collected| Sociodemographic data, contraceptive history, lifestyle factors, PT, INR, aPTT
Duration Categories| 1–2 months, 3–6 months, stopped < 6 months, > 1 year

---

## Methodology

Research Objective| Statistical Tool| Purpose
Sociodemographic & lifestyle association| One-Way ANOVA| Determine whether background characteristics influence coagulation parameters
OC users vs. non-users comparison| One-Way ANOVA| Compare mean PT, INR, and aPTT between groups
Duration of OC use effect| One-Way ANOVA| Assess differences across duration-of-use categories
Confounder assessment| Multivariate Regression| Evaluate whether age explains observed differences

## Statistical Assumptions

- Significance level: α = 0.05
- Parametric assumptions verified using normal probability plots
- Null and alternative hypotheses tested for each objective


![image alt]
---

## Key Findings

1. Sociodemographic & Lifestyle Factors

Findings:

- No statistically significant relationship was observed between coagulation parameters and:
  
  - Age
  - Marital status
  - Educational level
  - Occupation
  - Smoking status
  - Alcohol consumption
  - Exercise frequency

- All tests returned p > 0.05.

Significant Factor Identified

The brand of oral contraceptive used was significantly associated with coagulation outcomes.

- Levofem users demonstrated lower PT and INR values compared to Postinor users.
- This difference was statistically significant (p < 0.05).
- Findings are consistent with the stronger estrogenic effect of combined oral contraceptives.

---

2. Oral Contraceptive Users vs. Non-Users

Parameter| OC Users (Mean ± SD)| Non-Users (Mean ± SD)| F-value| p-value| Interpretation
PT (sec)| 8.80 ± 2.82| 11.78 ± 1.73| 1264.96| < 0.001| Significant
INR| 0.68 ± 0.23| 0.97 ± 0.15| 1264.96| < 0.001| Significant
aPTT (sec)| 25.57 ± 4.57| 25.82 ± 3.68| 585.80| < 0.001| Statistically significant but clinically negligible

### Interpretation

Oral contraceptive users exhibited:

- Shorter Prothrombin Time (PT)
- Lower International Normalized Ratio (INR)

These findings indicate a faster clotting tendency, suggesting activation of the extrinsic and common coagulation pathways and a potential hypercoagulable state.

Although aPTT showed statistical significance, the observed difference was too small to have meaningful clinical implications, suggesting minimal influence on the intrinsic coagulation pathway.

---

3. Effect of Duration of Oral Contraceptive Use

Duration Category| n| Mean PT ± SD| Mean INR ± SD| Mean aPTT ± SD
1–2 months| 12| 9.42 ± 3.04| 0.73 ± 0.24| 26.08 ± 5.12
3–6 months| 15| 8.53 ± 2.61| 0.66 ± 0.20| 25.40 ± 4.27
Stopped < 6 months| 7| 8.71 ± 2.78| 0.67 ± 0.22| 25.57 ± 4.32
> 1 year| 1| 8.00| 0.62| 24.90

### ANOVA Results

Parameter| F-value| p-value| Result
PT| 1.21| 0.32| Not Significant
INR| 1.09| 0.37| Not Significant
aPTT| 0.87| 0.47| Not Significant

 Interpretation

No statistically significant differences were observed across duration groups.

However:

- All duration categories consistently demonstrated lower PT and INR values than non-users.
- This suggests coagulation changes may occur early after initiating oral contraceptives.
- The small sample size in the >1 year group (n = 1) limits long-term conclusions.

---

4. Age as a Potential Confounding Variable

Multivariate Regression Results

Parameter| Group| R²| Significance F| Conclusion
PT| OC Users| 0.013| 0.515| Age not significant
PT| Non-Users| 0.025| 0.295| Age not significant
INR| OC Users| 0.005| 0.694| Age not significant
INR| Non-Users| 0.037| 0.205| Age not significant
aPTT| OC Users| 0.036| 0.280| Age not significant
aPTT| Non-Users| 0.000| 0.908| Age not significant

Interpretation

Age was not a significant predictor of:

- PT
- INR
- aPTT

Across both participant groups:

- All p-values > 0.05
- All R² values < 0.04

This indicates that age did not confound the relationship between oral contraceptive use and coagulation outcomes.

---

## Conclusions

The analysis revealed that:

- Oral contraceptive use is associated with a statistically significant pro-coagulant shift.
- Users exhibited significantly lower PT and INR values than non-users (p < 0.001).
- Combined oral contraceptives (Levofem) produced stronger coagulation effects than Postinor.
- The intrinsic coagulation pathway (aPTT) showed minimal practical change.
- Sociodemographic and lifestyle factors were not significant predictors of coagulation outcomes.
- Duration of use did not significantly alter coagulation parameters within the study sample.
- Age was statistically ruled out as a confounding variable.

---

### Tools & Statistical Techniques

Descriptive Statistics

- Mean
- Standard Deviation
- Median
- Minimum & Maximum
- 95% Confidence Intervals

Inferential Statistics

- One-Way ANOVA
- F-Ratio Analysis
- Hypothesis Testing
- p-value Interpretation

Predictive Analysis

- Multivariate Regression
- R² and Adjusted R²
- Regression F-test

Assumption Testing

- Normal Probability Plots
- Parametric Test Validation

---

### Research Context

This repository showcases the statistical analysis component of a Bachelor of Medical Laboratory Science (B.MLS) research project conducted at the University of Ilorin.

The project demonstrates:

- Data analysis workflow
- Statistical reasoning
- Hypothesis testing
- Research reporting
- Healthcare data analytics

and serves as a portfolio project highlighting analytical and research-oriented data skills.

---

## Author

Oluwatosin Moses

Data Analyst | Research Analytics Enthusiast

Skills Demonstrated

- Statistical Analysis
- Data Interpretation
- Hypothesis Testing
- ANOVA
- Regression Analysis
- Research Reporting
- Healthcare Data Analytics
