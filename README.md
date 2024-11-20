# PredicitonofPoliticalInstability
# Country Political Stability Classification

This project uses historical datasets to classify countries based on their **Human Development Index (HDI)** values, **Fragile States Index (FSI)** values, **Currency Strength Index (CSI)** values, **Tax to GDP Ratio** values, **Ecological Threat Report (ETR)** values  and other indicators to assess their political stability. It demonstrates data loading, threshold-based classification, and basic data processing using Python.

---

## Features
- **Data Integration**: Combines data from multiple sources (FSI, CSI, Tax to GDP Ratio, ETR, and HDI).
- **Threshold-Based Classification**: Classifies countries as **Politically Stable** or **Politically Unstable** based on HDI values and user-defined thresholds for other indicators.
- **Iterative Processing**: Iterates through each country and computes its political stability status.

---

## Dataset Details
The following datasets are used:
1. **Fragile States Index (FSI)**: Evaluates the stability and the fragility of states.
2. **Currency Strength Index (CSI)**: Measures the strength of a currency.
3. **Tax to GDP Ratio**: Assesses a country's economic efficiency.
4. **ETR**: Tracks external threat rankings and scores.
5. **Human Development Index (HDI)**: Measures countries’ social and economic development.

---

## Prerequisites
1. Python 3.x
2. Required Python libraries:
   - `pandas`
   - `scikit-learn`
3. Datasets in `.xls` or `.xlsx` format:
   - `FSI.xlsx`
   - `CurrencyStrengthIndex.xls`
   - `TaxToGDPRatio.xls`
   - `ETR.xlsx`
   - `HDI.xlsx`

---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/country-stability-classification.git

# For datasets, kindly reachout via email. 
