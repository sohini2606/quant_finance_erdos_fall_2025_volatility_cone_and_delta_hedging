# Volatility Cone Analysis & Delta Hedging Strategy

## Project Overview
This repository contains the complete Python implementation and analysis for a systematic option trading strategy applied to **Apple Inc. (AAPL)**. The project identifies trading opportunities by comparing market-implied risk (IV) against historical volatility (HV) distributions.

## 🎯 Core Finding: Negative Volatility Premium
[cite_start]The analysis discovered a **persistent negative volatility premium** in AAPL, where the ATM Implied Volatility ($\mathbf{10.6\%}$) was significantly below its historical median ($\mathbf{24.9\%}$) . [cite_start]This anomaly generated a strong, data-driven signal to initiate **long volatility positions** (BUY OPTIONS) .

## 🧪 Methodology and Key Models
The analysis is structured around a four-phase methodology:

1.  **Baseline:** Construction of a **Volatility Cone** from 5 years of daily stock data.
2.  **Pricing:** Extraction of Implied Volatility using the **Black-Scholes model** and **Brent's method**.
3.  **Risk:** Visualization of the **Implied Volatility Skew** (Smirk) and analysis of the Greeks (Gamma, Vega).
4.  **Validation:** Monte Carlo simulation of a delta-hedged long option position to validate profitability and optimize hedging frequency.

## 📈 Simulation Result Summary
The delta hedging simulation confirmed the strategy's effectiveness:

* [cite_start]**Profitability:** Consistent **positive mean P&L** across all tested rebalancing frequencies .
* [cite_start]**Optimal Risk Control:** The **5-day rehedging frequency** was found to be the most efficient for minimizing P\&L variance (risk) .

## 💻 Technical Setup

### Prerequisites
* Python 3.8+
* The analysis requires the following libraries:
    `numpy`, `pandas`, `scipy`, `matplotlib`, `seaborn`, `yfinance`

### How to Run
1.  Clone this repository:
    ```bash
    git clone # 🍏 Volatility Cone Analysis & Delta Hedging Strategy

## Project Overview
This repository contains the complete Python implementation and analysis for a systematic option trading strategy applied to **Apple Inc. (AAPL)**. The project identifies trading opportunities by comparing market-implied risk (IV) against historical volatility (HV) distributions.

## 🎯 Core Finding: Negative Volatility Premium
[cite_start]The analysis discovered a **persistent negative volatility premium** in AAPL, where the ATM Implied Volatility ($\mathbf{10.6\%}$) was significantly below its historical median ($\mathbf{24.9\%}$) . [cite_start]This anomaly generated a strong, data-driven signal to initiate **long volatility positions** (BUY OPTIONS) .

## 🧪 Methodology and Key Models
The analysis is structured around a four-phase methodology:

1.  **Baseline:** Construction of a **Volatility Cone** from 5 years of daily stock data.
2.  **Pricing:** Extraction of Implied Volatility using the **Black-Scholes model** and **Brent's method**.
3.  **Risk:** Visualization of the **Implied Volatility Skew** (Smirk) and analysis of the Greeks (Gamma, Vega).
4.  **Validation:** Monte Carlo simulation of a delta-hedged long option position to validate profitability and optimize hedging frequency.

## 📈 Simulation Result Summary
The delta hedging simulation confirmed the strategy's effectiveness:

* [cite_start]**Profitability:** Consistent **positive mean P&L** across all tested rebalancing frequencies .
* [cite_start]**Optimal Risk Control:** The **5-day rehedging frequency** was found to be the most efficient for minimizing P\&L variance (risk) .

## 💻 Technical Setup

### Prerequisites
* Python 3.8+
* The analysis requires the following libraries:
    `numpy`, `pandas`, `scipy`, `matplotlib`, `seaborn`, `yfinance`

### How to Run
1.  Clone this repository:
    ```bash
    git clone # 🍏 Volatility Cone Analysis & Delta Hedging Strategy

## Project Overview
This repository contains the complete Python implementation and analysis for a systematic option trading strategy applied to **Apple Inc. (AAPL)**. The project identifies trading opportunities by comparing market-implied risk (IV) against historical volatility (HV) distributions.

## 🎯 Core Finding: Negative Volatility Premium
[cite_start]The analysis discovered a **persistent negative volatility premium** in AAPL, where the ATM Implied Volatility ($\mathbf{10.6\%}$) was significantly below its historical median ($\mathbf{24.9\%}$) . [cite_start]This anomaly generated a strong, data-driven signal to initiate **long volatility positions** (BUY OPTIONS) .

## 🧪 Methodology and Key Models
The analysis is structured around a four-phase methodology:

1.  **Baseline:** Construction of a **Volatility Cone** from 5 years of daily stock data.
2.  **Pricing:** Extraction of Implied Volatility using the **Black-Scholes model** and **Brent's method**.
3.  **Risk:** Visualization of the **Implied Volatility Skew** (Smirk) and analysis of the Greeks (Gamma, Vega).
4.  **Validation:** Monte Carlo simulation of a delta-hedged long option position to validate profitability and optimize hedging frequency.

## 📈 Simulation Result Summary
The delta hedging simulation confirmed the strategy's effectiveness:

* [cite_start]**Profitability:** Consistent **positive mean P&L** across all tested rebalancing frequencies .
* [cite_start]**Optimal Risk Control:** The **5-day rehedging frequency** was found to be the most efficient for minimizing P\&L variance (risk) .

## 💻 Technical Setup

### Prerequisites
* Python 3.8+
* The analysis requires the following libraries:
    `numpy`, `pandas`, `scipy`, `matplotlib`, `seaborn`, `yfinance`

### How to Run
1.  Clone this repository:
    ```bash
    git clone https://github.com/sohini2606/quant_finance_erdos_fall_2025_volatility_cone_and_delta_hedging/
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt 
    ```
    *(Note: Create a `requirements.txt` file listing all required packages.)*
3.  Open and run the main analysis file:
    ```bash
    jupyter notebook final_project.ipynb
    ```

---
**Author:** Sohini Mukherjee
**Analysis Period:** 2020–2025]
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt 
    ```
    *(Note: Create a `requirements.txt` file listing all required packages.)*
3.  Open and run the main analysis file:
    ```bash
    jupyter notebook final_project.ipynb
    ```

---
**Author:** Sohini Mukherjee
**Analysis Period:** 2020–2025
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt 
    ```
    *(Note: Create a `requirements.txt` file listing all required packages.)*
3.  Open and run the main analysis file:
    ```bash
    jupyter notebook final_project.ipynb
    ```

---
**Author:** Sohini Mukherjee
**Analysis Period:** 2020–2025
