# Investigating Bias in AI for Sepsis Diagnosis: Analyzing Ethnic Disparities in ICU Decision-Making

## Project Overview

This project investigates the presence of racial bias in machine learning models used to predict sepsis in ICU patients. By leveraging the MIMIC-III dataset, the study evaluates the predictive performance of various models across different racial groups and explores methods to improve fairness while maintaining accuracy.

The project was conducted as part of the DSCI 531 course (Fairness in Machine Learning) at the University of Southern California in Spring 2025.

## Objective

- Develop predictive models for early sepsis diagnosis using real-world ICU data.
- Quantify and evaluate model bias across racial groups.
- Apply fairness metrics to assess equity in model outcomes.
- Experiment with bias mitigation techniques and evaluate their effectiveness.

## Methodology

- Used the MIMIC-III critical care dataset to extract relevant features for sepsis prediction.
- Trained machine learning models including Logistic Regression, Random Forest, and Multi-Layer Perceptron (MLP).
- Evaluated group fairness using:
  - False Positive Rate (FPR)
  - False Negative Rate (FNR)
  - Equal Opportunity Difference
  - Demographic Parity
- Interpreted model predictions using SHAP to identify feature disparities across racial groups.
- Applied threshold adjustment and adversarial debiasing techniques to reduce model bias.

## Summary of Findings

- Initial models revealed disparities in predictive performance across racial groups, especially for Black patients.
- Adversarial debiasing effectively reduced fairness gaps while preserving overall model performance.
- SHAP analysis confirmed structural bias by highlighting group-specific differences in feature influence.

---

## Repository Structure

This repository includes the following files:

#### `DSCI531_FinalReport_YooPaul_PayapulliJoshua_PatelArmand.pdf`

The final report submitted for the course. It includes full documentation of the project scope, dataset description, methodology, and findings.

#### `531_project.ipynb`

A Jupyter Notebook containing the full analysis pipeline. Includes data processing, model training, evaluation metrics, visualization of results, and application of fairness techniques.

---

## Author

**Paul Yoo**  
M.S. in Applied Data Science  
University of Southern California, Spring 2025  
Data preprocessing, fairness metric implementation, bias mitigation, model evaluation  
[LinkedIn](https://www.linkedin.com/in/pkyoo) | [GitHub](https://github.com/PKYOO-116)
