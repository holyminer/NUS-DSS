# Methodology

Motivation of study:
Research has shown that there are already a number of new diseases that could potentially develop into the next pandemic. Covid-19 has brought about severe consequences to the economy but also opportunities in the stock market, and by learning from this, future opportunities can be seized when the next pandemic strikes. We learn by validating analyst reports with a focus on Morningstar and Yahoo Finance as other analyst reports such as from Bloomberg and The Economist are either paid-to-access or too general.  

Data: 
Historical daily stock data from Yahoo Finance from 2 Jan 2020 - 30 Apr 2021 with a total of 334 trading days. The 'Close' price is taken as it is considered the most accurate valuation of a stock.  

Methodology:
Firstly, a prediction regarding UBER and LYFT by Morningstar is verified. Morningstar predicts that ‘Recovery will take until 2021’.

Assumption: Recovery is taken to be pre-covid levels (defined as highest price of stock between Jan-Feb 2020 which was just before Covid-19).

Result: Prediction was partially correct as UBER recovered by 5 Nov 2020 while LYFT recovered by 10 Feb 2021.

Secondly, the study tests the validity of the fair value estimate by Morningstar. The fair value is the long term intrinsic value of a stock, calculated by discounting future cash flows of the company. Test for 18 companies to see if they reach the fair value estimate. If the fair value is higher than the current price, the strategy is to buy the stock and sell when it reaches its fair value, and vice versa if the fair value is lower than the current price. 
Caveat: The fair value estimate is usually a paid feature, but Morningstar released the fair value estimate for 18 companies during Covid-19 in 2020 for free. 

Result: 10/18 companies reached their fair value. However this is an underestimation as 4/8 companies which did not reach fair value came very close to reaching it (plus minus 10% of the fair value), and 2 companies which did not reach their fair value were tested with data for less than a year when they could have reached the fair value if given a longer time. 
Average profit was 86% in 216 days.

Thirdly, Yahoo Finance recommendations were analysed. They consist of ratings assigned to a stock by investment firms, which include 'buy', 'hold', 'sell' etc which were grouped into 3 categories (Buy, Neutral, Sell). Test for the top 30 companies in terms of market cap in the S&P 500 IT (ETF consisting of companies from S&P 500 in the IT sector). 
Hypothesis: More neutral/sell than buy recommendations → less demand → longer time to recover to pre-covid level

Result: 7/30 firms with more neutral and sell recommendations than buy recommendations. 4/30 firms did not reach pre-covid price, and 2 of the 4 firms have more neutral/sell than buy recommendations. 

4 months longer on average for firms with more neutral/sell than buy recommendations to recover to pre-covid/max price. 

This shows that Yahoo finance recommendations are associated with stock recovery. 


Conclusion:
This study mostly validates analyst reports by stock recovery - measuring how long and if a stock recovers to its pre-covid price within a specific time horizon (2 Jan 2020 - 30 Apr 2021), and whether stocks reach their fair value estimate determined by Morningstar. 
The predictions by Morningstar are mostly accurate, with stock recovery of UBER and LYFT being partially correct and the fair value estimate having an accuracy of 10/18 although this is an underestimation. Yahoo Finance recommendations were also associated with stock recovery, with stocks that have more neutral/sell than buy recommendations taking a longer time to recover and reach their pre-covid price.

If you want analyst reports which are free and mostly accurate, Morningstar and Yahoo Finance fit the bill, while other analyst reports are either too general or require a subscription fee. 
