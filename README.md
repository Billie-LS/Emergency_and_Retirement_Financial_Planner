# **Columbia University Engineering, New York FinTech BootCamp** 
# **August 2022 Cohort**
## *Module 5, Challenge - Portfolio key risk management metrics & analysis*
### example analysis of key metrics: daily returns, standard deviations, Sharpe ratios, and betas




The purpose of this project was to assume the role of a quantitative analyst for a FinTech investing platform. The task at hand is to offer clients a one-stop online investment solution for their retirement portfolios that’s both inexpensive and high quality.

The goal is to systematically evaluate four new investment options (funds) for possible inclusion in the client portfolios. In so doing, determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

Beyond the scope of the assignment, the author sought to conduct additional analysis of the data obtained and demonstrate further visualization with combined data plots, overlay plots, and heatmap visualization.  Supplemental and/or extra analysis beyond the scope of the project is noted as 'supplemental' were approrpiate. 

---
## **Methods**

The code script analysis performed:








            
   SUPPLEMENTAL ANALYSIS was then introduced by the author.
   The `corr` function was used to calculate correlations for each fund pair.
   The `heatmap` function from the Seaborn library was used to create a heatmap of correlation values visualization.
   
![all_dataframes_htmap](Images/htmaps.png)    
   
   
   
   Additional information about the heatmap method from seaborn on the [documentation page](https://seaborn.pydata.org/generated/seaborn.heatmap.html#seaborn.heatmap).






# Emergency_and_Retirement_Financial_Planner
Financial planner for emergencies; use this tool to visualize current savings.  Financial planner for retirement; forecast retirement portfolio's 30 year performance.









---
## **Technologies**
---
### **Dependencies**

This project leverages Jupyter Lab v3.4.4 and python v3.7 with the following packages:

* [os](https://docs.python.org/3/library/os.html) - provides a portable way of using operating system dependent functionality.

* [getenv](https://docs.python.org/3/library/os.html?highlight=os%20getenv#os.getenv) - From os, return the value of the environment variable key if it exists, or default if it doesn’t.

* [requests](https://requests.readthedocs.io/en/latest/) - an elegant and simple HTTP library for Python, allows you to send HTTP/1.1 requests extremely easily.

* [json](https://docs.python.org/3/library/json.html?highlight=json) - JavaScript Object Notation, is a lightweight data interchange format inspired by JavaScript object literal syntax 

* [pandas](https://pandas.pydata.org/docs/) - Software library written for the Python programming language for data manipulation and analysis.

* [Timestamp](https://pandas.pydata.org/docs/reference/api/pandas.Timestamp.html) - From 'pandas', equivalent of python’s Datetime, used for the entries that make up a DatetimeIndex, and other timeseries oriented data structures in pandas.

* [concat](https://pandas.pydata.org/docs/reference/api/pandas.concat.html) - From 'pandas', concatenate pandas objects along a particular axis, allows optional set logic along the other axes.

* [Dataframe](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html) - From 'pandas', data structure also contains labeled axes (rows and columns). Arithmetic operations align on both row and column labels. Can be thought of as a dict-like container for Series objects. The primary pandas data structure.

* [numpy](https://numpy.org/doc/stable/) - Software library, NumPy is the fundamental package for scientific computing in Python, provides vast functionality.

* [timedelta](https://numpy.org/doc/stable/reference/arrays.datetime.html) - From NumPy, from datetime, allows the subtraction of two datetime values, an operation which produces a number with a time unit.

* [dot_env](https://pypi.org/project/python-dotenv/) - Python-dotenv reads key-value pairs from a .env file and can set them as environment variables.

* [alpaca-trade-api](https://pypi.org/project/alpaca-trade-api/0.29/) - a python library for the Alpaca trade API. It allows rapid trading algo development easily, with support for the both REST and streaming interfaces.

* [MCForecastTools]- A Python classroom provided application/script for runnning Monte Carlo simulation on portfolio price data

For additional and / or supplemental processing and visulaization this project also makes use of the following packages:

* [matplotlib.pyplot](https://matplotlib.org/stable/tutorials/introductory/pyplot.html) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python; matplotlib.pyplot is a collection of functions that make matplotlib work like MATLAB.

* [seaborn](https://seaborn.pydata.org/tutorial/introduction) - Software library for making statistical graphics in Python. It builds on top of matplotlib and integrates closely with pandas data structures.



### **Hardware used for development**

MacBook Pro (16-inch, 2021)

    Chip Appple M1 Max
    macOS Monterey version 12.5.1

### **Development Software**

Homebrew 3.5.10

    Homebrew/homebrew-core (git revision 0b6b6d9004e; last commit 2022-08-30)
    Homebrew/homebrew-cask (git revision 63ae652861; last commit 2022-08-30)

anaconda Command line client 1.10.0

    conda 4.13.0
    Python 3.7.13

pip 22.1.2 from /opt/anaconda3/envs/dev/lib/python3.7/site-packages/pip (python 3.7)


git version 2.37.2

---
## *Installation of application (i.e. github clone)*

 In the terminal, navigate to directory where you want to install this application from the repository and enter the following command

```python
git clone git@github.com:Billie-LS/Emergency_and_Retirement_Financial_Planner.git
```

---
## **Usage**

From terminal, the installed application is run through jupyter lab web-based interactive development environment (IDE) interface by typing at prompt:

```python
  > jupyter lab
```

---
## **Project requirements**
### see starter code

---
## **Version control**

Version control can be reviewed at:

```python
https://github.com/Billie-LS/Emergency_and_Retirement_Financial_Planner
```

[repository](https://github.com/Billie-LS/Emergency_and_Retirement_Financial_Planner)


---
## **Contributors**

### **Author**

Loki 'billie' Skylizard
    [LinkedIn](https://www.linkedin.com/in/l-s-6a0316244)
    [@GitHub](https://github.com/Billie-LS)


### **BootCamp lead instructor**

Vinicio De Sola
    [@GitHub](https://github.com/penpen86)


### **BootCamp teaching assistants**

Corey Recai

Santiago Pedemonte
    [@GitHub](https://github.com/Santiago-Pedemonte)


### **askBCS assistants**

Vijaya Reddy
    [LinkedIn](https://www.linkedin.com/in/vijaya-reddy-209b041a3/)

Mounika Mamindla
    [LinkedIn](https://www.linkedin.com/in/mounika-mamindla/)


### **GitHub inspiration - dynamic and/or current date formatting ideas**


endie5 
    [@GitHub](https://github.com/endie5/Challenge5)


### **Additional references**


[SparkByExamples.com](https://sparkbyexamples.com/pandas/pandas-drop-a-level-from-a-multi-level-column-index/)

[W3Schools](https://www.w3schools.com/python/python_dictionaries.asp)

[Geeks for Geeks](https://www.geeksforgeeks.org/get-yesterdays-date-using-python/)

[pandas.to_datetime documentation](https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html)

[Numpy Datetimes and Timedeltas](https://numpy.org/doc/stable/reference/arrays.datetime.html)

---
## **License**

MIT License

Copyright (c) [2022] [Loki 'billie' Skylizard]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


