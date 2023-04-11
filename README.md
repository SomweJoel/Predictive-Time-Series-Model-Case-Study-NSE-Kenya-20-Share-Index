# Predictive Time Series Model Case Study NSE Kenya 20 Share Index
### Team Members:

1. Whitney Ngili
2. Catherine Chelagat
3. Gibson Wanjau
4. Bella Somwe
5. George Mungai

![nse](https://user-images.githubusercontent.com/117165965/231267951-21958356-66c9-4028-84b0-0ae2cf4a05dc.jpg)

## Introduction

The Nairobi Securities Exchange (NSE) is the principal securities exchange of Kenya, providing a platform for the buying and selling of various financial instruments, including stocks, bonds, and derivatives. The NSE is a key player in the East African capital markets, attracting local and international investors who seek to capitalize on the investment opportunities presented by the growing Kenyan economy.

The NSE 20 Share Index, launched in 1953, is one of the most widely followed stock market indices in East Africa, comprising the top 20 blue-chip companies listed on the NSE. The index serves as a benchmark for the overall performance of the Kenyan stock market and provides investors with an indication of the market sentiment and direction.

With the advent of technology and the availability of vast amounts of financial data, investors are increasingly turning to quantitative analysis and machine learning techniques to predict stock prices and generate alpha. In this project, we aim to develop a predictive time series model to forecast the stock prices of companies listed in the NSE, using a range of market-specific factors as inputs.

Our target partners for this project include SACCOs, insurance companies, and pension funds, who are important players in the Kenyan financial market. By developing a reliable time series model to forecast stock prices, we hope to provide our partners with valuable insights that can inform their investment decisions and enable them to optimize their portfolio returns.

The project will involve collecting and analyzing historical stock prices and market-specific factors, exploring the various time series models available, and developing and evaluating the performance of the selected model. The results of the project could provide valuable insights into the dynamics of the Kenyan stock market and inform investment decisions by local and international investors.

## Problem Statement

The Nairobi Securities Exchange (NSE) is the main securities exchange in Kenya, providing a platform for trading a range of financial instruments including equities, bonds, and derivatives. The NSE Share 20 Index is an index of the 20 largest and most actively traded stocks on the NSE, designed to provide a benchmark for the performance of the Kenyan stock market.

The ability to predict stock prices is of great interest to investors, traders, and financial analysts, as it can help them make informed decisions about buying and selling securities. Accurate stock price predictions can also be useful for companies seeking to raise capital through stock offerings, as they can better understand the potential value of their shares.

The Breakfast Club Consultancy is committed to leveraging machine learning techniques to predict the stock prices of the NSE Share 20 Index. By analyzing historical data on stock prices, as well as other economic and financial indicators, models will be trained that can forecast future prices with a high degree of accuracy. The goal is to provide investors, traders, and financial analysts with a valuable tool for making more informed decisions about buying and selling securities on the NSE.

## Main Objective

To develop and deploy a predictive time series model that leverages machine learning techniques to accurately forecast the stock prices of the Kenya NSE 20 Share Index, taking into account market-specific factors and historical data.

## Specific Objectives

Develop and test machine learning models to identify the most significant market-specific factors that influence stock prices in the NSE.
Evaluate the performance of the machine learning models in predicting future stock prices and compare them with traditional forecasting methods.
Deploy the developed model online to provide easy access to our target partners, including SACCOs, insurance companies, and pension funds, who can use the model to inform their investment decisions.

## Data Understanding

The data used in this project was downloaded from here and CBK website.

The NSE 20 dataset contains 4531 rows and 6 columns with the following information:

No.	Column	Description
1	Date	Relevant date
2	Price	Average price of the stock
3	Open	Price at which the stock trades when an exchange opens for the day
4	High	Highest price the stock traded on that date
5	Low	Lowest price the stock traded on that date
6	Change %	Percentage change in stock price from the previous day

The data on exchange rate with the USD is downloaded from the investing website. It has 4729 rows and 6 columns with the columns having the same information as the NSE 20 dataset columns.

The datasets from the CBK website are on the specific macroeconomic factors affecting the prices of shares. The following datasets have been downloaded:

Inflation rates : This has 219 rows and contains the the percentage change in the monthly consumer price index (CPI).
Annual GDP : This has 23 rows and contains the Kenyan GDP from 2000-2021
Central Bank Rate : Data on this is found in two datasets, with one ranging from 2008-2023 and the other from 1991-2016. They contain the interest rate that the Central Bank of Kenya charges on loans to banks.
