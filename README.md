# Bank of Canada Collateral and Pledging Report 
## Background Information 
The purpose of this report is to provide the Bank of Canada with data on collateral pledging which is necessary for evaluating linkages between counterparties and activities, as well as determining the magnitude of transactions across various asset classes. 

This return is to be completed at the business day frequency. Business days are defined to include all weekdays except federal and provincial statutory holidays. The attached template identifies a selection of rows and columns which are only required to be updated as of month end. Values are required to be reported in these cells for every business day; however, previous values can be carried forward until month end is reached. 

The template for this return has been provided in “objectives” section 

**[Definition for asset types]**
* **Level 1 Asset**: Government Bond
* **Level 2 Asset**: Non-financial corporate bond/equity, with credit rating between A and AAA.
* **Level 3 Asset**: Financial corporate bond/equity, or non-financial corporate bond/equity with credit rating under A. 
* 
Note that we rank credit ratings from **high to low** as following: 

AAA, AA+, AA, AA-, A+, A, A-, BBB+, BBB, BBB-, BB+, BB, BB-, B+, B, B-, etc.

## Objective
Our objective is to fill in the report template as requested by Bank of Canada:
![image](https://user-images.githubusercontent.com/83738852/214911027-8b6be3a1-3243-4f62-b3a1-5aa40c2a99c8.png "Figure I: Final Report Template from Bank of Canada") 

*Figure I: Final Report Template from Bank of Canada*

## Inputs
The inputs provided as following:
* **Collateral transactions as of Jul 2020**. (“*Collateral_Transaction.csv*") 
![image](https://user-images.githubusercontent.com/83738852/214911461-de9956e7-378a-48bc-8ced-72d9bd6be53b.png "Figure II: Collateral transactions source file (sample).")

*Figure II: Collateral transactions source file (sample).*

* **Security instrument details**. (“*Security.csv*") 
![image](https://user-images.githubusercontent.com/83738852/214911670-597ab252-2f8e-4ec3-98f2-da1ced023804.png "Figure III: Security instruments source file (sample).")

*Figure III: Security instruments source file (sample).*

* **Counterparty details**. ("*Customer.csv*") 

![image](https://user-images.githubusercontent.com/83738852/214911821-afa83817-80ee-4f3e-b0c9-1687a35e7615.png "Figure IV: Counterparty source file (sample)") 

*Figure IV: Counterparty source file (sample)*

## Tools
SQLite Studio, Excel
