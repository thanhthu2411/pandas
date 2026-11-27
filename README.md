# Superstore Sales Analysis

A data analysis project that uses Python and pandas to explore the Superstore sales dataset. It answers two questions about the data and shows the results in charts made with matplotlib:

1. Which customers contributed the most to overall sales in 2017?
2. Which state generated the most sales in each year, and what percent of each year's total did each state make up?

The analysis uses a **filter** (orders from 2017), a **sort** (highest sales first), and an **aggregation** (sum of sales per customer and per state). For the stretch challenge, it draws a bar chart of the top 10 customers in 2017 and a pie chart of the top 5 states by sales in 2015.


## Instructions for Build and Use

Steps to build and/or run the software:

1. Download or clone this repository, and make sure the dataset (`train.csv`) is in the same folder as the notebook.
2. (Optional) Create and activate a virtual environment: `python -m venv venv`
3. Install the libraries: `pip install pandas matplotlib jupyter`
4. Open the notebook `[your notebook name].ipynb` in VS Code (with the Jupyter extension) or Jupyter Notebook.

Instructions for using the software:

1. Run the cells from top to bottom (or use **Run All**) so the data loads before the analysis runs.
2. Read the results of each question in the output below its code cell: the top customers for 2017, and the sales and percent for each state by year.
3. View the charts in the notebook output.
4. To look at a different year, change the year in the filter or pie chart cell and run it again.

## Development Environment

To recreate the development environment, you need the following software and/or libraries with the specified versions:

* Python [your version, e.g. 3.12]
* pandas [your version]
* matplotlib [your version]
* Jupyter Notebook, or VS Code with the Jupyter extension

(Run `pip show pandas matplotlib` to see your versions.)

## Useful Websites to Learn More

I found these websites useful in developing this software:

* [Corey Schafer's pandas tutorials (YouTube)](https://www.youtube.com/@coreyms)
* [10 Minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
* [Kaggle Learn: Pandas](https://www.kaggle.com/learn/pandas)
* [Matplotlib documentation](https://matplotlib.org/stable/index.html)
* [Superstore dataset on Kaggle]([paste the link to your dataset])

## Future Work

The following items I plan to fix, improve, and/or add to this project in the future:

* [ ] Make pie charts for the other years so all years can be compared
* [ ] Analyze profit and discounts, not only sales
* [ ] Try the same analysis with Polars and compare it to pandas