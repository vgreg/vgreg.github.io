.. title: Python Bootcamp
.. slug: python-bootcamp
.. date: 2017-03-21 12:01:52 UTC+11:00
.. tags: python-bootcamp python code teaching
.. category: python
.. link:
.. description:
.. type: text


This is a collection of the material that I used for the Python for
financial research  bootcamp that I taught
to honours and PhD students at the University of Melbourne in March 2017.

Outline
-------

The bootcamp is divided into four blocks of three hours each:

**1. Introduction to Python programming**

We will discuss what is Python and you will learn the basic structure of the
language. You will also learn your way around the programming environment,
including the two main editors for scientific Python, Spyder and Jupyter.

**2.	Introduction to data analysis using pandas, matplotlib**

You will learn how to import, export and transform data using pandas, the
panel data package for Python. You will also learn how to explore the data
by generating summary statistics and plotting graphs using matplotlib.

**3.	More data analysis using pandas and statsmodels**

You will learn more advanced features of Python and pandas, including dealing
with timestamps and estimating measures from daily and intraday data. You
will also learn how to estimate OLS and panel regressions using statsmodels.

**4.	Other topics**

In this block, you will be introduced briefly to other python packages that
can be helpful for research. The list of topics is not yet finalized, but
will likely include text analysis, web scraping, network analysis and
symbolic algebra.

Software
--------

I recommend the `Anaconda distribution <https://www.continuum.io/downloads>`__,
which is available for Windows, Mac OS and  Linux. We're using the Python
2.7 version for the bootcamp.


Material
--------

Slides
~~~~~~

- `Python for Financial Research (PDF) </bootcamp/PythonBootcampMarch2017.pdf>`__
- `Introduction to Web Scraping with Python (PDF) </bootcamp/WebScrapingPythonMarch2017.pdf>`__


Code
~~~~

**Note**: this code is for illustrative purpose, and does not necessarily show
the *correct* or *best* way to do something, the main goal is to illustrate
the Python language, its libraries and some common use cases in research.

**Block 1:**

- `PythonIntro.py </listings/bootcamp/PythonIntro.py.html>`__: Introduction to the Python language.
- `TurtleTutorial.py </listings/bootcamp/TurtleTutorial.py.html>`__: Some exercises with the turtle package.

**Block 2:**

- `Introduction to pandas </introduction-to-pandas/>`__: Short intro to pandas using Yahoo Finance data.
- `CRSP Example - Dividends </crsp-example-dividends/>`__: A quick event study around dividends announcements

**Block 3:**

- `Introduction to empirical market microstructure in Python </introduction-to-empirical-market-microstructure-in-python/>`__: Intro to using pandas with intraday data.
- `Estimating standard errors in Python </standard-errors-in-python/>`__: Using statsmodels and pandas for panel regressions.

**Block 4:**

- `Trump's tweets and the stock market </trump-tweets-and-the-stock-market/>`__: Merge and analyze twitter data, apply textual (sentiment) analysis and process intraday stock market data.
- `DownloadEdgar.py </listings/bootcamp/DownloadEdgar.py.html>`__: Batch downloading 10-Ks from EDGAR.
