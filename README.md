# Finance-and-Risk-Analytics


EXECUTIVE SUMMARY
 The objective of this project is to create an Indian credit risk(default) model, using the data provided. There are two machine learning models – Logistic Regression and Random Forest classifier models have been used to predict the defaulter in this project.

INTRODUCTION
Though the main objective of the project is to build an Indian credit risk(default) model, various steps have been taken before the same model. First, the given dataset was imported using pandas library and preprocessing steps such as missing value treatment, outlier treatment, descriptive analysis, graphical representations of the features are done. With all these preprocessing a better cleaner data is obtained and is used for training and testing the model built. Logistic Regression and Random Forest Classifier are the two models built and results are evaluated through metrics such as accuracy score, classification report, confusion matrix and roc_auc curve.

DATA DESCRIPTION

The below are the features present in the dataset and its description.


1.Networth Next Year - Net worth of the customer in next year.

2. Total assets	- Total assets of customer.

3.Net worth	- Net worth of the customer of present year.

4.Total income - Total income of the customer.

5.Change in stock	- difference between value of current stock and the value of stock in last trading day.

6.Total expenses	- Total expense done by customer.

7.Profit after tax	- Profit after tax deduction.

8.PBDITA	- Profit before depreciation, income tax and amortization.

9.PBT	- Profit before tax deduction.

10.Cash profit	- Total Cash profit.

11.PBDITA as % of total income	- PBDITA / Total income.

12.PBT as % of total income	- PBT / Total income.

13.PAT as % of total income	- PAT / Total income.

14.Cash profit as % of total income	- Cash Profit / Total income.

15.PAT as % of net worth	- PAT / Net worth.

16.Sales	- Sales done by customer.

17.Income from financial services	- Income from financial services.

18.Other income	- Income from other sources.

19.Total capital	- Total capital of the customer.

20.Reserves and funds	- Total reserves and funds of the customer.

21.Deposits (accepted by commercial banks)	- All blank values.

22.Borrowings	- Total amount borrowed by customer.

23.Current liabilities & provisions	- current liabilities of the customer.

24.Deferred tax liability	- Future income tax customer will pay because of the current transaction.

25.Shareholders funds	- Amount of equity in a company, which is belong to shareholder.

26.Cumulative retained profits	- Total cumulative profit retained by customer.

27.Capital employed	- Current asset minus current liabilities.

28.TOL/TNW	- Total liabilities of the customer divided by Total net worth.

29.Total term liabilities / tangible net worth	- Short + long term liabilities divided by tangible net worth.

30.Contingent liabilities / Net worth (%)	- Contingent liabilities / Net worth.

31.Contingent liabilities	- Liabilities because of uncertain events.

32.Net fixed assets	- purchase price of all fixed assets.

33.Investments	- Total invested amount.

34.Current assets	- Assets that are expected to be converted to cash within a year.

35.Net working capital	- Difference of current liabilities and current assets.

36.Quick ratio (times)	- Total cash divided by current liabilities.

37.Current ratio (times)	- Current assets divided by current liabilities.

38.Debt to equity ratio (times)	- Total liabilities divided by its shareholder equity.

39.Cash to current liabilities (times)	- Total liquid cash divided by current liabilities.

40.Cash to average cost of sales per day	- Total cash divided by average cost of the sales.

41.Creditors turnover	- Net credit purchase divided to average trade creditors.

42.Debtors turnover	- Net credit sales divided by average accounts receivable.

43.Finished goods turnover	- Annual sales divided by average inventory.

44.WIP turnover	- The cost of goods sold for a period divided by the average inventory for that period.

45.Raw material turnover	- Cost of goods sold is divided by the average inventory for the same period.

46.Shares outstanding	- Number of issued shares minus the number of share held in the company.

47.Equity face value	- cost of the equity at the time of issuing.

48.EPS	- Net income divided by total number of outstanding share.

49.Adjusted EPS	- Adjusted net earning divided by the weighted average number of common share outstanding on a diluted basis during the plan year.

50.Total liabilities	- Sum of all type of liabilities.

51.PE on BSE	- Company current stock price divided by its earning per share.
