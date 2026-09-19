# Introduction to Programming

Python coursework completed as part of my MSc in Artificial Intelligence and Data Science at the University of Hull. The module builds up from core programming concepts to reading and writing real data files and producing data visualisations, worked through a series of weekly lab notebooks and a final portfolio project. The work is organised as Jupyter notebooks, each covering one week's material, plus a final project that brings the concepts together on a larger dataset.

**Workshop 1 - Programming fundamentals**
Data types and variables, control flow (`if` / `elif` / `else`), boolean expressions, and loops (`for` and `while`).

**Workshop 2 - Functions and scope**
Defining and calling functions, return values, variable scope, and using abstraction and decomposition to make code more reusable and readable.

**Workshop 3 - File I/O, CSV and JSON**
Reading and writing files with context managers (`with`), working with the CSV and JSON formats, and a first look at NumPy for numerical computing.

**Workshop 4 - Pandas and Seaborn**
Loading and exploring data with Pandas DataFrames and Series, and building visualisations with Seaborn.

**Final portfolio project - Data processing and visualisation**
An end-to-end exercise on a customer dataset: flattening and nesting JSON records, flagging problematic rows, splitting records into separate files (for example employed vs retired customers), deriving new fields such as credit card expiry and a salary-to-commute metric, and producing univariate and multivariate plots to explore the results.

## Data files

The notebooks use a set of supporting datasets included in the repository, including `titanic.csv`, `wind_data.csv`, and several JSON files used by the final project (customer, commute, and card records).

## Running the notebooks

The project uses Python with a small set of scientific libraries, pinned in `requirements.txt`.

```bash
git clone https://github.com/sabihaafrin/intro-to-programming.git
cd intro-to-programming
pip install -r requirements.txt
jupyter notebook
```

Open any of the `.ipynb` files to view the exercises and solutions.

## Skills demonstrated

Python fundamentals, functions and program structure, file input/output, working with CSV and JSON data, data cleaning and transformation, and data analysis and visualisation with NumPy, Pandas, Matplotlib, and Seaborn.
