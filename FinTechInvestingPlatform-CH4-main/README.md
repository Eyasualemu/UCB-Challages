# FinTechInvestingPlatform-CH4

# Technology 
 These are the technologies the user can use to run the solution -- Jupyter notebook  -- Python -- CSV file reader -- Github -- To download the solution file. It's saved in githun as public

 # Contributors 
 The solution is developed by Eyasu Alemu LinkdIn account -- https://www.linkedin.com/in/eyasu-a-684854112 Email -- Bekaqa01@gmail.com Phone Number -- 202 344 0733

## # FinTechInvestingPlatform_ch4 Instructions and high level report 

Using the starter code file and the provided CSV files, complete the following steps.

1. Import the required libraries and dependencies. 

2. Set paths to the CSV files by creating a `path` object for each CSV file path. Each CSV file contains a stock's closing price and the date of the closing price.
    
3. Use the Pandas `pct_change` function together with `dropna` to create the daily returns DataFrame.
![image](https://user-images.githubusercontent.com/44585226/232368233-d66db76e-a89a-45ab-8c16-e1ff75107f5a.png)


4. Plot the daily return data of the 4 funds and the S&P 500 
![image](https://user-images.githubusercontent.com/44585226/232368276-4df275ec-ec63-4f2b-bd88-6ce80958da1f.png)


5. Calculate and plot the cumulative returns of the 4 fund portfolios and the S&P 500
![image](https://user-images.githubusercontent.com/44585226/232368339-98eb8f6d-8b6f-4c29-b1ee-4cf8e7cea17a.png)

6. Analyze the volatility by using the plot box 
![image](https://user-images.githubusercontent.com/44585226/232368398-ab294099-e423-4702-a372-93b085bbc4ca.png)

7. Analyze the risk by using Daily and Annualized standard deviation 
8. Calculate the standard deviation by using  the daily returns DataFrame and a 21-day rolling window,
![image](https://user-images.githubusercontent.com/44585226/232368507-a05cce4b-dbb0-41fb-8ec0-2ab14ba526c6.png)

9. Analyzing the risk return profit by using the sharp ratio and bar graph 

BERKSHIRE HATHAWAY INC portfolios offers the best risk-return profile and PAULSON & CO.INC.offers the worst

![image](https://user-images.githubusercontent.com/44585226/232368609-c61d029d-e595-4ce6-a5ea-2444e04b515b.png)

10. Verify the portfolio diversity by calculating the beta and comparing to S&P 500
    
Based on the calculation BERKSHIRE HATHAWAY INC seem more sensitive to movements in the S&P 500. If you see the beta mean for BERKSHIRE HATHAWAY INC it's way higher than TIGER GLOBAL MANAGEMENT LLC
BERKSHIRE HATHAWAY INC beta mean = 0.2214986101354593

TIGER GLOBAL MANAGEMENT LLC beta mean = 0.03093001487238774

Since TIGER GLOBAL MANAGEMENT LLC is less sensitive to movements in the S&P 500 i recommend for inclusion in my firm’s suite of fund offerings

![image](https://user-images.githubusercontent.com/44585226/232368770-247a7945-cdab-4bc9-87d4-04347448e41a.png)
![image](https://user-images.githubusercontent.com/44585226/232368809-76180085-eebc-40a9-96b1-aa8dce198b13.png)


