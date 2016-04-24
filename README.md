# Data Manipulation and Analysis in Python using `pandas`

## NGCM Summer Academy 2016

This tutorial will introduce the use of Python for statistical data analysis, using data stored as Pandas DataFrame objects. Much of the work involved in analyzing data resides in importing, cleaning and transforming data in preparation for analysis. Therefore, the first half of the course is comprised of a 2-part overview of basic and intermediate Pandas usage that will show how to effectively manipulate datasets in memory. This includes tasks like indexing, alignment, join/merge methods, date/time types, and handling of missing data. Next, we will cover plotting and visualization using Pandas and Seaborn, focusing on creating effective visual representations of your data, while avoiding common pitfalls. Finally, participants will be introduced to methods for statistical data modeling using some of the advanced functions in Numpy, Scipy and Pandas. This will include fitting statistical models using linear and non-linear models, bootstrapping methods, and imputation of missing data. Each section of the tutorial will involve hands-on manipulation and analysis of sample datasets, to be provided to attendees in advance.

## Instructors

Christopher Fonnesbeck (Vanderbilt University) Skipper Seabold (Civis Analytics)

## Outline

Thursday, June 23, 09:30 - 13:00

* NumPy arrays and indexing
* Multidimensional arrays
* Array methods and functions
* Series and DataFrame objects
* Importing data
* Setting options
* Categorical data
* Indexing, data selection and subsetting
* where and query
* Hierarchical indexing
* Reading and writing files
* Sorting and ranking
* Missing data
* Data summarization
* Data Wrangling with Pandas

Thursday, June 23, 14:30 - 17:30

* Date/time types
* Merging and joining DataFrame objects
* Concatenation
* Text data operations
* Reshaping DataFrame objects
* Pivoting
* Data transformation
* Rolling and window operations
* Permutation and sampling
* Data aggregation and GroupBy operations
* Out-of-core workflows
* Method chaining
* Pipe

Friday, June 24, 09:30 - 13:00

* Plotting in Pandas vs Matplotlib
* Bar plots
* Histograms
* Box plots
* Grouped plots
* Scatterplots
* Trellis plots

Friday, June 24, 14:30 - 17:30

* Statistical operations in pandas
* Fitting regression models
* Bootstrapping
* Working with missing data
* Parallel computing with Dask
* Statistical Data Modeling
* Statistical plotting with Seaborn

## Prerequisites

This is an intermediate-level computing course, so some previous experience with Python is required. Some undergraduate-level statistics is also recommended.

## Software Requirements

Python 3.5. We recommend installing the free Anaconda distribution of Python, available from Continuum Analytics.

The following packages should be installed on your system:

* ipython>=3.0
* numpy>=1.9
* pandas>=0.16.2
* scipy
* matplotlib
* scikit-learn
* seaborn
* patsy
* numexpr
* bottleneck
* xlrd
* jinja2
* tornado
* pyzmq
* jsonschema
* mpld3
* dask

If you have installed Anaconda, these should already be available to you.

## Getting this repository

    git clone https://github.com/fonnesbeck/ngcm_pandas_course.git

Make sure you have the requirements installed.

    cd ngcm_pandas_course

If using pip,

    pip install -r requirements.txt