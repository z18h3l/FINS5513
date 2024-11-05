java c
TERM PROJECT FINS5513 
Markowitz and SIM-Based Portfolio Optimisation 
TERM PROJECT SUMMARY 
The Term Project has 2 parts:
Part A – Portfolio construction using Markowitz optimisation (Excel)
Part B – Portfolio construction using SIM-based optimisation (Excel)
Each of the parts are described below.  Please attempt ALL parts.
AFTER READING THESE INSTRUCTIONS, PLEASE WATCH THE “TERM PROJECT DEMONSTRATION” ON MOODLE.
PART A: 5 STOCK MARKOWITZ OPTIMISATION 
A1 Allocated Stocks You are evaluating a portfolio of 5 U.S. equities drawn from the SP500. The five allocated stocks are randomly drawn and are unique to you. Each student will have a different combination of stocks. Your allocated stocks will be emailed to you from bankfinexams@unsw.edu.au. You will receive this email shortly, and an announcement will be made when it has been sent. Once the email is sent, please check your junk file and all other inboxes. If you cannot find it, please email robert.bishop@unsw.edu.au.The allocated stocks used in the Term Project demonstration are an EXAMPLE only (because your allocated stocks will be different).    The five stocks used in the Term Project demonstration have the FactSet identifiers (i) APPL-US, (ii) DIS-US, (iii) GS-US, (iv) JNJ-US, and (v) V-US.
A2 Data Download and Validation 
For the period from January 2014 through December 2018, download the monthly returns for each stock in your portfolio from FactSet (60 observations). All returns should be inclusive of dividends
- in the FactSet dropdown box "Total Return" select "% Return."
We will first verify that you have downloaded the correct data for your assigned companies and that you are able to correctly compute some basic statistics.
Given that you can multiply monthly average returns by 12 to annualise them, what is the average annualised return for...QA1. ...Stock 1?QA2. ...Stock 2?QA3. ...Stock 3?QA4. ...Stock 4?QA5. ...Stock 5?Given that you can multiply monthly standard deviations by √ 12 to annualise them, what is the annualised standard deviation of monthly returns for... QA6. ... Stock 1?QA7. ... Stock 2?QA8. ... Stock 3?QA9. ... Stock 4?QA10...Stock 5?
Before you continue, please check whether you have downloaded the data correctly from FactSet by opening the Excel file “FactSet Download Check” on Moodle. Search for your zID (use the Excel Home menu, go to the magnifying glass, select Find, and then enter your zID). Check that the answers for QA1-10 that you have derived above are equal with the answers provided in the Excel file for QA1-10 to 5 decimal places (there may be small differences beyond 5 decimal places).  If they do not, do not proceed as it means you have downloaded the data incorrectly from Factset. Go back and try downloading the data again, following these instructions exactly. If your answers for QA1-10 do match those in the Excel file (to 5 decimal places), enter them in the Quiz QA1-10, and proceed with the following questions. 
Given that you can multiply the covariances of monthly returns by 12 to annualise them, what is the annualised covariance of monthly returns between...
QA11. ... Stock 1 and Stock 2 (Example: APPL-US and DIS-US)?
QA12. ... Stock 3 and Stock 4 (Example: GS-US and JNJ-US)?
QA13. ... Stock 1 and Stock 5 (Example: APPL-US and V-US)?
A3 Efficient Frontier 
Now we will proceed to portfolio optimisation.
We will firstly derive the Minimum Variance Frontier (MVF) using the Solver tool in Excel.
MVF: For a portfolio constructed from your assigned securities, find the portfolio weightings that would minimise its annualised standard deviation/variance of returns at each expected annual portfolio return level between 0% and 30% (in increments of 10%).
What is the minimum attainable standard deviation of annual returns for...
QA14. ... an expected return level of 0%?
QA15. ... an expected return level of 10%?
QA16. ... an expected return level of 20%?
QA17. ... an expected return level of 30%?
Next, we will  derive the portfolio weightings  for the Global  Minimum  Variance  Portfolio (GMVP) – the portfolio weightings that result in the portfolio having the lowest possible variance (without any constraint on expected portfolio return) – by using Solver.
GMVP: What is the GMVP portfolio weight in ...QA18. ... Stock 1QA19. ... Stock 3QA20. ... Stock 5
Compute the annualised expected return and annualised standard deviation of the GMVP. What is its ...
QA21. ... annualised expected return?
QA22. ... annualised standard deviation?
Now, we can derive the Efficient Frontier by discarding any portfolio that is inefficient (that is, any portfolio on the MVF that has a return lower than the GMVP)
A4     Capital Allocation Line and the Optimal Risky Portfolio P* 
Use a risk-free rate of 3.00% APR (i.e., fixed at 0.25% monthly) for all parts of this task. 
The Optimal Risky Portfolio (P+) is the point on the Efficient Frontier that has the highest possible Sharpe Ratio. We will derive the portfolio weightings for P* by using Solver.
P*: What is the portfolio weight in P+ of ...QA23. ... Stock 1QA24. ... Stock 3QA25. ... Stock 5
Compute the annualised expected return and annualised standard deviation for P*. What is its ...
QA26. ... annualised expected return?
QA27. ... annualised standard deviation?
Now, we can derive the Capital Allocation Line (CAL) by joining the risk-free rate (the y- intercept) with P* in a linear line.  (Note: this should be tangent to your efficient frontier – if it is not, then extend your efficient frontier target level expected returns beyond 30% until you have at least one return level greater than the P* expected return and they should now be tangent to each other).
A5 Optimal Complete Portfolio 
Assume the optimal allocation to risky assets y ∗ for an investor is given by:
y ∗ = E (rp∗) − rf 
A × σp(2)∗ 
The Optimal Complete Portfolio (C*) is the portfolio combination of risky assets (composed of P*) and risk-free assets that provides an investor the highest possible utility, given their level of risk aversion. We can determine an investor’s risk aversion if we have information on C*.
QA28. What is the risk aversion coefficient, A, for Investor I, who invests on the CAL and whose optimal allocation to risky assets (y∗ ) is 100%?
QA29. What is investor I’s Optimal Complete Portfolio Sharpe Ratio?
C*: Investor J’s Optimal Complete Portfolio has an annualised standard deviation of 10% and is located on the CAL.  What is Investor J’s …
QA30. … optimal allocation to risky assets y∗ ?
QA31. … risk aversion coefficient, A 
QA32. … Optimal Complete Portfolio annualised expected return?
QA33. … Optimal Complete Portfolio annua代 写FINS5513 Markowitz and SIM-Based Portfolio OptimisationR
代做程序编程语言lised Sharpe ratio?
QA34. … Optimal Complete Portfolio utility score - using the conventional utility function:
Uc = E(rc*) - 2/1Aσp(2)∗ 
GRAPHSPARTA - OPTIONAL QUESTIONS 
You  are  not required to complete these graphs but they are an excellent learning opportunity 
In your Excel spreadsheet: 
a)   Plot the Minimum Variance Frontier (MVF) for all target annualised expected returns between 0% and 30% in increments of 10%, and clearly label it. 
b)   Plot the Efficient Frontier and clearly label it. 
c)   Plot the Capital Allocation Line (CAL), showing where it intersects the y-axis and the efficient frontier and clearly label it. 
d)   Plot investor J ’s indifference curve at the utility score derived in QA34, with the Capital Allocation Line and efficient frontier overlaid, and showing C* as the point of tangency between the indifference curve and the CAL. 
PART B: 10 STOCK MARKOWITZ AND SIM-BASED OPTIMISATION 
B1 Allocated Stocks - 10 Stock Portfolio 
Now, please add the following 5 stocks to your portfolio: (vi) HD-US, (vii) IBM-US, (viii) JPM-US, (ix) WMT-US (x) CVX-US.  You should now have 10 stocks in your portfolio with no duplicates.
B2     Data Download and Basic Portfolio Statistics 
For the period from January 2014 through December 2018, download from FactSet the monthly returns (inclusive of dividends) for each of the 5 new stocks that you have been assigned above (60 observations). Combine this new data with the data you have downloaded for your previously allocated 5 stocks so that you have a spreadsheet covering 10 stocks.
For the period from January 2014 through December 2018, download from FactSet the monthly returns for the SP 500 Index (FactSet identifier: SP50) (60 observations).
All returns should be total returns inclusive of dividends - in the FactSet dropdown box "Total Return" select "% Return.". For the SP500 "Total Return", select "% Return (Gross, Unhedged)"
Compute the annualised average return, standard deviation and variance for each stock.
Compute the annualised average return, standard deviation and variance for the SP 500.
B3 Markowitz Portfolio Optimisation 10 Stocks 
B3.1 Global Minimum Variance Portfolio Under Markowitz Derive the 10-stock sample variance-covariance matrix using any method demonstrated in Part A.
For the portfolio without any position-size constraints (long/short portfolio), identify the Global Minimum Variance Portfolio (GMVP). What is its ...
QB1. ... annualised expected return?
QB2. ... annualised standard deviation?
For the portfolio with the constraint that no stock can be shorted (long only portfolio), identify the Global Minimum Variance Portfolio (GMVP). What is its ...
QB3. ... annualised expected return?
QB4. ... annualised standard deviation?
B3.2     Optimal Risky Portfolio P* Under Markowitz 
For  the  portfolio without  any  position-size  constraints  (long/short portfolio),  identify  the Optimal Risky Portfolio (P*). What is its ...
QB5. ... annualised expected return?
QB6. ... annualised standard deviation?
For the portfolio with the constraint that no stock can be shorted (long only portfolio), identify the Optimal Risky Portfolio (P*). What is its ...
QB7. ... annualised expected return?
QB8. ... annualised standard deviation?
B4     Single Index Model (SIM) Portfolio Optimisation 10 Stocks 
B4.1 Derive Excess Returns 
For each stock in your portfolio, calculate monthly excess return: Rit  = rit − rf  where rit   is the return on stock i for month t, and rf  is the risk-free rate. (Make sure you use the fixed monthly risk- free rate given above). Compute the annualised average excess return for each stock in your portfolio over the sample period.
For the SP 500 index, calculate monthly excess return: R Mt   = rMt − rf  where,rMt  is the return on the SP 500 for month t. Compute the annualised average excess return for the SP 500 over the sample period.
B4.2 Single Index Model (SIM) Regression 
Estimate the SIM beta βi, for each stock in your portfolio using the regression equation:
Rit  = α i  + βiR Mt  + εit  
QB9. What was the highest beta out of your 10 stocks? 
QB10. What was the lowest beta out of your 10 stocks (including negative values)?
B4.3 SIM Variance-Covariance Matrix 
Calculate the variance-covariance matrix for your 10-stock portfolio using these SIM estimates.
For the matrix diagonal, simply use the individual variances for each stock σi2  derived in B2.
For the off-diagonal covariances, assume no residual covariance between stocks (the standard assumption of the SIM), and apply the following equation:
Cov(ri , rj) = βi βj σM(2)                for all i, j, … .n  = 10 stocks
B4.4     Global Minimum Variance Portfolio and Optimal Risky Portfolio Under SIM 
Use the (already annualised) sample variance-covariance matrix  derived in B4.3  for all  SIM optimisations.
For the portfolio without any position-size constraints (long/short portfolio), identify the Global Minimum Variance Portfolio (GMVP) under the SIM. What is its ...
QB11. ... annualised expected return?
QB12. ... annualised standard deviation?
For the portfolio with the constraint that no stock can be shorted (long only portfolio), identify the Global Minimum Variance Portfolio (GMVP) under the SIM. What is its ...
QB13. ... annualised expected return?
QB14. ... annualised standard deviation?
For  the  portfolio without  any  position-size  constraints  (long/short portfolio),  identify  the Optimal Risky Portfolio (P*) under the SIM. What is its ...
QB15. ... annualised expected return?
QB16. ... annualised standard deviation?
For the portfolio with the constraint that no stock can be shorted (long only portfolio), identify the Optimal Risky Portfolio (P*) under the SIM. What is its ...
QB17. ... annualised expected return?
QB18. ... annualised standard deviation?
GRAPHS PART B - OPTIONAL QUESTIONS 
You  are  not required to complete these graphs but they are an excellent learning opportunity 
In your Excel spreadsheet: 
e)   For the 10-stock Markowitz portfolio  without any position-size constraints only, derive the Minimum Variance Frontier (MVF) for all target annualised expected returns between 0% and 30% in increments of 10%, and clearly label it. 
f) For the 10-stock Markowitz portfolio without any position-size constraints only, plot the Efficient Frontier and clearly label it. 
g)   For the 10-stock Markowitz portfolio without any position-size constraints only, plot the Capital Allocation Line (CAL) showing where it intersects they-axis and the efficient frontier, and clearly label it. 



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
