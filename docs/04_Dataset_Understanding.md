## Dataset Overview

### Source
Lending Club Loan Data from Kaggle

https://www.kaggle.com/datasets/adarshsng/lending-club-loan-data-csv?resource=download 

### Description
Lending Club dataset is publicly available and shows a realistic dataset that contains historical loan application and final loan outcome (whether borrowers repaid or defaulted). This allows us to develop and evaluate credit risk model without needing access to confidential data.

Lending Club is a platform that published large amounts of anonymized historical loan data which closely resembles the type of information a retail bank. Thus, Lending Club is appropriate to act as a stand-in for a retail bank's internal loan database.

### Number of observations
1,048,576 loan applicants

### Number of variables
145 columns

### Time period
NA

### Target variable
loan status (Did the borrower repay?)

## Variable Categories

### Applicant Information (Who is applying?)
emp_length
emp_title
home_ownership
annual_inc
verification_status
addr_state
zip_code

### Loan Information (What kind of loan is the bank issuing?)
loan_amnt
funded_amnt
funded_amnt_inv
term
int_rate
installment *not found*
purpose
grade
sub_grade

### Credit History (Has the borrower handled credit responsibly in the past?)
delinq_2yrs
earliest_cr_line
inq_last_6mths
open_acc
pub_rec
revol_bal
revol_util
total_acc
mort_acc *not found*

### Financial Health (Can this borrower afford another loan?)
dti
tot_cur_bal
tot_hi_cred_lim
total_bal_ex_mort

### Loan Outcome
loan_status

## Initial Business Hypotheses
1. Higher DTI leads to higher default rates	> Borrowers with higher debt burdens may struggle to repay.
2. Lower annual income increases default risk	> Lower income may reduce repayment capacity.
3. Longer loan terms are associated with higher default rates > Borrowers face more uncertainty over longer repayment periods.
4. Higher interest rates are associated with higher default rates >	Larger monthly payments may increase financial strain.
5. More past delinquencies increase default risk > Previous repayment behavior is often predictive of future behavior.
6. Lower revolving credit utilization is associated with lower default risk >	Borrowers using less of their available credit may be in a stronger financial position.
