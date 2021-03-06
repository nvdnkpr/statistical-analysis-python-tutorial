# Statistical Data Analysis in Python

Introductory Tutorial, SciPy 2013, 25 June 2013

***Christopher Fonnesbeck - Vanderbilt University School of Medicine***

Chris Fonnesbeck is an Assistant Professor in the Department of Biostatistics at the Vanderbilt University School of Medicine. He specializes in computational statistics, Bayesian methods, meta-analysis, and applied decision analysis. He originally hails from Vancouver, BC and received his Ph.D. from the University of Georgia.

## Description

This tutorial will introduce the use of Python for statistical data analysis, using data stored as Pandas DataFrame objects. Much of the work involved in analyzing data resides in importing, cleaning and transforming data in preparation for analysis. Therefore, the first half of the course is comprised of a 2-part overview of basic and intermediate Pandas usage that will show how to effectively manipulate datasets in memory. This includes tasks like indexing, alignment, join/merge methods, date/time types, and handling of missing data. Next, we will cover plotting and visualization using Pandas and Matplotlib, focusing on creating effective visual representations of your data, while avoiding common pitfalls. Finally, participants will be introduced to methods for statistical data modeling using some of the advanced functions in Numpy, Scipy and Pandas. This will include fitting your data to probability distributions, estimating relationships among variables using linear and non-linear models, and a brief introduction to Bayesian methods. Each section of the tutorial will involve hands-on manipulation and analysis of sample datasets, to be provided to attendees in advance.

The target audience for the tutorial includes all new Python users, though we recommend that users also attend the NumPy and IPython session in the introductory track.

## Outline

### Introduction to Pandas (45 min)

* Importing data
* Series and DataFrame objects
* Indexing, data selection and subsetting
* Hierarchical indexing
* Reading and writing files
* Date/time types
* String conversion
* Missing data
* Data summarization

### Data Wrangling with Pandas (45 min)

* Indexing, selection and subsetting
* Reshaping DataFrame objects
* Pivoting
* Alignment
* Data aggregation and GroupBy operations
* Merging and joining DataFrame objects

### Plotting and Visualization (45 min)

* Time series plots
* Grouped plots
* Scatterplots
* Histograms
* Visualization pro tips

### Statistical Data Modeling (45 min)

* Fitting data to probability distributions
* Fitting regression models
* Spline models
* Bayesian models

## Required Packages

* Python 2.7 or higher (including Python 3)
* pandas >= 0.11.1 and its dependencies
* NumPy >= 1.6.1
* matplotlib >= 1.0.0
* pytz
* IPython >= 0.12
* pyzmq
* tornado