# Hands-On Data Lab Implementation

## Project Summary
This project demonstrates basic data analysis using Python. It covers data creation, inspection, cleaning checks, calculations, grouping, and visualization.

## Tools and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset
The file `sample_sales_data.csv` contains sample sales records with these columns:
- `Product`: product name
- `Quantity`: number of units sold
- `Price`: price per unit in INR
- `City`: city associated with the sale
- `Order_Date`: sample order date
- `Revenue`: Quantity multiplied by Price

## Analysis Performed
1. Loaded the dataset into a Pandas DataFrame.
2. Checked the number of rows and columns.
3. Checked for missing values and duplicate rows.
4. Calculated revenue for each record.
5. Summarized revenue by product and city.
6. Summarized revenue by month.
7. Created charts to compare product-wise revenue, city-wise revenue, and quantity versus revenue.

## Key Findings
- Total revenue in the sample dataset: ₹385,000.
- Total units sold: 17.
- Laptop revenue: ₹150,000.
- Phone revenue: ₹135,000.
- Tablet revenue: ₹100,000.
- Hyderabad revenue: ₹160,000.
- Vizag revenue: ₹125,000.
- Vijayawada revenue: ₹100,000.
- January 2026 revenue: ₹235,000.
- February 2026 revenue: ₹150,000.

## How to Run
1. Install Python.
2. Install the required libraries:
   ```bash
   py -m pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Start Jupyter Notebook:
   ```bash
   py -m notebook
   ```
4. Open the project notebook (`hands_on_data_lab.ipynb`) and run the cells from top to bottom.

## Note
This is a small sample dataset created for learning and demonstration. The results describe only these sample records and should not be treated as real business data.
