# explainable-generative-ai-financial-forecasting-pub
Explainable Generative AI system for financial time series forecasting with interpretable models and an interactive dashboard.

# Explainable Generative AI Dashboard for Real Time Financial Forecasting and Decision Support

This repository presents a portfolio overview of the system developed for the Master’s thesis:

“Explainable Generative AI Dashboard for Real Time Financial Forecasting and Decision Support.”

The project implements a reproducible forecasting pipeline that combines financial market data with contextual signals derived from news and social media. The system focuses on transparent forecasting and decision support through explainable machine learning models and interactive visual analytics.

This repository provides an overview of the system architecture, methodology, and outputs.
The full research implementation and training pipelines are maintained in a private repository.

# Project Overview

The system supports a daily forecasting workflow designed for transparency and reproducibility.
It integrates machine learning models, contextual data features, and explainability techniques into a unified decision-support environment.

# Key objectives of the project:

Forecast next-day S&P 500 returns using machine learning models

Integrate contextual signals from news and social media

Provide explainable predictions through SHAP feature attribution

Generate plausible multi-day market scenarios

Deliver results through an interactive dashboard

# System Architecture

The system includes several key components.

Data Ingestion

Market and contextual data sources are collected and prepared for analysis.

Data Processing

Automated pipelines clean, transform, and structure raw datasets.

Feature Engineering

Financial indicators and contextual features are prepared for modeling.

Forecasting Models

Time series forecasting is performed using:

LSTM neural networks

Classical regression and ensemble models

Generative Scenarios

A Variational Autoencoder (VAE) generates plausible multi-day return paths for scenario exploration.

Explainability

Model predictions are interpreted using SHAP feature attribution.

Dashboard

A Streamlit dashboard provides:

Forecast visualizations

Scenario inspection

Narrative reporting

Model explainability insights

# Technologies

Python

SQL

Pandas

Scikit-learn

TensorFlow / PyTorch

SHAP Explainability

Streamlit

AWS Cloud Services

# Example Outputs

The system produces several outputs including:

Financial return forecasts

Feature importance analysis

Model evaluation metrics

Scenario simulations

Interactive dashboard visualizations

Example outputs include:

Forecast plots

SHAP feature importance charts

Scenario simulations

Dashboard views

# Folder Structure (Conceptual)

The full research implementation follows a structured pipeline design:

00_Scripts

01_Documentation

02_Data

03_Notebooks

04_Src

05_Results

06_App

Each module supports reproducible research workflows and artifact generation for thesis evaluation.

# Reproducibility

The original project is designed around an artifacts-first workflow, where model training and evaluation generate outputs stored in a structured results directory. These outputs are then consumed by the dashboard and reporting modules.

This design ensures that results reported in the thesis can be regenerated without manual modification.

# Portfolio Note

This repository provides an overview of the system architecture, methodology, and results.

The complete implementation, datasets, and training pipelines remain in a private research repository.

# Author

Mahdi Rajabi

M.Sc. Data Science

University of Europe for Applied Sciences – Berlin

LinkedIn

https://www.linkedin.com/in/mahdi-rajabi7

GitHub

https://github.com/mahdi-rjb
