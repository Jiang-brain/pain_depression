# pain_depression
The association between pain conditions and incident depression

A series of Cox proportional hazards regression models were implemented to estimate the association of pain conditions across eight body sites and pain status with the risk of depression incidence, using the follow-up time as the underlying timescale. The analyses used PF individuals as the reference group and adjusted for 13 covariates including age, sex, race, material deprivation, educational attainment, household income, smoking status, alcohol intake frequency, sedentary behaviour, BMI category, and history of cancer, vascular or heart problems, and diabetes.

Results were reported as hazard ratios (HR) and their 95% confidence intervals (CI). The potential non-linearity was formally examined by introducing a restricted cubic spline into the Cox models. All analyses were performed using a 5-year landmark analysis to minimize a possible reverse causality by excluding participants experiencing events at baseline or within the first 5-year follow-up period. The proportional hazard assumption was checked using Schoenfeld residuals and no violation was found. We examined the modifying effect of all covariates on the association by including a multiplicative interaction term. Then, stratified analyses were performed by covariates showing significant interaction effects.


Separate linear-mixed effect models were utilized to investigate how the composite pain scores relate to each of the 14 inflammatory markers. Within each model, the composite pain scores and covariates were fitted as an independent fixed effect, the UK Biobank assessment center as a random effect, and the inflammatory markers as the dependent variable. The standardized β coefficients were extracted and converted to Cohen’s d according to previous studies. Linear and nonlinear associations between these inflammatory markers and depression incidence were also investigated using Cox proportional hazards models within the same analytical framework.

We further used the ‘mediation’ package in R to examine whether the effect of the composite pain scores on depression incidence was mediated by inflammatory markers. We established a standard three-variable path model, where linear regression was used for pain-inflammatory associations and survival regression was used for pain-depression and inflammation-depression associations. The significance of mediating effects was determined based on 5000 bootstrap iterations.


