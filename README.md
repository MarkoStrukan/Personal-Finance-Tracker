# 💰 Simple Personal Finance Tracker (CLI)

This Python script serves as a straightforward Command Line Interface (CLI) tool for tracking personal finances. It allows you to add transactions (income and expenses), view a summary of your finances within a specific date range, and visualize the flow of your money using a chart.

## 🚀 Features

* **Data Storage:** Transactions are persistently stored in a CSV file (`finance_data.csv`).
* **Filtering:** View and summarize transactions within a selected time period.
* **Financial Summary:** Calculation of total income, total expense, and net savings/loss.
* **Visualization:** Generates a line plot to compare income and expenses over time using Matplotlib.

## 🛠️ Project Setup

To run the script, you need two Python files (`finance_tracker.py` and `data_entry.py`) and a few external libraries.

### 1. File Structure

Create the following two files in the same directory:

* `finance_tracker.py` (The main logic)
* `data_entry.py` (Input and validation logic)

### 2. Install Dependencies

Install the required Python packages (`pandas` and `matplotlib`):

```bash
pip install pandas matplotlib
