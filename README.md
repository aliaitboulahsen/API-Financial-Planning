# Unit 5 - Financial Planning
## Background
You decided to start a FinTech consultancy firm, and you want to make a difference by working on projects with high social impact in local communities. You just won your first contract to help one of the biggest credit unions in your area. They want to create a tool that helps their members enhance their financial health. The Chief Technology Officer (CTO) of the credit union asked you to develop a prototype application to demo in the next credit union assembly.
The credit union board wants to allow the union's members to assess their monthly personal finances, and also be able to forecast a reasonably good retirement plan based on cryptocurrencies, stocks, and bonds.
In this homework activity, you will use all the skills you have learned until now - focusing on using APIs as part of the technical solution - to create two financial analysis tools.
The first will be a personal finance planner that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.
The second tool will be a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. You will then use the Monte Carlo data to calculate the expected portfolio returns given a specific initial investment amount.

## For this exercise, we would be leveraging two main learning objectives: APIs and Monte Carlo Simulation.
We will first use an Alpaca API to extract the price of Bitcoin and Ethereum to assess the value of our portfolio.
We will use an Alpaca API again to extract the prices of two stocks/bonds: AGG and SPY.
A pie chart will showcase the breadown of this portfolio composed of BTC, ETH, AGG and SPY and then assess if the overall portfolio meetings our emergency funds criteria.
In the last part of the exercise, we will pull historical data of AGG and SPY to conduct a Monte Carlo Simulation to analyze how the portfolio could be valued in 30 years.

Please refer to the code file in this repo for the full analysis.

Thank you! 
