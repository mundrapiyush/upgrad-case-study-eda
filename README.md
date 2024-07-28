# Lending Club Case Study Notebook


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information


### Problem Context
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

### Problem Outcome

To minimize the risk of losing money while lending to customers, analyze the existing data to identify the variables that are strong indicators of loan default. 

### Loan Data Set  
It contains the complete loan data for all loans issued through the time period 2007 t0 2011.

### Data Dictionary
The data dictionary that describes the meaning of the columns present in the dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
**Minor Impact**

- Higher loan amount (above 15k)

- Applicant’s address state (NV, SD, AK, ID, NE)

- Higher debt to income ratio (above 15%)

- Credit utilization rate (above 50%)

**Major impact**

- Loan purpose (small business, renewable energy, educational)

- Loan Tenure ( 5 year loans tends to cause more defaults)

- Public bankruptcy records (1 or 2)

- Higher interest rate (above 20%)

- Loan grade & sub-grade (E, F, G)

- Higher DTI's affect the payment of Higher Loan Amounts

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- Data Analysis Library
    - pandas
- Visualization Libraries 
    - matplotlib
    - seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->