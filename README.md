# alumni-project-finance
Financial Management/Debt Payoff Application built by *Trilogy Boot Camp Alumni*

---

## Ideas from 1/26
- Users should have a unique dashboard with insights (ideas for charts: Debt Payoff date/timeline, total balance by categories… possibly more?)
- User should be able to add debts Total Balance, Minimum Payment,  Loan term (if applicable), Account name (Or nickname), Interest Rate, type of debt (auto loan, mortgage, student loan, credit cards).
- User should be able to categorize their debts  
- User should be able to add a customized payment (a lump sum) to see the effects that payment has on the loan/account
- User should be able to see a breakdown of an amortization schedule
- User should be able to record payments made on a debt
- User should be able to look through their transactions
- User should be able to choose a category to pay off or select a transaction/account to pay off
	
#### Inspiration: 
- [Debt Repayment Calculator (CreditKarma)](https://www.creditkarma.com/calculators/debtrepayment)
- [Loan Repayment Calculator (Mint)](https://mint.intuit.com/resources/loan-calculator/)
- [Page Layout (CapitalOne)](https://www.capitalone.com/credit-cards/benefits/)

---

## Ideas from 2/2

### Action items
#### Choose our stack
- MERN?
- MEAN?
- CSS framework?
- Wire framing and design platform?
- Other tech? 
    - JsCharts?
    - Plotly

#### What APIs can we use
- [Plaid](https://plaid.com) is a way for app developers to interface with user Banks without infringing on user privacy.
 
### TO-DO
- Create a repo
- Write out our (official) README
- Set up project methodology
    - scrum
    - kan ban board
- Assign roles
- Set up checks
    - Github Issues
- Web development
- Establish coding norms such as linter?

### Brainstorm
> (From 1/26 Meeting): "Users should have a unique dashboard with insights to their current finances and future goals (ideas for charts: Debt Payoff date/timeline, total balance by categories… possibly more?)"

#### Charts
- Cashflow Diagram (spending and income)
    - Bar graph?
- Categories of spending 
    - Pie graph?
    - Tree map?

#### Calendars
- *User can set a date*
- *Simulate the snowball effect of paying off debt*
    - starting with smaller items to pay and moving to larger items in different categories. 
    - For example: clothing 200, phone bill 100, 400 travel, etc.
        1. Phone Bill
        2. Clothing
        3. Travel
- *Amortization Calculator*
    - User uploads current debt information (e.g current balance, original principal, interest rate, anticipated payoff date)
    - App responds by building Amortization schedule
    - User can add or subtract from payments to visualize adjustments on the original loan:
        - total interest paid (saved)
        - monthly payment
        - payoff date

#### Personalizing Credit Card Debt Visualization:
- In the same way that banks allow users to match spending categories to budget line items, imagine a user who charges $100 of clothing expenses and a $200 phone bill to their credit card. At the end of the month if they pay $30 then we could visualize those transactions such that the user has paid off 10% of their clothing charge and 10% of their phone bill. This could help a user to diagnose their spending habits, emotionally connecting to their purchases in a more concrete manner.

#### Budget
- Search budget categories across previous months to see where you over or under spent on your budget.
- App should reconcile transactions with the user defined budget based on the transactions at each merchant.

