# SmartSpend — Personal Expense Analytics

## 1. About the Project
SmartSpend is a Python-based personal expense analytics project that analyzes financial transaction data from a CSV file. It helps users understand their income, expenses, category-wise spending, and monthly expense trends through calculations and visualizations.

## 2. Features
- Calculate total income.
- Calculate total expenses.
- Calculate net balance.
- Analyze expenses by category.
- Visualize category-wise expenses using a bar chart and pie chart.
- Analyze monthly expenses using a graph.
- Identify the highest-spending category and month.
- Perform basic dataset checks.

## 3. Technologies Used
- Python
- Pandas
- Matplotlib
- Google Colab
- CSV dataset

## 4. Dataset
The project uses a CSV file containing transaction information such as date, category, transaction type, and amount.

The `Amount` column is used for financial calculations.

## 5. How to Run
1. Open the project notebook in Google Colab.
2. Upload `expense_data_1.csv`.
3. Run the notebook cells in order.
4. Review the financial summaries and graphs.

## 6. Main Calculations
- **Net Balance = Total Income − Total Expenses**
- Category-wise expense totals are calculated by grouping transactions by category.
- Monthly expense totals are calculated by grouping transactions by month.

## 7. Project Objective
The objective of SmartSpend is to turn raw transaction data into understandable financial summaries and visual insights.

## 8. Future Scope
- Add an interactive dashboard.
- Support more transaction file formats.
- Add budget comparison features.
