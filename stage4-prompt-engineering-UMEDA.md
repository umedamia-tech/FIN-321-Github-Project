# stage4-prompt-engineering-UMEDA.md

You are a financial modeling assistant.

**GOAL**

Create an Excel file modeling forward, money market, and option hedges for my EUR receivable.

**CONTEXT FILES** 

Use the logic in:
- https://github.com/umedamia-tech/FIN-321-Github-Project/blob/main/stage2-spec-UMEDA.md
- Previously made Excel spreadsheet (attached)

**INPUT VARIABLES**

- FC_AMT = 4,500,000 EUR
- Spot = 1.1607 USD/EUR
- Forward = 1.0875 USD/EUR
- r_USD = 3.55% per annum
- r_EUR = 2.15% per annum
- K_put = 1.1607 USD/EUR (ATM)
- K_call = 1.1607 USD/EUR (ATM)
- Premium_put = 0.015 USD per EUR
- Premium_call = 0.018 USD per EUR
- T_days = 365 days

**SPREADSHEET REQUIREMENTS**

Use standardized named ranges such as
- FC_AMT
- S0_in
- F0_in
- R_USD
- R_FC
- K_PUT
- K_CALL
- PREM_PUT
- PREM_CALL
- T_DAYS

Color code inputs yellow, formulas green, outputs gray, assumptions blue.
Include forward hedge, money market hedge, option hedge, and sensitivity analysis.

**MODEL LOGIC**

(Insert pseudocode from Stage 2 spec)

**VERIFICATION**

Validate parity and confirm all named ranges.

**EXPORT**

Return a downloadable Excel file.
