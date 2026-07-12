# Brent Oil Price Change Point Analysis

## Project Overview

This project analyzes the impact of major geopolitical events, economic shocks, international sanctions, and OPEC policy decisions on historical Brent crude oil prices.

The objective is to identify statistically significant structural changes in Brent oil prices using Bayesian Change Point Detection implemented with PyMC. The project combines exploratory data analysis, Bayesian inference, and interactive visualization to provide insights that support investors, policymakers, and energy companies in understanding oil market dynamics.

---

## Business Problem

Brent crude oil prices are highly sensitive to global political and economic events. Sudden changes in oil prices create uncertainty for governments, investors, and energy companies.

This project aims to:

- Detect structural changes in Brent crude oil prices.
- Quantify the impact of major historical events on oil prices.
- Compare detected change points with real-world geopolitical and economic events.
- Present the findings through an interactive dashboard.

---

## Dataset

The dataset contains historical daily Brent crude oil prices.

**Source:**

- Brent Oil Prices Dataset (provided as part of the challenge)

**Date Range**

20 May 1987 – 30 September 2022

**Variables**

| Column | Description |
|---------|-------------|
| Date | Date of observation |
| Price | Brent crude oil price (USD per barrel) |

The project also includes a manually compiled dataset of significant geopolitical events, OPEC decisions, economic crises, and international sanctions that potentially affected Brent oil prices.

---

## Project Structure

```
project-root/
│
├── data/
│   ├── BrentOilPrices.csv
│   └── events.csv
│
├── notebooks/
│   └── task1_eda.ipynb
│
├── src/
│
├── scripts/
│
├── tests/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository

```bash
git clone <repository-url>
```

Navigate to the project

```bash
cd <repository-name>
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the virtual environment

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
notebooks/task1_eda.ipynb
```

and run the notebook from top to bottom.

Future notebooks will include Bayesian Change Point Modeling (Task 2) and Dashboard Development (Task 3).

---

## Analysis Workflow

The project follows these analytical steps:

1. Load and inspect Brent oil price data.
2. Perform data cleaning and preprocessing.
3. Conduct exploratory data analysis.
4. Analyze trend, stationarity, and volatility.
5. Compile historical geopolitical and economic event data.
6. Implement Bayesian Change Point Detection using PyMC.
7. Compare detected change points with historical events.
8. Develop an interactive Flask–React dashboard.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- SciPy
- Statsmodels
- PyMC
- Jupyter Notebook
- Flask
- React

---

## Repository Contents

- Exploratory Data Analysis
- Stationarity Testing
- Log Return Analysis
- Historical Event Dataset
- Bayesian Change Point Detection (Task 2)
- Interactive Dashboard (Task 3)

---

## Author

Prepared as part of the Birhan Energies Brent Oil Price Analysis Challenge.