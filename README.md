# About Project
 This project applies the Self-Organizing Map (SOM) model as an additional method to assist in stock selection prior to applying the Mean-Variance model. Initially, we used the SOM model on the average features of 46 companies from 2018 to the present, narrowing the selection down to 36 companies. Then, we applied the SOM model again using quarterly data with two different grid dimensions: 5×5 and 7×7. The 5×5 SOM grid resulted in a selection of 21 companies, while the 7×7 grid reduced the list further to 10 companies. Finally, we applied the Mean-Variance model to both the 21- and 10-company selections to identify the most promising investment options.
# Stock
### Consumer Discretionery
#### Home Depot
 Data records in Thoundsands.
<br>  For Q4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3
<br>    Apllied for Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  Total debt =  short-term debt + Current installments of long-term debt + current operating lease liabilities + long-term debt + long-term operating lease liabilities

#### Wayfair (W)
 Data records in thousands.
<br>  For Q4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3
<br>    Apllied for Total Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  Total debt = "long-term debt" + "Operating lease liabilities, net of current"
<br>  Shares Outstandings = Class A + Class B outstandings

#### Amazon (AMZN)
  Data records in thousands
<br>  For Q4 report, take the features of annual report , minus to the sum of features of Q1, Q2, Q3
<br>    Apllied for Total Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  Total liabilities = "Total liabilities and stockholders’ equity" - "Total stockholders’ equity"
<br>  Total debt = "long-term debt" + "long-term lease liabilities"
<br>  Amazon's stock split occurred on June 3, 2022, and the split was 20-for-1. Therefore, for diluted EPS Q1, Q2, Q3 before that time, I divided them to 20, and shares outstanding was multiplied to 20 in order to keep the consistency. Also, to calculate the EPS of Q4, before that time, we multiply  diluted weighted average common shares to 20 first then divide net income to it.
### Healthcare

#### UnitedHealth Group Inc (UNH)
  Wait for the annual report of 2025.
<br>  Data records in Thousands.
<br>  For Q4 report, take the features of annual report , minus to the sum of features of Q1, Q2, Q3
<br>    Apllied for Total Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  Total Shareholder's Equity =  common stock + additional paid-in capital + retained earnings + accumulated other comprehensive loss
<br>  Total debt = “long-term debt, less current maturities” + “short-term borrowings and current maturities of long-term debt”
#### Pfizer (PFE)
<br>  Data records in Thousands.
<br>  For Q4 report, take the features of annual report , minus to the sum of features of Q1, Q2, Q3
<br>    Apllied for Total Net sales/ Net Revenue, Net Income.
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>   For year 2017, 2018, 2019, please find a full report in directly website
<br>  For Shares Outstanding, find it on “The number of shares outstanding” for annual report and “ shares of the issuer’s voting common stock were outstanding” for quarterly report
<br>  Total debt =  “short-term borrowings” + “long-term debt”
<br>  For Net Income, find  Net income/(loss) attributable to Pfizer Inc. common shareholders for annual for quarterly and GAAP reported number for annual report
#### DexCom Inc (DXCM)
  Data records in thousands
<br>  For Q4 report, take the features of annual report , minus to the sum of features of Q1, Q2, Q3
<br>    Apllied for Total Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  Total liabilities = "Total liabilities and stockholders’ equity" - "Total stockholders’ equity"
<br>  Total debt =  "Short-term operating lease liabilities" + "Long-term senior convertible notes" + "long-term operating lease liabilities" (if they have Current portion of long-term senior convertible notes, include it).
<br>  DexCom's stock split occurred on June 13, 2022, and the split was 4-for-1. Therefore, for diluted EPS before that time, I divided them to 4, and shares outstanding was multiplied to 4 in order to keep the consistency. Also, to calculate the EPS of Q4, before that time, we multiply  diluted weighted average common shares to 4 first then divide net income to it.
### Consumer Staples

#### Costco (COST)
  Data records in thousands
<br>  Costco has a different time of fiscal year, it runs from September 1 through August 31. For Q3 report, take the features of annual report, minus to the sum of features of Q4 of previous year, Q1, Q2 of this year
<br>    Apllied for Total Net sales/ Net Revenue, Net Income, EPS
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  for Net income, find "Net income attributable to Costco"
<br>  Total debt = "Long-term debt, excluding current portion" + "Long-term operating lease liabilities" + "Current portion of long term debt"
#### Hershey Co (HSY)
  Data records in thousands
