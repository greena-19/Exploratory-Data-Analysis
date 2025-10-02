# Exploratory Data Analysis (EDA) Report

## Introduction

This project performs Exploratory Data Analysis (EDA) on a dataset to
uncover patterns, relationships, and potential predictors of survival.
The analysis includes handling missing values, univariate exploration,
and bivariate relationships.

## Missing Values

-   Missing values were identified and handled.
-   Age values were imputed using the median.
-   Categorical missing values (if any) were filled or excluded.

## Univariate Analysis

-   **Age:** Broad distribution; missing values imputed with median.
-   **Fare:** Positively skewed with outliers.
-   **Class (Pclass):** Majority of passengers in 3rd class.
-   **Sex:** Slightly more males than females.
-   **Family (SibSp, Parch):** Most passengers traveled alone or with
    small families.

## Bivariate Analysis

-   **Sex vs Survival:** Females show higher survival rates.
-   **Class vs Survival:** Higher class = better survival chances.
-   **Fare vs Survival:** Higher fares linked to higher survival rates.
-   **Age vs Survival:** Subtle effect; children/elderly differ from
    adults.
-   **Family Size:** Small families had slightly better outcomes.

## Observations

-   Gender and Class are the strongest survival indicators.
-   Fare has weaker predictive power.
-   Age has limited role except at extremes.
-   Outliers in Fare expected due to premium ticket holders.

## Conclusion

-   Women and children in higher classes had higher survival chances.
-   Economic status (ticket class) was a major factor.
-   Age and family structure added contextual understanding.
-   Dataset is now cleaned and ready for predictive modeling.

------------------------------------------------------------------------

### Files Generated

-   **EDA_Report.pdf**: Full EDA report in PDF format.
-   **README.md**: Summary and documentation for the project.
