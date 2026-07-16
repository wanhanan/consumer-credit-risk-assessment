# Banking Basics
This document explains the banking concepts relevant to the Consumer Credit Risk Assessment project.

## Main Question

How does a retail bank actually make money?

## 01 Commercial Bank
Idea: Interest Differential

```mermaid
flowchart TD

    A[Households deposit money into Bank] --> B[Bank receives deposits]

    B --> C[Bank lends deposits to Borrowers]

    C --> D[Borrower receives loan]
    D --> E[Example:
    Loan amount = $10,000
    Loan interest rate = 5%]

    E --> F[Borrower repays:
    Principal $10,000 + Interest $500]

    F --> G[Bank receives lending interest income:
    $500]


    B --> H[Bank pays interest to Depositors]

    H --> I[Example:
    Deposit amount = $20,000
    Deposit interest rate = 3%]

    I --> J[Deposit remains fully deposited until maturity]

    J --> K[Bank pays depositor:
    $20,000 x 3% = $600]


    G --> L[Bank Interest Income]
    K --> M[Bank Interest Expense]

    L --> N[Interest Differential / Net Interest Margin]

    M --> N

    N --> O[Bank Profit from Financial Intermediation]

Thus, this is the general system of how bank exists. However, in the case deposits being withdrawn by the their depositor, the calculation of interest paid by the bank to their customers may differ based on bank's rule.


---

# Flowchart 2 — Withdrawal Case: Methods of Calculating Deposit Interest

This begins **only after the depositor withdraws part of the savings**.

```md
```mermaid
flowchart TD

    A[Depositor has savings account] --> B[Withdrawal occurs before interest payment date]

    B --> C[Deposit balance changes]

    C --> D{Which interest calculation method does the bank apply?}


    D -->|Method 1:
    Daily Balance Method| E[Interest calculated based on daily account balance]

    E --> F[Example:
    Day 1-100:
    Balance = $20,000

    Day 101-365:
    Balance = $15,000]

    F --> G[Interest calculated separately for each period]


    D -->|Method 2:
    Minimum Balance Method| H[Bank identifies lowest balance during period]

    H --> I[Example:
    Initial deposit = $20,000

    Withdrawal = $5,000

    Minimum balance = $15,000]

    I --> J[Interest:
    $15,000 x 3% = $450]


    D -->|Method 3:
    Average Balance Method| K[Bank calculates average balance during period]

    K --> L[Example:
    Average balance = $17,500]

    L --> M[Interest:
    $17,500 x 3% = $525]


    D -->|Method 4:
    Maturity Balance Method| N[Only money remaining until maturity receives interest]

    N --> O[Withdrawn amount excluded]

    O --> P[Interest calculated on remaining matured deposit]


    G --> Q[Depositor receives interest payment]
    J --> Q
    M --> Q
    P --> Q

## 02 Investment Bank