<br>  For Q4 report, take the features of annual report , minus to the sum of features of Q1, Q2, Q3
<br>    Apllied for Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  Total debt =  "total lease liabilities" + "long-term debt" + "Current portion of long-term debt" + "Short-term debt"
#### Keurig Dr Pepper Inc (KDP)
  Data records in thousands
<br>  For Q4 report, take the features of annual report , minus to the sum of features of Q1, Q2, Q3
<br>    Apllied for Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  Total debt =  Short-term borrowings and current portion of long-term obligations + Long-term obligations
<br>  In July 2018, Keurig Green Mountain merged with Dr Pepper Snapple Group to form Keurig Dr Pepper (KDP). Therefore, we see the dramaticall changes in their daata. 
#### E.L.F Beauty, Inc (HSY)
<br>  Data records in Thoundsands.
<br>  For Q1 report, take the features of annual report , minus to the sum of features of Q4, Q3, Q2 of previous year
<br>    Apllied for Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  Total debt =  "Current portion of operating lease liabilities" in Note 5—Accrued expenses and other current liabilities + "Current portion of long-term debt" in current asset + "Long-term debt" + "Long-term operating lease obligations"
#### Clorox Co (CLX)
<br>  Data records in Millions, except shares data.
<br>   For Q4 report, take the features of annual report , minus to the sum of features of Q1, Q2, Q3. Apllied for Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>    Apllied for Net sales/ Net Revenue, Net Earnings (Net Income), EPS. In order to find the annual report, please find them on direct webiste of Clorox Co.
<br>  Total debt = "Note and loan payable" + "Current operating lease liabilities" + "Long-term debt" + "Long-term operating lease liabilities"

### Energy

#### Exxon Mobil (XOM)
  Data records in thoundsands
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year
<br>    Apllied for Total Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  For Net income, find "Net income (loss) attributable to ExxonMobil". For total Net Sales/Net Revenue, find "Total revenues and other income". 
<br>  Total debt = long-term debt + Notes and loans payable

#### Chrevon (CVX)
  Data records in thoundsands
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year
<br>    Apllied for Total Net sales/ Net Revenue, Net Income
<br>    EPS for all quarter is directly found in annual report of each year
<br>  For Net income, find "Net Income (Loss)Attributable to Chevron Corporation".
<br>  Total debt = Long-term debt + short term debt
#### Shell PLC (SHEL)
  Data records in thoundsands Data report directly in the website of Shell. before Q2 2022, we combine the shares common A and B. We find EPS under "Earning per share per ADS". Links: https://www.shell.com/investors/results-and-reporting/quarterly-results.html
<br>  For Total debt, we find Find "total debt" in APM sheet
#### Marathon Petroleum Corporation (MPC)
  Data records in thoundsands
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares, 2018, 2017 found directly in report
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue, Net Income
<br>  For Net Sales/ Net revenue, find "Sales and other operating revenue".
<br>  Total debt = Debt due within one year + Operating lease liabilities + Long-term debt + Long-term operating lease liabilities
#### Halliburton Co (HAL)
  Data records in Millions, shares outstandings in ones.
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares, 2018, 2017 found directly in report
<br>  For Net income, find "Net income attributable to company".
<br>  Total debt = "Current portion of operating lease liabilities" + "Long-term debt" + "Operating lease liabilities"
### Ultities
#### Dominion Energy Inc (D)
  Data records in Thoundsands.
<br>   For Q4 report, take the features of the annual report, minus the sum of features of Q1, Q2, Q3 of this year.Apllied for Total Net sales/ Net Revenue (Operating Revenue), Net Income (Net Income Attributable to Dominion Energy)
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  Total debt = "Securities due within one year" + "Supplemental credit facility borrowings" + "Total long-term debt" + "Short term debt"

#### NextEra Energy Inc (NEE)
  Data records in Thoundsands.
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue , Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  For Net income, find "Net income attributable to NEE". For total Net sales/ net revenue, find "Operating revenues"
<br>  Total debt = Commercial paper + Other short-term debt + Current portion of long-term debt + long-term debt
<br>  The company has stock split 4 for 1 on 2020. Therefore in 2020 data and previous that time, shares outstanding multiply to 4, and diluted EPS divide to 4 in order to keep the consistency. Also, to calculate the EPS of Q4, before that time, we multiply  diluted weighted average common shares to 4 first then divide net income to it.
#### Duke Energy Corp (DUK)
  Data records in Thoundsands.
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue, Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>   For Net income, find "Net Income Available to Duke Energy Corporation Common Stockholders". For total Net sales/ net revenue, find "Total Operating revenues"
<br>   Total liabilities = total Liabilities and Equity - Total equity
<br>  Total debt = Long-term Debt + Notes payable and commercial paper + Current maturities of long-term debt + Operating lease liabilities

