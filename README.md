# Anomaly Detection on Bitcoin Prices

## Overview
This project aims to identify anomalies in Bitcoin prices during specific time windows, focusing on opening and closing prices. The dataset uses UNIX time as the time measurement standard.

**Dataset**: The dataset can be found [here](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data).

---

## Dataset
The dataset includes the following labels:
- **Timestamp**: When the data was recorded.
- **Open**: The price at the start of the time window.
- **High**: The highest price within the time window.
- **Low**: The lowest price within the time window.
- **Close**: The price at the end of the time window.
- **Volume**: The trading volume during the time window.

---

## Objective
The cryptocurrency market is known for its high volatility. At the conclusion of this project, we aim to determine which data points should be categorized as anomalies and which should be considered normal.

---

## Models
We will evaluate the performance of the following models to identify the most suitable approach for anomaly detection:
- **KNN (K-Nearest Neighbors)**
- **LODA (Lightweight On-line Detector of Anomalies)**
- **ABOD (Angle-Based Outlier Detection)**
- **OCSVM (One-Class Support Vector Machine)**

---

## Outcome
The goal is to analyze and compare the performance of these models to conclude which is best suited for detecting anomalies in Bitcoin price data.

