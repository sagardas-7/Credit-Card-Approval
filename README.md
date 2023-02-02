<h1>Introduction</h1>

A credit score is a number between 300–850 that depicts aconsumer's creditworthiness. The higher the score, 
the better aborrower looks to potential lenders. A credit score is based on credithistory: number of open accounts, total levels of debt,
and repaymenthistory, and other factors.
Banks receive a lot of applications for issuance of credit cards. Many of them are rejected for many reasons, 
like high-loan balances,low-income levels, or too many inquiries on an individual’s creditreport which determines the credit score.

<h1>Business Problem</h1>

Manually analyzing these applications is error-prone and atime-consuming process. Luckily, this task can be automated with thepower
of machine learning and pretty much every bank does sonowadays. In this project, we will build an automatic credit cardapproval predictor 
using machine learning techniques, just like the real banks do.

<h1>ML formulation of the business problem</h1>
The dataset consists of:
<br>
<h3>a. application_record.csv</h3> This table contains details about the background of thecustomer like annual income,
type of employment, numberof days employed, occupation type, number of childrens,number of family members, education qualification,
owns acar or not, owns a real estate or not, type of housing.
<br>

<h3>b. credit_record.csv</h3> This table contains the data related to a customers(id) 
pastcredit records which contains the month of the extracteddata and the status of the due. Status explains about thenumber of days 
that his debt is due.
<br>
i.id-clientnumber
<br>
ii.month_balance -The month of the extracted data isthestarting point, backwards, 0 is the current month, -1 is theprevious month, and so on
<br>
iii.status - 0: 1-29 days past due 1: 30-59 days past due 2:60-89 days overdue 3: 90-119 days overdue 4: 120-149days overdue 5: Overdue or bad debts, 
write-offs for morethan 150 days C: paid off that month X: No loan for themonth

<br>
<br>
Depending on these given inputs we will have to determine whether or not a credit card application will get accepted or not.


<h1>Blog Link</h1>
https://medium.com/@sagardas7.1998/credit-card-approval-prediction-using-machine-learning-8c0f55a76a5f

<h1>Author</h1>
Sagar Das
<br> Contact Details: +91 900778474
