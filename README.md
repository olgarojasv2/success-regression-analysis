# Fanfiction Success Prediction using Linear Regression

## Overview

This project analyzes fanfiction stories from the GOLEM KG dataset to determine whether literary quality measures can predict the success of a story, measured in kudos.

The dataset (data_full.csv) contains the following features:
- Kudos (Success metric)
- Automated Readability Index (ARI)
- Flesch Grade (FG)
- Flesch Ease (FE)
- Mean Segmental Type-Token Ratio (MSTTR)
- Word Count
- Comment Count

## Objective
Using Simple Linear Regression, we assess which literary quality measures (independent variables) are significant predictors of a story’s success (dependent variable: Kudos).

## Analysing Steps

1. Identify dependent and independent variables
2. Scatterplots (using matplotlib) to visualize relationships
3. Perform Simple Linear Regression on each independent variable
4. Plot regression lines based on intercept & slope values
5. Compute R² scores to evaluate the model's predictive power
6. Analyze residuals for model accuracy
7. Perform the Shapiro-Wilk test to check the normality of residuals
8.  Compare regression results to determine the best predictors of kudos

## Vocabulary Report:
### Lexical Diversity:
MSTTR -Mean Segmental Type-Token Ratio- It is a statistical measure for lexical diversity in text analysis, calculated by averaging type-token ratios across fixed-length text segments.
### Text readability metrics:
ARI Automated Readability Index - Strong predictor of engagement.
FG Flesch-Kincaid Grade Level -Higher level scores indicate a more complex text
FE Flesch Reading Ease -Higher FE scores are easy-to-read text.
### Structural Features:
Wordcount: longer texts may reduce engagement
CommentCount: signals community interest, creating a feedback loop for future kudos
