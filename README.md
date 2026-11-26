# Hands-On Data Analysis with Python

This is a small practice project I built to get more comfortable working with data in Python. I used a sample sales dataset to practise the steps I would normally follow before sharing a simple analysis: load the data, check its quality, calculate useful values, group the results and make a few charts.

## What is in this repository?

| File | Purpose |
|---|---|
| `hands_on_data_lab.ipynb` | Notebook containing the analysis and visualisations |
| `sample_sales_data.csv` | Small sample sales dataset used by the notebook |

## Tools used

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn

## What I worked on

1. Loaded the CSV file into a Pandas DataFrame.
2. Reviewed the dataset shape, columns and data types.
3. Checked for missing values and duplicate rows.
4. Calculated revenue using quantity multiplied by unit price.
5. Grouped sales by product, city and month.
6. Used charts to compare the results.

## A quick look at the sample results

The dataset contains six sample sales records. In this dataset:

- Total revenue is **₹385,000**.
- A total of **17 units** were sold.
- Laptop sales contributed **₹150,000**.
- Hyderabad recorded **₹160,000** in revenue.
- January 2026 recorded **₹235,000** in revenue.

These figures are only the result of the small sample included here. They are not real company sales figures and should not be used to make business decisions.

## Run it on your computer

You will need Python installed.

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter
```

Clone the repository and open the project folder:

```bash
git clone https://github.com/Venkatakishore125/HandsOnDataLab.git
cd HandsOnDataLab
jupyter notebook
```

Open `hands_on_data_lab.ipynb` and run the cells from top to bottom.

## What I would like to improve next

- Work with a larger and more realistic sales dataset.
- Add more data-quality checks, including date and numeric-column validation.
- Compare average order value and product contribution.
- Write a short business takeaway below each chart.
- Add a requirements file and screenshots of the notebook output.

## About

This is a learning project focused on practising the basic data-analysis workflow. Feedback and suggestions are welcome.

**Author:** Venkata Kishore Seelam  
**GitHub:** [Venkatakishore125](https://github.com/Venkatakishore125)
