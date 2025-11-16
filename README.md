# 💰 Simple Personal Finance Tracker (CLI)

This Python script serves as a straightforward Command Line Interface (CLI) tool for tracking personal finances. It allows you to add transactions (income and expenses), view a summary of your finances within a specific date range, and visualize the flow of your money using a chart.

## 🚀 Features

* **Data Storage:** Transactions are persistently stored in a CSV file (`finance_data.csv`).
* **Filtering:** View and summarize transactions within a selected time period.
* **Financial Summary:** Calculation of total income, total expense, and net savings/loss.
* **Visualization:** Generates a line plot to compare income and expenses over time using Matplotlib.

## 🛠️ Project Setup

To run the script, you need two Python files (`main.py` and `data_entry.py`) and a few external libraries.

### 1. File Structure

Create the following two files in the same directory:

* `main.py` (The main logic)
* `data_entry.py` (Input and validation logic)

### 2. Install Dependencies

Install the required Python packages (`pandas` and `matplotlib`):

`bash
pip install pandas
pip install matplotlib`


2. 🖥️ Main Menu

The application will launch and present the main menu:

```
--- Personal Finance Tracker ---
1. Add a new transaction
2. View transactions and summary within a date range
3. Exit
Enter your choice (1-3):
```
3. ➕ Adding a Transaction (Option 1)

Select 1 to input a new record. The script will guide you through entering the necessary data:
Prompt	Format/Input	Notes
Date	dd-mm-yyyy or Enter	Pressing Enter uses today's date.
Amount	Numeric value (e.g., 150.75)	Must be a positive number.
Category	1 (Income) or 2 (Expense)	Choose the corresponding number.
Description	Text (e.g., "Monthly salary")	Optional descriptive text.


4. 📊 Viewing Summary and Plot (Option 2)

Select 2 to analyze your finances:

    You will be prompted for a start date and end date in dd-mm-yyyy format to define the reporting period.

    The script will display all transactions in that range, followed by the Total Income, Total Expense, and Total Savings.

    Finally, you will be asked if you want to view the plot: Do you want to see the plot? (y/n):. Enter y to display the visualization of income and expenses over time .


5. 🚪 Exiting (Option 3)

Select 3 to close the application and return to the command line.


