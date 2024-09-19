# Altair Software - Credit Risk Analysis

This project focuses on **Credit Risk Analysis** using the **Altair** visualization library, based on the popular **Credit Risk dataset** from Kaggle. The primary objective is to assess the probability of a borrower defaulting on a loan, leveraging data analysis and visualization techniques.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Usage](#usage)
- [Visualizations](#visualizations)

## Introduction

Credit Risk Analysis is crucial for financial institutions, as it helps in determining the risk associated with loan approval. This project uses **Altair**, a declarative statistical visualization library in Python, to provide insights and patterns in the dataset.

## Dataset

The dataset used in this project is the **Credit Risk Dataset** from [Kaggle](https://www.kaggle.com/datasets). It contains information on borrower attributes like income, loan history, and repayment status, allowing us to classify borrowers as high or low risk.

Key features include:

- **Age**
- **Income**
- **Loan Amount**
- **Credit Score**
- **Employment Status**
- **Loan History**
- **Repayment Status**

## Usage

1. Preprocess the data using the `data_preprocessing.py` script:
    ```bash
    python data_preprocessing.py
    ```

2. Generate visualizations with Altair using the `visualizations.py` script:
    ```bash
    python visualizations.py
    ```

3. The analysis focuses on:
    - Distribution of credit scores.
    - Loan approval rates by risk category.
    - Correlations between loan defaults and borrower attributes.

## Visualizations

Key visualizations included are:

- **Credit Score Distribution**: A bar chart representing the distribution of borrowers' credit scores.
- **Risk Classification**: A grouped bar chart showing high-risk and low-risk borrowers based on specific attributes.
- **Correlation Matrix**: A heatmap displaying the relationships between the features.
