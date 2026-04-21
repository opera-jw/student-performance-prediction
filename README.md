# Regression Analysis Report

## Introduction
This project analyzes how different factors influence student performance using multiple linear regression. The study considers variables such as study time, attendance, sleep duration, previous academic performance, and participation in tutoring sessions. The aim is to understand how these factors contribute to performance and identify the most impactful predictors.

## Research Question
How do Hours Studied, Attendance, Sleep Hours, Previous Scores, and Tutoring Sessions affect student performance?

## Analysis

### Regression Statistics

| Metric                | Value   |
|----------------------|--------|
| Multiple R           | 0.85   |
| R Square             | 0.71   |
| Adjusted R Square    | 0.71   |
| Standard Error       | 4.67   |
| Observations         | 6607   |

### Model Equation


### ANOVA Table

| Source      | df   | SS           | MS           | F           | Significance F |
|-------------|------|-------------|-------------|-------------|----------------|
| Regression  | 5    | 360568.5054 | 72113.70108 | 3306.200353 | 0              |
| Residual    | 6601 | 143978.7339 | 21.81165488 |             |                |
| Total       | 6606 | 504547.2393 |             |             |                |

### Coefficients Summary

| Variable             | Coefficient | Std Error | t Stat      | P-value       | Lower 95%      | Upper 95%      |
|---------------------|------------|-----------|-------------|---------------|----------------|----------------|
| Intercept           | 0.30       | 0.628819  | 0.474539    | 0.635131      | -0.934290      | 1.531088       |
| Hours_Studied       | 0.61       | 0.009599  | 63.108686   | 0             | 0.586977       | 0.624612       |
| Attendance          | 0.21       | 0.004977  | 41.758054   | 0             | 0.198091       | 0.217605       |
| Sleep_Hours         | -0.10      | 0.044566  | -2.332501   | 0.019704      | -0.191312      | -0.016586      |
| Previous_Scores     | 0.40       | 0.003977  | 99.583998   | 0             | 0.388206       | 0.403797       |
| Tutoring_Sessions   | 1.50       | 0.047252  | 31.790837   | 1.6977E-206   | 1.409552       | 1.594811       |

## Findings

- The model explains 71% of the variation in student performance (R Square = 0.71), indicating a strong model fit.
- Hours Studied has a strong positive effect, meaning increased study time leads to better performance.
- Attendance positively influences results, showing that consistent participation improves outcomes.
- Previous Scores strongly predict performance, indicating that past academic success influences future results.
- Tutoring Sessions have the highest impact among all variables, suggesting extra academic support significantly improves performance.
- Sleep Hours has a small but statistically significant negative effect.
- The overall model is statistically significant (Significance F = 0), meaning all variables together have a meaningful impact on performance.

## Conclusion

The regression analysis shows that student performance is largely influenced by effort-related factors such as studying, attending classes, and engaging in tutoring. Previous academic performance also plays a key role. Although sleep shows a slight negative relationship, its effect is relatively small. These insights can help students and educators focus on strategies that improve academic success.
