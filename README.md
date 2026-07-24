# Applied Statistical Inference in R

Applied statistical inference and causal analysis using R. This project demonstrates regression modeling, diagnostic testing, and modern causal inference techniques through two empirical case studies using real-world datasets from the wooldridge and causaldata R packages.

## Project Overview

This project was completed as part of a university Statistical Inference course and showcases practical applications of econometrics and statistical modeling in R.

The project is divided into two complementary analyses:

* Part I – Cross-Sectional Regression Analysis
    * Investigates factors associated with extramarital affairs using multiple regression techniques.
* Part II – Causal Inference
    * Estimates the impact of castle doctrine laws on homicide rates using Difference-in-Differences, fixed effects, and event study methods.

The objective is not only to estimate statistical models but also to evaluate model assumptions, perform robustness checks, and interpret results using modern econometric methods.


## Research Questions

Part I – Cross-Sectional Analysis

* How does marital satisfaction affect the number of extramarital affairs?
* Which demographic and socioeconomic variables are statistically significant predictors?
* Which regression model provides the best fit for count data?

Part II – Causal Inference

* Did the adoption of castle doctrine laws affect homicide rates?
* Can the policy impact be identified using Difference-in-Differences?
* Do the parallel trends assumption and event study support the causal interpretation?



## Methodology

#### Part I

* Exploratory Data Analysis (EDA)
* Descriptive Statistics
* Correlation Analysis
* Multiple Linear Regression (OLS)
* Variance Inflation Factor (VIF)
* Heteroskedasticity Testing
* Robust Standard Errors
* Cook’s Distance (Influential Observations)
* Log-Transformed Regression
* Negative Binomial Regression

#### Part II

* Difference-in-Differences (DiD)
* Two-Way Fixed Effects
* Clustered Standard Errors
* Event Study Analysis
* Dynamic Treatment Effect Estimation



## Datasets

#### Affairs Dataset

Source: wooldridge R package

Variables include:

* Marital satisfaction
* Number of extramarital affairs
* Age
* Years married
* Education
* Religiosity
* Occupation
* Children



#### Castle Doctrine Dataset

Source: causaldata R package

Variables include:

* Homicide rates
* Policy adoption
* State identifiers
* Year
* Treatment indicators



## Technologies Used

* R
* R Markdown
* tidyverse
* lmtest
* sandwich
* car
* broom
* MASS
* modelsummary
* stargazer
* corrplot
* kableExtra



## Repository Structure

```text
Applied-Statistical-Inference/
│
├── README.md
├── report/
│   ├── Statistical_Inference_Report.Rmd
│   └── Statistical_Inference_Report.pdf
│
├── figures/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── .gitignore
└── LICENSE
```

## Key Skills Demonstrated

* Statistical Inference
* Applied Econometrics
* Multiple Linear Regression
* Regression Diagnostics
* Difference-in-Differences
* Fixed Effects Models
* Event Study Analysis
* Causal Inference
* Robust Statistical Estimation
* Data Visualization
* Reproducible Research


## How to Reproduce

1. Clone the repository.
2. Install the required R packages listed in the report.
3. Open Statistical_Inference_Report.Rmd in RStudio.
4. Knit the document to generate the PDF report.


## Project Highlights

* Comprehensive regression diagnostics
* Robustness checks using heteroskedasticity-consistent standard errors
* Count-data modeling with Negative Binomial Regression
* Policy evaluation using Difference-in-Differences
* Event study visualization for dynamic treatment effects
* Fully reproducible analysis using R Markdown

## Author

Maria Murziankova

Bachelor’s student in Economics & Finance with interests in data analytics, econometrics, causal inference, and financial data analysis.