#### American Electric Power Company Inc (AEP)
  Data records in Thoundsands
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue , Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  For Net income, find "Earnings attributable to AEP Common Shareholders"
<br>  Total debt = Total Short-term debt + Long-term Debt Due Within One Year + Obligations Under Operating Lease + Long-term Debt + Obligations Under Operating Lease

#### Eversource Energy (ES)
  Data records in Thoundsands
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue , Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income  of Q4 / diluted weighted average common shares
<br>  For Net income, find "Net (Loss)/ Income Attributable to Common Shareholders". For total Net sales/ net revenue, find "Operating revenues"
<br>  Total debt = "Notes Payable" + "Long-term Debt-Current Portion" + "Rate Reduction Bonds - Current Portion" +"Long-term Debt" + "Rate Reduction Bonds"
<br>  Total Liabilities = Total Liabilities and Capitalization - Common Shareholder's Equity

#### PG&E Corp (PCG)
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue, Net Income.
<br>   In order to find EPS, EPS =  "(Net Income - Preferred stock dividend requirement)" or "Income Available for Common Shareholders"/ diluted weighted average common shares
<br>   For total Net sales/ net revenue, find "Total revenues"
<br>   Total liabilities = Total current liabilities + Total noncurrent liabilities
<br>  Total debt = Total Debt = Short-term borrowings + Long-term debt, classified as current + Operating lease liabilities (under current liabilities) + Financing lease liabilities (under current liabilities) + Long-term debt + Regulatory liabilities + Operating lease liabilities (under noncurrent liabilities) + Financing lease liabilities (under noncurrent liabilities)
### Industrials
#### RTX Corporation (RTX)
  Data records in thousands
<br>   For Q4 report, take the features of the annual report, minus the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue (Operating Revenue), Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income  of Q4 / diluted weighted average common shares
<br>  For Net income, find "Net (loss) income attributable to common shareowners".
<br>  Total debt find directly in financial statement. In order to find data before the changes, I found the old data on directly website
#### FedEx Corp (FDX)
  Data records in thousands.
<br>   For Q2 report, take the features of the annual report, minus the sum of features of Q1 of this year and Q3, Q4 of previous year. Apllied for Total Net sales/ Net Revenue (Operating Revenue), Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income  of Q4 / diluted weighted average common shares
<br>  For Net income, find "Net income from operations".
<br>  Total liabilities = total current liabilities + Long-term debt, less current portion + Total other long-term liabilities
<br>  Total debt= Current portion of long-term debt + Operating lease liabilities + Long-term debt, less current portion + Operating lease liabilities

#### L3Harris Technologies Inc (LHX)
L3Harris Technologies announced the successful merger completion between Harris Corporation and L3 Technologies on June 29, 2019. Therefore, the annual report of 2019 of the old company is found directly on their website.
<br>   For Q4 report, take the features of the annual report, minus the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue (Operating Revenue), Net Income
<br>   In order to find the Q4 EPS, EPS =  Net Income  of Q4 / diluted weighted average common shares
<br>  Total debt= Short-term debt + Current portion of long-term debt, net + long-term debt, net 
#### Tetra Tech Inc (TTEK)
<br>   For Q3 report, take the features of the annual report, minus the sum of features of Q1, Q2, of this year and Q4 of previous year. Apllied for Total Net Sales/ Net Revenue (Operating Revenue), Net Income
<br>   In order to find the Q3 EPS, EPS =  Net Income  of Q3 / diluted weighted average common shares
<br>   The company has stock split 5 for 1 on september 2024. Therefore in 2024 data and previous that time, shares outstanding multiply to 5, and diluted EPS divide to 5 in order to keep the consistency. Also, to calculate the EPS of Q3, before that time, we multiply  diluted weighted average common shares to 5 first then divide net income to it.
<br>  For Net income, find "Net income from operations".
<br>  Total debt = Short-term lease, operating leases + current portion of long-term debt + Long-term debt + Long-term lease liabilities, operating leases

