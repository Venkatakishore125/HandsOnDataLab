# Sales Data Analysis with Python

This is a small hands-on project I built to practise a complete beginner-level data analysis workflow with Python. I use a sample sales file to inspect the data, check for common data-quality issues, calculate revenue, compare products and cities, and create charts.

The dataset has only six records, so the goal is to practise the process rather than make claims about a real business.

## Project files

| File | What it is for |
|---|---|
| `hands_on_data_lab.ipynb` | Main notebook with the analysis and charts |
| `sample_sales_data.csv` | Sample sales data used by the notebook |
| `requirements.txt` | Python libraries needed to run the notebook |
| `.gitignore` | Keeps local and generated files out of Git |

## Tools

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib

## What the notebook covers

1. Load the CSV file and inspect its columns and data types.
2. Review missing values and duplicate records.
3. Prepare the product, city, quantity, price and date fields.
4. Recalculate revenue from quantity multiplied by price.
5. Summarise revenue and units sold by product and city.
6. Group revenue by month and visualise the results.
7. Identify the highest-revenue order record.
8. Export the cleaned data to a CSV file.

## Sample findings

The current sample file contains six sales records. The notebook calculates:

- **Total revenue:** ₹385,000
- **Units sold:** 17
- **Laptop revenue:** ₹150,000
- **Phone revenue:** ₹135,000
- **Tablet revenue:** ₹100,000
- **Hyderabad revenue:** ₹160,000
- **Vizag revenue:** ₹125,000
- **Vijayawada revenue:** ₹100,000
- **January 2026 revenue:** ₹235,000
- **February 2026 revenue:** ₹150,000

These are calculations from the included sample only. They are not real company figures, and the dataset is too small to support wider business conclusions.

## Run the project

You will need Python installed.

Clone the repository:

```bash
git clone https://github.com/Venkatakishore125/HandsOnDataLab.git
cd HandsOnDataLab
```

Install the libraries:

```bash
python -m pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

Open `hands_on_data_lab.ipynb` and run the cells from top to bottom. Keep `sample_sales_data.csv` in the same folder as the notebook.

The notebook creates `cleaned_sales_data.csv` when it runs. That file is generated output and is excluded from Git by `.gitignore`.

## Possible next improvements

- Try a larger dataset with more dates, products and cities.
- Add more data-quality checks and explain any removed records.
- Explore product mix, average selling price and profit when cost data is available.
- Add a short interpretation below each chart.

## About

This is a learning project by **Venkata Kishore Seelam**.

[GitHub profile](https://github.com/Venkatakishore125)
