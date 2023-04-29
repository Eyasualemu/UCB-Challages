# financial_planning_ch5
# Technology 
 These are the technologies the user can use to run the solution -- Jupyter notebook  -- Python -- Github -- To download the solution file. It's saved in githun as public
Test Data 
Crypto btc_url = "https://api.alternative.me/v2/ticker/Bitcoin/?convert=USD"
Crypto eth_url = "https://api.alternative.me/v2/ticker/Ethereum/?convert=USD"
Stock and bond data from Alpaca
 # Contributors 
 The solution is developed by Eyasu Alemu LinkdIn account -- https://www.linkedin.com/in/eyasu-a-684854112 Email -- Bekaqa01@gmail.com Phone Number -- 202 344 0733



Using the starter code file and the provided CSV files, complete the following steps.

1: Create a Financial Planner for Emergencies
    
Evaluate the Cryptocurrency Wallet by Using the Requests Library : The current value of a member’s cryptocurrency wallet collected the current prices for the    Bitcoin and Ethereum cryptocurrencies by using the Python Requests library. For the prototype,the assume is the member holds the 1.2 Bitcoins (BTC) The code gives total crypto wallet. 

Evaluate the Stock and Bond Holdings by Using the Alpaca SDK : The solution determine the current value of a member’s stock and bond holdings. To get the data You’ll make an API call to Alpaca via the Alpaca SDK to get the current closing prices of the SPDR S&P 500 ETF Trust (ticker: SPY) and of the iShares Core US Aggregate Bond ETF (ticker: AGG). For the prototype, assume that the member holds 110 shares of SPY, which represents the stock portion of their portfolio, and 200 shares of AGG, which represents the bond portion. 

Evaluate the Emergency Fund : The solution uses the valuations for the cryptocurrency wallet and for the stock and bond portions of the portfolio to determine if the credit union member has enough savings to build an emergency fund into their financial plan. 

<img width="392" alt="image" src="https://user-images.githubusercontent.com/44585226/233878151-6008b885-0d42-4eb0-aa7f-5ed39e4096a2.png">


2. Create a Financial Planner for Retirement

Create the Monte Carlo Simulation

    <img width="597" alt="image" src="https://user-images.githubusercontent.com/44585226/233878220-3560f2bc-9b5b-447e-9688-f71814794c64.png">

   <img width="473" alt="image" src="https://user-images.githubusercontent.com/44585226/233878316-814eb821-4ce6-41a9-b1ff-7b7b510b74d9.png">
   
Analyze the Retirement Portfolio Forecasts : There is a 95% chance that an investment of $60688.7 in the portfolio over the next 30 years will end within the range of $160658.78 and $2645777.61.
 
Forecast Cumulative Returns in 10 Years

![image](https://user-images.githubusercontent.com/44585226/233878403-8dcb1055-df7a-4b0f-84f3-6bd0c1baf3f2.png)

![image](https://user-images.githubusercontent.com/44585226/233878428-91160577-4299-42a1-bb0c-977994917536.png)

There is a 95% chance that an investment of $60688.7 in the portfolio over the next 10 years will end within the range of $51103.45 and $447686.94.


