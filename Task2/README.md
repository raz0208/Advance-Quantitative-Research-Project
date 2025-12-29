# Natural Gas Storage Contract Pricing Prototype
JPMorgan Chase & Co. Quantitative Research Virtual Experience Program on Forage

---

## Overview

This repository contains a prototype pricing model developed for a commodities trading desk. The tool is designed to value natural gas storage contracts by analyzing seasonal price spreads—specifically the opportunity to buy gas during low-cost periods (summer) and sell during high-demand periods (winter).

## Key Features

* **Price Curve Analysis:** Loads historical price data and forecasts future trends to create a continuous daily forward price curve.
* **Contract Valuation:** Calculates the net value of a storage contract by comparing purchase/sale prices against operational costs.
* **Cost Modeling:** Accounts for complex cash flows including:
* Monthly storage/rental fees.
* Injection and withdrawal costs.
* Transportation charges.


**Interactive Interface:** A Jupyter Notebook-based tool that allows traders to manually input dates and volumes to simulate different contract scenarios.

## Repository Structure

* `Natural_Gas_Storage_Contract_Pricing_Model.ipynb`: Focuses on data preparation, visualization of historical trends, and price forecasting.
* `Natural_Gas_Storage_Contract_Pricing_App.ipynb`: Contains the main pricing logic and a user interface for calculating specific contract values based on user inputs.

## Usage

1. Ensure all data files (e.g., `Nat_Gas.csv`) are in the working directory.
2. Open `Natural_Gas_Storage_Contract_Pricing_App.ipynb`.
3. Run the cells to initialize the pricing function.
4. Input your specific contract parameters (injection dates, withdrawal dates, storage costs, max volume) to receive the estimated contract value.

## Dependencies

* Python 3.x
* Pandas
* NumPy
* Matplotlib / Seaborn
* Jupyter Notebook / Google Colab
