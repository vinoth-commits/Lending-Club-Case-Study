# Project Name
> Lending Club Project case study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Libraries Used](#libraries-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

      As the largest online loan marketplace, the company specializes in facilitating personal, business, and medical loans.
      Borrowers can conveniently obtain lower interest loans through a streamlined online interface.


      Lending loans to risky applicants is the largest source of financial loss.
      Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.
      Identification of such applicants using exploratory data analysis (EDA) is the aim of this case study.


      Aim of the project:
            The study focuses on identifying factors that may contribute to loan applicants defaulting on their payments. 
            The company wants to understand the driving factors behind loan default.  i.e. the variables which are strong indicators of default.  
            The company can utilise this knowledge for its portfolio and risk assessment. 

      Dataset used:
            loan.csv - the dataset contains all the details of loans applied from 2007 through 2011.


## Conclusions

- Conclusion 1: 

  Summary of Univariate Analysis:

      1. Applicants with rented homes accounted for the highest defaults (50%).

      2. Debt consolidation loans led to the most defaults (49%).

      3. Borrowers with an interest rate between 11% to 17% had the highest default rate.

      4. Loans in the amount range of 5000 to 10000 were most prone to default.

- Conclusion 2:

  Summary of Derived Metrics:

      1. Type-driven Metric: Applicants with 10+ years of experience account for 28% of defaults, the highest among experience groups.

      2. Business-driven Metric: Loans issued in December have the highest default rate.
      
      3. Data-driven Metrics:

            Applicants with an annual income between 30,000 and 60,000 defaulted the most.
            
            Interestingly, those in the lower income range (1,000 to 30,000) showed fewer defaults.
            
            Borrowers with a monthly debt-to-income ratio of 10% to 20% had the highest default rate.

- Conclusion 3:

  Summary of Bivariate Analysis:

      1. Annual Income vs Loan Purpose: The highest default rates are seen in loans for credit cards, small businesses, home improvement, and house mortgages.

      2. Annual Income vs Debt-to-Income (DTI) Ratio: Borrowers with incomes between 30000 and 70000 and a DTI ratio between 15% and 25% show debt management issues.

      3. Loan Amount vs Annual Income: A moderate positive correlation (0.41) indicates that as annual income increases, the loan amount tends to rise as well.

      4. Loan Amount vs Grade: High default rates are observed when the loan grade is F or G and the loan amount exceeds 17000.

- Conclusion 4:

  Summary of Multivariate Analysis: 

      1. Small business loans show a high rate of default.

      2. Credit card and debt consolidation loans are at a significant risk of default, with many borrowers on the verge of defaulting.




## Technologies Used
* Python3


## Libraries Used
| Package       | Version       |
| ------------- |:-------------:|
| pandas        | 2.1.4         |
| cmatplotlib   | 3.8.0         |
| seaborn       | 0.12.2        |
| scipy         | 1.11.4        |




## Acknowledgements
Credit:
      * Vishal Sinha
      * Vinoth Kumar

```
References:
- https://pandas.pydata.org/
- https://matplotlib.org/
- https://seaborn.pydata.org/
```


## Contact
Created by [https://github.com/vinoth-commits] - feel free to contact me!
