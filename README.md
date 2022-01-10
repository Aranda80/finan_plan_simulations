![Loan Finder App](images/financial_planning.png)

# Financial Planning with APIs and Simulations

This program provides two financial tools, a financial planner for emergencies and another one to prepare for retirement. 

- Financial planner for emergencies: The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

- Financial planner for retirement: This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

## Technologies

This application uses python 3.7.11 and the following packages:

* ** requests

* ** json

* ** pandas

* ** alpaca_trade_api

* ** MCForecastTools

## Instructions

Prior to running the program, you need to create an environment file (`.env`) to store the values of your Alpaca API key and Alpaca secret key.

## Financial planner for emergencies

This tool analysis and evaluates if the member's current holdings of stocks, bonds and cryptocurrencies have met the emergency fund threshold of 3 times the current monthly salary. 

## Financial planner for retirement

This tool analysis and evaluates a 30 and a 10 year forecast of investment returns of the stock and bond portfolio. 

## Contributors

Jaime Aranda


---

## License

Licensed under the MIT License.
