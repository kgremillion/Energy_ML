# Machine Learning Meets Energy Share Prices
![Stock Market Image](Code/Resources/luis-rocha-3UyoEEZBUhQ-unsplash.jpg)


## Project Question:
### Do external and internal factors have an impact on the share price of Energy companies? If so, which factors are more important?

## Objective:
### Use statistical models & Machine Learning libraries to test the relationship between internal/external variables and Energy Company share prices.

## Project Summary:
A million-dollar question is what factors can be used to predict future share prices? Our humble attempt was to brainstorm what internal & external factors would most likely impact share prices of large Energy companies. Four factors for each were selected:

**Internal:** Revenue, Expenses, Divident Yield, & Cash Flow

**External:** US Interest Rate, US Unemployment Rate, Brent Oil Price, & LNG Price

We gathered quarterly data from the years 2005-2017 using Yahoo Finance, FRED, & Macrotrends websites. Data was gathered for 6 selected large energy companues: Exxon ( XOM ), BP, Equinor ( EQNR ), Chevron ( CVX ), Shell ( RDS-A ), & Total ( TOT ). This created a dataset of 312 records. 

We started by running a coefficient matrix to check that all variables were independent of each other. It was found that Expenses & Revenue were highly related, therefore we decided to drop Expenses to reduce bias in the dataset. 
![CorrMatrix](Code/Resources/download (1).png)
