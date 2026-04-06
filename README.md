# Bachelor-thesis
08, 2023, Time-to-event analysis for hospital stays caused by respiratory infections with Prof. Frank Klawonn at Helmholtz-Zentrum für Infektionsforschung.

1. Overview
   This project investigates the factors influencing hospital stay duration for patients with 5 different respiratory infections using survival analysis techniques. I applied Cox proportional hazards models and Restricted Mean Survival Time (RMST) to analyze time-to-event data and compare outcomes across different patient groups. Model validity was assessed using Schoenfeld residuals for the proportional hazards assumption, Martingale residuals for covariate diagnostics, and Cox-Snell residuals for overall model fit. The results indicate that the model assumptions are reasonably satisfied.

2. Skills Demonstrated
- Survival Analysis (Cox Regression, RMST)
- Statistical Modeling
- Hypothesis Testing
- Data Preprocessing for real-world medical data
- Python (pandas, lifelines, matplotlib)

3. Result
   The analysis shows that several clinical and demographic factors significantly influence hospital stay duration across different respiratory infections. 
   Cox regression results indicate that higher age, presence of nosocomial infections, bacterial infections, and pre-existing conditions (e.g., diabetes, cardiac problems, renal insufficiency) are consistently associated with longer hospital stays, reflected by reduced hazard ratios for discharge. Among these factors, nosocomial and bacterial infections showed the strongest effects. In contrast, increased LDH levels were associated with a higher probability of discharge in certain groups. Laboratory markers such as CRP, glucose, and leukocyte count were generally linked to prolonged hospitalization.
   The RMST analysis confirmed these findings by providing an interpretable measure of average hospital stay within a fixed time horizon. Patients with nosocomial or bacterial infections exhibited substantially longer mean hospital stays, with consistent trends observed between SARS-CoV-2 and Omicron groups.

5. Data
   The dataset used in this project contains sensitive medical information and cannot be shared publicly. And the data preprocessing steps were specifically designed for this dataset. However, a synthetic or sample dataset structure can be provided upon request.
 
