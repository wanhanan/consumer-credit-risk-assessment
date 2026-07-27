# 1. What is credit risk? 
Credit risk is the possibility that a borrower will fail to meet their repayment obligations according to the agreed loan terms. When a borrower defaults, the bank may lose part or all of the outstanding loan amount, incur collection costs, and lose expected interest income.

Since loan defaults directly affect profitability, accurately assessing credit risk before approving a loan is one of the most important responsibilities of a retail bank.

# 2. Why credit risk matters?
High default rates lead to:
- Financial losses
- Lower profitability
- Higher loan loss provisions
- Reduced lending capacity
- Increased regulatory scrutiny
- Loss of investor and customer confidence

However, being too conservative is also bad.

If the bank rejects too many applicants,
- fewer loans are issued
- interest income decreases
- market share declines

The goal of a retail bank is to manage risk while maintaining its profitability, not to eliminate risk.

# 3. The Credit Approval Process

<img width="326" height="337" alt="image" src="https://github.com/user-attachments/assets/cdb5f7ae-20c4-4501-b23a-e63a763c17cf" />

# 4. Key Components of Credit Risk
## • Probability of Default (PD)
The probability that a borrower will default within a specified period (typically one year).
The higher the PD, the higher risk of giving credit to that person.

## • Loss Given Default (LGD)
If the borrower defaults, how much money will the bank actually lose?
The amount in which collateral may not being able to cover the person's outstanding loan. 
For example, given the outstanding balance is $12,000 and the borrower pledged a car as collateral. The bank sells the car for $9,000. This means the actual loss suffered by the bank is $3,000. ($3000/$12,000)*100% = 25%. Thus, the bank only loss 25% of the outstanding loan.

## • Exposure at Default (EAD)
How much money is still owed when the borrower defaults?
The outstanding loan that borrower not able to repay. 
For example, the original loan amount is $20,000 and the borrower has successfully paid $8,000. Thus, the outstanding balance or known as EAD is $12,000.

## • Expected Loss
Banks would not think of what is the probability of the person will default but they would think of the average amount of expected loss. Thus, the bank will consider the probability of the individual default and the actual loss suffered given default. 
Thus, the formula of Expected Loss is EL = PD × LGD × EAD.
For example:
PD = 10% , LGD = 25%, EAD = $12,000
Therefore, expected loss is 0.10 x 0.25 x $12,000 = $300. This mean, based on the historical data, the bank is expected to lose $300 on average on this loan over time.

Imagine 3 borrowers:
<img width="473" height="99" alt="image" src="https://github.com/user-attachments/assets/3bfdd91a-dc29-4c41-89e8-4ce1c8430740" />

- Borrower B has the highest chance of default, but because the loan is small, the expected loss is relatively low.
- Borrower C has a lower probability of default than B, but if they do default, the bank is likely to lose a large amount because the loan is large and little can be recovered.

This shows why banks cannot rely only on the probability of default, they must also consider how much is at risk and how much can be recovered.

# 5. Credit Risk Assessment in Practice

7. Why Data Analytics Matters

8. Transition to the Dataset
