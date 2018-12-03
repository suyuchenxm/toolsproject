# Finance SuperMAN

### Purpose
  - The purpose of our project is to offer user with the most relevent and latest financial information related to a stock.


### Prerequest packages

Our project needs following packages for normal operation


* [bs4] 
* [datetime]
* [request] 
* [matplotlib]
* [mpl_finance]
* [numpy]
* [pandas] 
* [pylab] 
* [statsmodels.api]
* [yahoo_fin]

For easier installation, you may run the following bash command to run all the installation
```sh
$ pip install bs4
$ pip install datetime
$ pip install request
$ pip install matplotlib
$ pip install mpl_finance
$ pip install numpy
$ pip install pandas
$ pip install pylab
$ pip install statsmodels.api
$ pip install yahoo_fin
```
### Users instruction
    By using our project, user can simply open the "final version "
    
    
### Function Button

To run our project, you will need to enter an ticker in the interface. Then you will be prompted to choose the information you would like to access with the following buttons. A detail description of what the following buttons do is below:



Stock Basic Information

- This button will provide you with a summary about what the company does. In addition to the basic summary information, you will also be provided with the latest news related to this company. You can access those news by clicking the urls below the news title



Competitor Analysis:

- This button will give you a table with the stock itself and four of the most close competitiors. The information included in the table are 'Price','Market Cap (intraday)','Enterprise Value','Operating Margin','Quarterly Revenue Growth','Quarterly Earnings Growth','Diluted EPS','Trailing Annual Dividend Yield','5 Year Average Dividend Yield','Payout Ratio','Trailing P/E','Forward P/E','PEG Ratio (5 yr expected)','Return on Equity','Total Debt/Equity','Book Value Per Share','Beta (3Y Monthly)'



Stock Analyst Expectations

-	This button will provide you with the latest stock analysts' expectation for the stock you are interested in. This is forward predicted information from various analysts.

View Expected Returns

- This button will plot the expected return against the standard deviation for the company of your choice and it's competitors. This will give insight to whether the return is stable in comparison to the competitors



Key Technical Plot

- This button will show you plots of the key technical information. The first plot in this button is a plots of the moving averages plotted against the stock price. The second plot in this button is the trading volume for the stock. The third plot is MACD plot for the stock



Competitor Correlation Table
- This button will display a table of correlation for the stock of your choice and its competitors. This tells how correlated your stock is to its competitors.



Stock Performance against S&P 500

- In this button you will be provided with a fitted plot of the stock of your interest against the S&P 500. In addition, you will also be provided with an linear regression plot of S&P 500 price regress on your stock price.


Sector Analysis

- In this button you will be able to access the sector information of the stock you are interested in. The sector information is displayed together with all other sectors for easy comparison.



Competitor Performance against S&P 500
- This button will show a plot of the closest competitor's price against the performance of S&P 500. 

### User instruction
        In order to use our project, users can simply open the file "two pages changeable interface.ipynb" and run it by jupyter notebook. Then there will appear an interface that ask users to enter the ticker that they want to analysis. Finally, users can choose any of 9 buttons and the results will display in notebook correspondingly.


