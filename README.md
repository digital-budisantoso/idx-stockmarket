# Indonesian Stock Market Sector Dataset (IDX)

This repository provides a curated dataset of Indonesian stock market data obtained from the Indonesia Stock Exchange (IDX). The dataset covers multiple key sectors of the Indonesian equity market and includes both raw and processed data suitable for financial research and quantitative analysis.

The repository contains stock market data from the following sectors:

- Energy  
- Technology  
- Consumer Cyclical  
- Financials  

In addition, the dataset includes the Indonesian composite market index, namely the IHSG (IDX Composite Index), which represents the overall performance of the Indonesian stock market.

The primary objective of this repository is to provide a structured dataset that can support **time series analysis, econometric modeling, and causal inference research**, including applications such as **Granger causality analysis**, sectoral market interaction studies, and financial forecasting.

---

# Repository Structure

The repository is distributed as a compressed `.zip` file containing three main directories:

## 1. `emiten/`

This folder contains lists of publicly listed companies (emiten) for each sector included in the dataset.  
These files provide the mapping between stock tickers and their respective sectors within the IDX classification.

---

## 2. `stock_data/`

This directory contains the **raw stock price data for individual companies**.  
Each file corresponds to a specific listed company and includes historical market data collected from the IDX.

These datasets can be used for:

- Firm-level financial analysis  
- Custom sector index construction  
- Portfolio analysis  
- Market microstructure research  

---

## 3. `market_analysis/`

This folder contains **processed datasets** derived from the raw stock data.

The data in this directory includes:

- Calculated **sectoral indices**
- The **composite market index (IHSG)**
- Combined datasets integrating sector indices with the overall market index

These processed datasets are designed to be **ready-to-use for time series analysis**, including:

- Vector Autoregression (VAR)
- Granger causality testing
- Market spillover analysis
- Sectoral co-movement analysis
- Financial forecasting models

---

# Intended Use

The dataset is intended for:

- Academic research  
- Financial market analysis  
- Econometric modeling  
- Machine learning applications on financial time series  
- Teaching materials for financial data analysis  

Researchers can directly utilize the processed datasets for statistical modeling or reconstruct their own indices using the raw stock data provided.

---

# Citation

If you use this dataset in your research, academic publications, or projects, please cite this repository as follows:

Santoso, A. (2026). *Indonesian Stock Market Sector Dataset (IDX)* [Data set]. GitHub. https://github.com/digital-budisantoso/idx-stockmarket

Example in APA format:

Santoso, A. (2026). *Indonesian Stock Market Sector Dataset (IDX)* [Data set]. GitHub. https://github.com/digital-budisantoso/idx-stockmarket

Proper citation helps support reproducible research and acknowledges the effort involved in collecting and preparing the dataset.

