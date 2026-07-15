# Survival-Analysis-of-Treatment-Success-Rate-of-Drug-Resistant-Tuberculosis-Patients-in-East-Java

The purpose of this project was to analyze the factors influencing the treatment success rate of drug-resistant tuberculosis (DR-TB) patients in East Java using survival analysis. The following are the steps in the analysis :
1. Collected and analyzed secondary medical record data of 3,703 drug-resistant tuberculosis (DR-TB) patients in East Java, January 2022 to June 2025, from the Sistem Informasi Tuberkulosis (SITB).
   
3. Performed data preprocessing, including missing value, categorical variable encoding, data cleaning such as duplicates, inconsistencies, and outliers, survival time calculation, and event status determination for survival analysis.
   
5. Conducted exploratory and descriptive data analysis to summarize patient characteristics and visualize treatment outcomes using R.
   
7. Developed Kaplan–Meier survival curves and performed Log-Rank tests to compare treatment success rates across patient groups.
   
9. Evaluated the Proportional Hazards (PH) assumption using the Goodness-of-Fit method to identify variables that violated the Cox model assumptions.
    
11. Built and compared three survival models, Cox Proportional Hazards, Stratified Cox, and Extended Cox—to identify the most appropriate model for predicting treatment success.
    
13. Estimated hazard ratios, performed global and partial significance tests, and interpreted the impact of clinical and demographic variables on treatment outcomes.
    
15. Selected the Stratified Cox model as the best-performing model based on the lowest Akaike Information Criterion as follows AIC = 22,034.38, identifying healthcare facility type as the only significant factor influencing treatment success.
    
17. Delivered evidence based recommendations to the East Java Provincial Health Office to improve healthcare service quality, particularly in primary healthcare centers, to increase DR-TB treatment success rates.
