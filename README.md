# Loan-Repayment-Prediction-using-Neural-networks-and-random-foerst-classifier
<h1>loan repayment Approval</h1>

![OIP](https://github.com/mohansharma077/Loan-Repayment-Prediction-using-Neural-networks-and-random-foerst-classifier/assets/104629829/cac4c81f-6ccc-4a6c-af8f-b48ec7a3f582)


<h1>Predicting whether an applicant is capable of repaying a loan</h1>
<p>As a bank decides which applicants to provide loans, they may wish to predict if the applicant will default on the loan. Through automated feature engineering, we can identify the predictive patterns in the financial data that can be used to ensure that clients capable of repayment are not rejected.</p>

![download](https://github.com/mohansharma077/Loan-Repayment-Prediction-using-Neural-networks-and-random-foerst-classifier/assets/104629829/654c5d61-3861-4f22-9a65-0750c5ee65ef)
<h2>Introduction</h2>

<li>The two most critical questions in the lending industry are: 1) How risky is the borrower? 2) Given the borrower’s risk, should we lend him/her? The answer to the first question determines the interest rate the borrower would have. Interest rate measures among other things (such as time value of money) the riskness of the borrower, i.e. the riskier the borrower, the higher the interest rate. With interest rate in mind, we can then determine if the borrower is eligible for the loan.</li>

<li>Investors (lenders) provide loans to borrowers in exchange for the promise of repayment with interest. That means the lender only makes profit (interest) if the borrower pays off the loan. However, if he/she doesn’t repay the loan, then the lender loses money.</li>

<li>We’ll be using publicly available data from LendingClub.com. The data covers the 9,578 loans funded by the platform between May 2007 and February 2010. The interest rate is provided to us for each borrower. Therefore, so we’ll address the second question indirectly by trying to predict if the borrower will repay the loan by its mature date or not.</li>

**Below is a short description of each feature in the data set:**</br>

credit_policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.

purpose: The purpose of the loan such as: credit_card, debt_consolidation, etc.

int_rate: The interest rate of the loan (proportion).

installment: The monthly installments ($) owed by the borrower if the loan is funded.

log_annual_inc: The natural log of the annual income of the borrower.

dti: The debt-to-income ratio of the borrower.

fico: The FICO credit score of the borrower.

days_with_cr_line: The number of days the borrower has had a credit line.

revol_bal: The borrower’s revolving balance.

revol_util: The borrower’s revolving line utilization rate.

inq_last_6mths: The borrower’s number of inquiries by creditors in the last 6 months.

delinq_2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.

pub_rec: The borrower’s number of derogatory public records.

not_fully_paid: indicates whether the loan was not paid back in full (the borrower either defaulted or the borrower was deemed unlikely to pay it back).

<h2>Proposing Model</h2>

![OIP](https://github.com/mohansharma077/Loan-Repayment-Prediction-using-Neural-networks-and-random-foerst-classifier/assets/104629829/3d36a736-c574-44fb-80ff-1700031be263)

![download](https://github.com/mohansharma077/Loan-Repayment-Prediction-using-Neural-networks-and-random-foerst-classifier/assets/104629829/ac195959-9bf1-4dbc-9441-0301d93716f7)

![download](https://github.com/mohansharma077/Loan-Repayment-Prediction-using-Neural-networks-and-random-foerst-classifier/assets/104629829/e84eb3cf-5e1a-454e-9209-1c89757c8bdf)


