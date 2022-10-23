# Leading World Currency Impacts

## Objective: 

Calculating the variance of different world leading currencies and highlight events with visualization using USD as the baseline. 

---

## Purpose:

This will help financial institutions predict the outcome of certain currency moves based on historical data and lead them to better manage their funds and risk.  

---

## Background:

Analysis of trends and history is essential in order to gather a meaningful interpretation of events. In foreign currency investment, variance analysis in relation to the USD reveals insightful information about trends in foreign currency. Variance, or exchange rate variance as it applies to this project, was used as it indicates the cost to exchange one currency for another. For buyers of foreign currency, a higher variance is advantageous since each dollar converted yields a greater amount of the foreign currency. 

Aside from variance, interest rate information on these currencies are important to understand as well. Higher interest rates for instance can cause the exchange rate to rise since it would attract foreign capital. 

USD as Baseline: Currencies in the forex market have typically been traded against the USD since near the end of WWII. A primary motivation for this at the time was that the US was essentially the only major nation to come out of the war economically strong. Since then, the USD has traditionally been used as a backbone for forex. 

---

## Data: 

Through websites like "Kaggle.com" and "Worldbank.org", our group pulled data exchange rate data for 16 currencies. Data was collected from 1950 to 2022 for all currencies except the Russian Ruble and the EU Euro (which began in 1993 and 1995 respectively). 

---

## Installations: 

Monte Carlo (MC) - The simulation is used to determine total possible outcomes when there exists a potential for random variables influencing the outcomes. 

Pandas - Software library used for data analysis and manipulation.

hvplot - Offers high-level plotting for APIs. 

Numpy - Library used for working with arrays. 



---


## Project Visuals:

<img width="641" alt="Screen Shot 2022-10-22 at 9 25 00 AM" src="https://user-images.githubusercontent.com/111773401/197361545-b5099e8a-53b6-473b-b453-2a1af112aff1.png">

<img width="646" alt="Screen Shot 2022-10-22 at 1 40 15 PM" src="https://user-images.githubusercontent.com/111773401/197361570-761080fe-dba5-4280-9b8f-dc36aae50914.png">

The above graphs reveal each currency's "delta", thus revealing the currencies' values over time. 

## Barriers, API, and CSV

API Issues - Issues with usage, CSV used instead for models

CSV vs API - Both are used to important information. CSV - useful for storing small, manageable data sets i.e. data that can go on a typical spreadsheet. API - Has two systems communicate to allow for the sharing of data set. APIs can be fast and efficient, and are useful live. 

Overcoming - We reached out to AskBCS, Tutors, and TA's to promptly address obstacles.

## Analysis Summary: 

Our graphing of the chosen currencies in relation to the USD have allowed us to notice key 
events in the data. Based on the events researched we have determined three predictors: 
1) War 
2) Political
3) Financial 

The usage of “war” as a predictor is straightforward, and the relationship between war and involved countries’ economic standing has been understood for some time. The “political” predictor refers to regime change, coups, major political unrest, etc. It is understood that as political turmoil increases, higher interest rates may result, which in turn can lower a currency’s exchange rate value. The final “financial” predictor includes bailouts, huge trade deficits, IMF devaluation and speculation, and so on. Beyond these general predictors, it is important to note that other factors may also be influential and consequently worth examining as well. 


## Next Steps:

Beyond the project, other factors we can look into include inflation rate, debt, and economic stability. 

