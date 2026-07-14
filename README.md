# debt-risk-prediction-ph
Predicting Next-Quarter Debt Servicing Risk of Philippine Listed Companies Using Machine Learning and Financial News Sentiment Analysis

Disclaimer: This repository is provided for academic and research purposes only. Financial data and news articles are derived from publicly available sources. Copyright remains with the original publishers. Any proprietary or copyrighted datasets are not redistributed in this repository.

Overview

This capstone project develops a machine learning framework for predicting the next-quarter debt servicing risk of Philippine companies by integrating structured financial statement data with unstructured financial news sentiment.

The study demonstrates how Natural Language Processing (NLP) and Machine Learning (ML) can be combined to enhance corporate credit risk assessment. Financial sentiment is extracted from publicly available news articles using FinBERT, while financial ratios and macroeconomic indicators are used alongside sentiment features to improve prediction performance.

The project was completed as part of the Postgraduate Diploma in Artificial Intelligence and Machine Learning at the Asian Institute of Management (AIM).

Problem Statement

Traditional debt risk assessment primarily relies on historical financial statements, which may not fully capture rapidly changing market perceptions and emerging business risks.

This project investigates whether incorporating financial news sentiment improves the prediction of next-quarter debt servicing risk among Philippine listed companies

Objectives

The project aims to:

- Develop a baseline debt risk prediction model using financial statement variables.
- Extract financial sentiment from news articles using FinBERT.
- Engineer quarterly sentiment indicators for each company.
- Integrate financial and sentiment features into machine learning models.
- Compare model performance before and after incorporating sentiment.
- Explain model predictions using SHAP for improved interpretability.

Dataset

Financial Data

--30 Philippine listed companies
- Quarterly observations
- Period: Q4 2020 – Q1 2026
- 660 company-quarter observations

Financial variables include:

- Liquidity ratios
- Profitability ratios
- Leverage ratios
- Cash flow measures
- Company size
- Macroeconomic indicators

Sentiment Data

- Publicly available financial news and disclosures collected 

Dataset summary:

- 857 financial news articles
- Quarterly sentiment aggregation
- FinBERT sentiment scores
- Company-quarter sentiment features

Methodology - The project follows the CRISP-DM framework.

Machine Learning Models - Three supervised classification algorithms were evaluated

Results - The Random Forest classifier achieved the best overall performance after integrating financial and sentiment features.

Best Model - Random Forest Classifier

The study demonstrates that incorporating financial news sentiment provides additional predictive information beyond traditional financial statement variables


License & Credits
Author: Jean Shermin B. Geronimo
Institution: Asian Institute of Management (AIM)

This project is submitted in partial fulfillment of the requirements for the
Postgraduate Diploma in Artificial Intelligence and Machine Learning.

Tools and Acknowledgements
Google Colab was used as the execution environment for developing and running the Jupyter notebook.
ChatGPT Plus and MS Copilot was used as a supportive tool for drafting, structuring, and refining narrative components of the project.


