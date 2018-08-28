# CAPSTONE | ILKNUR TEZGIDEN
# Default Prediction

## Brief Info About Data Set

**Data Set Mortgage**

The data set mortgage is in panel form and reports origination and performance observations for 50,000 residential U.S. mortgage borrowers over 60 periods. The periods have been deidentified. As in the real world, loans may originate before the start of the observation period (this is an issue where loans are transferred between banks and investors as in securitization). The loan observations may thus be censored as the loans mature or borrowers refinance. The data set is a randomized selection of mortgage-loan-level data collected from the portfolios underlying U.S. residential mortgage-backed securities (RMBS) securitization portfolios and provided by International Financial Research (www.internationalfinancialresearch.org). 

Key variables:

- __**id**__: Borrower ID
- __**time**__: Time stamp of observation
- __**orig_time**__: Time stamp for origination
- __**first_time**__: Time stamp for first observation
- __**mat_time**__: Time stamp for maturity
- __**balance_time**__: Outstanding balance at observation time
- __**LTV_time**__: Loan-to-value ratio at observation time, in %
- __**interest_rate_time**__: Interest rate at observation time, in %
- __**hpi_time**__: House price index at observation time, base year = 100
- __**gdp_time**__: Gross domestic product (GDP) growth at observation time, in %
- __**uer_time**__: Unemployment rate at observation time, in %
- __**REtype_CO_orig_time**__: Real estate type condominium = 1, otherwise = 0
- __**REtype_PU_orig_time**__: Real estate type planned urban development = 1, otherwise= 0
- __**REtype_SF_orig_time**__: Single-family home = 1, otherwise = 0
- __**investor_orig_time**__: Investor borrower = 1, otherwise = 0
- __**balance_orig_time**__: Outstanding balance at origination time
- __**FICO_orig_time**__: FICO score at origination time, in %
- __**LTV_orig_time**__: Loan-to-value ratio at origination time, in %
- __**Interest_Rate_orig_time**__: Interest rate at origination time, in %
- __**hpi_orig_time**__: House price index at origination time, base year = 100
- __**default_time**__: Default observation at observation time
- __**payoff_time**__: Payoff observation at observation time
- __**status_time**__: Default (1), payoff (2), and nondefault/nonpayoff (0) observation at observation time
