# 3-Statement Financial Model

An Excel model linking the income statement, balance sheet and cash flow statement, built from scratch following Financial Modeling Institute (FMI) conventions.

Revenue and cost drivers feed the P&L, the supporting schedules feed the balance sheet, and the cash flow statement is derived from both. Change an assumption and everything downstream updates.

## What's in the model

**Statements**
- **Income statement:** revenue build-up and operating expenses driven by assumptions.
- **Balance sheet:** balances in every period, with a check row (Assets = Liabilities + Equity).
- **Cash flow statement:** indirect method, starting from net income and using balance sheet changes.

**Schedules**
- **Working capital:** receivables, inventory and payables driven by DSO, DIO and DPO.
- **PP&E:** CapEx and depreciation.
- **Debt and equity:** senior debt amortization, interest expense and retained earnings roll-forward.

## Conventions

- Blue font for hardcoded historical inputs, black for formulas.
- No hardcoded numbers in forecast periods.
- A balance check row flags any imbalance immediately.
- A scenario toggle switches between cases.

## Note on the scenario toggle

The toggle is an Excel form control, so it only works in desktop Excel and won't respond in GitHub's preview. Download `Financial Model.xlsx`, open it and click **Enable Editing**. After that you can switch scenarios and trace the formulas.

##  Author
**Andrii Serdiuk**  
* Economics Graduate | CFA Level I Passed  
* **LinkedIn:** https://www.linkedin.com/in/andrii-serdiuk-/?isSelfProfile=true)
* **Location:** Warsaw, Poland
