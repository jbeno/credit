# credit
This is an analysis of the [Statlog (German Credit Data)](#https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data) from the UCI Machine Learning Repository. It was done as a project for the U.C. Berkeley Certificate in Machine Learning & Artificial Intelligence. The entire process is documented in this Jupyter notebook file:

* [credit.ipynb](credit.ipynb)

## Summary of Findings

Here are the key insights from my analysis:

* The majority of customers have a **"good" credit class** (70%)
* Almost all are **foreign workers!** (96.3%) I do believe this dataset came from Germany
* Most are **male** (69%) **skilled workers** (63%) that **own a home** (71.3%) and have just **1 dependent** (84.5%), themselves
* The **women are younger than the men**, with most between the ages of 20 and 30
* The most popular purpose is for a **Radio or TV** (28%), followed closely by a **new car** (23.4%)
* However, **Females** obtained a greater proportion of loans for **furniture/equipment, education, and domestic appliance** vs. males
* Most customers (60.3%) have a **Savings** with **less than 100 Deutsche Mark** (1 DEM = $0.55 USD)! No wonder they are applying for credit
* The **average credit amount** was 3,271 DEM ($1,825 USD)
* The **largest credit amount** was for the **Other** category or purpose (6,948 DEM median), followed by **Used Car** (4,788 DEM median)
* **Credit Amount vs. Duration** have the most positive correlation, which is strong at 0.62
* **Credit Amount vs. Installment Commitment** have the most negative correlation, which is weak at -0.27

## Helper Functions

As part of this project, I created some helper functions that are published here:

* [mytools.py](https://github.com/jbeno/mytools)
