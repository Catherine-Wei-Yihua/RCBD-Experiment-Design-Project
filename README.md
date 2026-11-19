# Popcorn Preference Experiment

## Overview
This project investigates whether different salt concentrations affect popcorn preference using a **Randomized Complete Block Design (RCBD)**. The experiment evaluates how salt levels influence taste ratings while controlling for individual differences among participants.

## Experimental Design
- **Participants:** 5
- **Treatments:** 4 salt levels (0.00g, 0.15g, 0.30g, 0.45g per 10g popcorn)
- **Observations:** 20
- **Design:** Randomized, blinded taste testing with participants as blocks
- **Response Variable:** Preference score (1–9)

## Statistical Methods
Analysis was conducted in **R**, including:
- Exploratory Data Analysis (EDA) and visualization
- RCBD Analysis of Variance (ANOVA)
- Tukey HSD pairwise comparisons
- Residual diagnostics and Shapiro-Wilk normality test
- Friedman nonparametric sensitivity test

## Key Findings
- Salt concentration significantly affected popcorn preference (**ANOVA p = 0.0004**).
- The **0.30g** treatment achieved the highest average preference score (**7.4/9**).
- All salted treatments were rated significantly higher than unsalted popcorn.
- Differences among the three salted treatments were not statistically significant.

## Conclusion
The experiment provides evidence that adding salt improves popcorn preference. However, the small sample size of five participants limits the generalizability of the findings.

## Project Files
- **Popcorn_Preference_Experiment_Report.pdf** — Full experimental design, statistical analysis, visualizations, conclusions, and R code in Appendix A.# RCBD-Experiment-Design-Project