#### U-Haul Holding Co (UHAL)
Data is taken from [Macrotrend](https://www.macrotrends.net/stocks/charts/UHAL/u-haul-holding/balance-sheet?freq=Q) website since their financial statement doesn't have current assets and current liabilities data for current assets and current liabilities. 
<br>  In order to find net income, Find "Earnings available to common stockholders". The fiscal year ends on March of each year. 
<br>   In order to find the Q1 EPS, EPS =  Net Income  of Q1 / diluted weighted average common shares
<br>  Amerco, the parent company of U-Haul, underwent a 10-to-1 stock split and a name change to U-Haul Holding Company starting November 2022.
<br>  Total debt = Notes, loans and finance leases payable, net + Operating lease liabilities
### Real Estate
#### Prologis, Inc (PLD)
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue, Net Income
<br>   Calculate EPS: First, find the net earnings attributable to common holders. Net earnings attributable to common holders = net earnings attributable to controlling interests - Less preferred stock dividends. In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br> Data is based on Yahoo Finance. Total current liabilities = Accounts payable and accrued expenses + Deferred revenue and fees+ liabilities associated with assets held for sale or contribution + value added taxes payable + Credit facilities and commercial paper + unearned rents. For Net income, find "Net earnings attributable to controlling interests.  Total current asset = 
Cash and cash equivalents + Accounts receivable + Other notes receivable + Value added taxes receivable (in total other assets) + prepaid assets + Net investments in real estate
#### American Tower Corporation (AMT)
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue, Net Income. For Net income, find "Net earnings(loss) income attributable to American tower corporation common stockholders. For Net Sales, find "Total operating revenue".
<br>   Calculate EPS: First, find the net earnings attributable to common holders. Net earnings attributable to common holders = net earnings attributable to controlling interests - Less preferred stock dividends. In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br>  Total debt = long-term obligations + operating lease liabilitiy + current portion of operating lease liabilitity + Current portion of long-term obligations
#### Extra Space Storage Inc. (EXR)
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue, Net Income. For Net income, find "Net income attributable to common stockholders." 
<br>   Calculate EPS:  In order to find the Q4 EPS, EPS =  Net Income (net earnings) of Q4 / diluted weighted average common shares
<br> Data is based on Yahoo Finance. Total current liabilities = Payables And accured Equity 
 (Accounts payable and accrued expenses +Cash distributions in unconsolidated real estate ventures)  + Current debt and capital (Revolving lines of credit). Total current asset = 
Cash and Cash equivalents + accounts receivable +Notes Receivable +Restricted Cash + Prepaid Assets (Other intangible assets, net) + other receivables (Other intangible assets, net)
<br>  Total debt = long-term obligations + operating lease liabilitiy + current portion of operating lease liabilitity + Current portion of long-term obligations
#### Kimco Realty Corporation (KIM)
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue, Net Income. For Net income, find "Net income attributable to the Company." In order to calculate the EPS, EPS = (Net income attributable to the Company - Preferred dividends) / weighted average shares or EPS = net income available to the Company's common share holders / weighted average shares (Diluted)
<br> Data is based on Yahoo Finance. Total current liabilities = Total Current liabilities = Accounts payable and accrued expenses + dividends payable. Total Current Assets = Cash, cash equivalents and restricted cash + Marketable securities + Accounts and notes receivable, net 
<br>  total debt = Notes Payable, net + Mortgages payable, net + Operating lease liabilities (yahoo Finance)
#### SL Green Realty Corp. (SLG)
<br>   For 4 report, take the features of annual report, minus to the sum of features of Q1, Q2, Q3 of this year. Apllied for Total Net sales/ Net Revenue, Net Income. For Net income, find "Net income (loss)." 
<br>   In order to calculate the EPS, EPS = Net income (loss) attributable to SL Green common Stockholders / Diluted weighted average common shares and common share equivalents outstanding
<br> Data is based on Yahoo Finance. Total current Liabilities = Revolving credit facility, net + Accrued interest payable + Accounts payable and accrued expenses + Deferred revenue + Dividend and distributions payable. Total current asset = Assets held for sale + Cash and Cash equivalents + restricted cash + Investments in marketable securities + tenant and other receivables + Related party receivables + Deferred rents receivable + Real estate loans held by consolidated securitization vehicles 
<br> Total debt = Mortgages and other loans payable, net + Revolving credit facility, net + Unsecured term loans, net+ Unsecured notes, net + Senior obligations of consolidated securitization vehicles + Lease liability + Junior subordinated deferrable interest debentures held by trusts that issued trust preferred securities
### Ultities
#### JPMorgan Chase & Co. (JPM)
  Data records in Thoundsands.
<br>   For Q4 report, take the features of the annual report, minus the sum of features of Q1, Q2, Q3 of this year. Total Current Liabilities, total current asset from website Macrotrends.
<br>   EPS found directly in the report
<br>  cash and cash Equivalents = "Cash and due from banks" + "Deposit with banks"
<br> total debt = long-term debt + short-term borrowing
#### Morgan Stanley (MS)
  Data records in Thoundsands.
<br>   For Q4 report, take the features of the annual report, minus the sum of features of Q1, Q2, Q3 of this year. Net Income, look for "Net income applicable to Morgan Stanley". Total Current Liabilities, total current asset from website Macrotrends
<br>  in order to find EPS Q4, take the Earnings applicable to Morgan Stanley common shareholders of Q4 / average common shares outstanding
<br> total debt = long-term debt + short-term borrowing
#### Morgan Stanley (MS)
  Data records in Thoundsands.
<br>   For Q4 report, take the features of the annual report, minus the sum of features of Q1, Q2, Q3 of this year. Net Income, look for "Net income applicable to Morgan Stanley". Total Current Liabilities, total current asset from website Macrotrends
<br>  in order to find EPS Q4, take the Earnings applicable to Morgan Stanley common shareholders of Q4 / average common shares outstanding
<br> total debt = long-term debt + short-term borrowing
#### Visa Inc. (V)
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> Net Income /( Diluted Weighted-average Shares Outstanding of Class A + Class B + Class C)
### Information Technology
#### Apple (AAPL)
<br> Apple's Fiscal year starts from October and ends in September
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Shares used in computing earnings per share (Diluted)
<br> 4-1 stock split happened in Q4 2020. In order to maintain consistency, the previous quarter's shares outstanding ahve been multipled by 4 and EPS is divided by 4.
<br> Total debt = Secured notes payables, net + Unsecured term loans, net + Unsecured senior notes, net + Operating lease liabilities + Revolving lines of credit

#### Service Now (NOW)
<br> Fiscal year starts from January and ends in December.
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Weighted-average shares (Diluted)
<br> Total Debt = Current Portion of OPerating Lease Liabilities + OPerating Lease Liabilities, less current portion + Long-term Debt, net

#### Microsoft (MSFT)
<br> Fiscal year starts from July and ends in September
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Weighted-average shares (Diluted)
<br> Total Debt = Long term Debt + Short Term Debt + Operating Lease Liabilities

### Communication Services
#### Alphabet (GOOG, GOOGL)
<br> Fiscal year starts from January and ends in December.
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Weighted-average shares (Diluted) of Class A, B & C
<br> 20 to 1 stock split happened in Q2 2022. For consistency, all the previous quarters Shares Outstanding have been multiplied by 20 and EPS has been divided by 20.
<br> Total Debt = Current Operating Lease Liabilities + Long Term Debt + Operating Lease Liabilities

#### Netflix (NFLX)
<br> Fiscal year starts from January and ends in December.
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Weighted-average shares (Diluted)
<br> Total Debt = Short Term Debt + Long Term Debt

#### Yelp (YELP)
<br> Fiscal year starts from January and ends in December.
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Weighted-average shares (Diluted)
<br> Total Debt = Operating lease liabilities — current	+ Operating lease liabilities — long-term	

### Materials
#### Ecolab Inc (ECL)
<br> Fiscal year starts from January and ends in December.
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Weighted-average shares (Diluted)
<br> Total Debt = Short-term debt + Long-term debt + Operating lease liabilities + perating lease liabilities (Discontinued Operations)

#### Sherwin Williams (SHW)
<br> Fiscal year starts from January and ends in December.
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Weighted-average shares (Diluted)
<br> 3-for-1 stock split happened in Q1 2021. To maintain consistency, the previous quarters Shares Outstanding were multiplied by 3 and EPS was divided by 3.
<br> Total Debt = Short-term borrowings	+ Current portion of long-term debt	+ Current portion of operating lease liabilities	+ Long-term debt	+ Long-term operating lease liabilities	

#### Southern Cooper Corporation (SCCO)
<br> Fiscal year starts from January and ends in December.
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Weighted-average shares (Diluted)
<br> Total Debt = Current portion of long-term debt + Lease liabilities current + Long-term debt + Lease Liabilities

#### Cleveland Cliffs (CLF)
<br> Fiscal year starts from January and ends in December.
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Average number of shares (Diluted)
<br> Total Debt = Long Term Debt

#### Linde PLC (LIN)
<br> Fiscal year starts from January and ends in December.
<br> For Q4 of every year, Net Sales/Total Revenue, Net Income are calcualted as follows Annual - (Q1 + Q2+ Q3)
<br> EPS for Q4 is calculated as Net Income of Q4/ Weighted average number of shares (Diluted)
<br> Total Debt = Short-term debt + Current portion of long-term debt + Long-term debt









