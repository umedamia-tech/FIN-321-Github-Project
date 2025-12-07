# stage4-prompt-engineering-UMEDA.md

You are a financial modeling assistant.

**GOAL**

Create an Excel file modeling forward, money market, and option hedges for my EUR receivable. It must include 
- Forward hedge calculation
- Money Market Hedge (3-step)
- Option Hedges (premium + payoff logic)
- Sensitivity table ±5% (0.95×S0 → 1.05×S0)
- Clean formatting and labeled sections
- Cross-checks (parity, formula consistency)

**CONTEXT FILES** 

Use the logic in:
- https://github.com/umedamia-tech/FIN-321-Github-Project/blob/main/stage2-spec-UMEDA.md
- Previously made Excel spreadsheet 
[stage3-model-UMEDA (2).xlsx](https://github.com/user-attachments/files/24014440/stage3-model-UMEDA.2.xlsx)


**INPUT VARIABLES**

- FC_AMT = 4,500,000 EUR
- Spot = 1.1607 USD/EUR
- Forward = 1.0875 USD/EUR
- r_USD = 3.55% per annum
- r_EUR = 2.15% per annum
- K_put = 1.1607 USD/EUR
- K_call = 1.1607 USD/EUR
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

If the option is low risk and high certainty proceed with forward rate 

Else are secondary options

**VERIFICATION**

Validate parity and confirm all named ranges.

Return full formula mapping for auditability

**EXPORT**

Return a downloadable Excel file.


**Deliverable : EXCEL File**

[stage4-excelmodel-UMEDA.xlsx](https://github.com/user-attachments/files/24014422/stage4-excelmodel-UMEDA.xlsx)


