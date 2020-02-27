# Baltimore Salary -

Employers often make mistake of overpaying or underpaying their employees. This project uses Baltimore City employee salary data to check if the Baltimore government is making that mistake or not. The regression model checks if there is any correlation between the difference of Annual and Gross salaries from last year with the present year.
The correlation between the two can help us predict amount of overpayment or underpayment in next year. 

![](https://github.com/yash0602/Linear-Regression-/blob/master/p.png)

![](https://github.com/yash0602/Linear-Regression-/blob/master/r.png)

# Clustering 

I have clustered different departments based on 1) Overpay, 2) Medium, and 3) Underpay to make the data clear.

![](https://github.com/yash0602/Linear-Regression-/blob/master/an.png)

# Analysis 
The R-Squared value for the fitted model is 0.7 which makes it a good model. It also means that 70% of the data can be explained through this model. The standard error is of 9,687, which means that the prediction error could range from +/- $9,687. In simple words, next year (2020) Baltimore government can either over-pay or under-pay their employees given the range of $9687 v/s what they paid this year. 

# Steps 
1. Retrieved data of Baltimore Salary from Baltimore City Employee Salaries for year 2019,2018, and 2017
2. Used VLOOKUP function to extract all the data sets into a single Excel sheet 
3. Cleaned the data to remove all the NAs using filters 
4. Took the difference between Annual and Gross salaries for every year
5. Using Data Analysis, fitted a Linear Regression Model and analysed statistical factors like R Square value, F significance, Standard error, and P value.
6. For clustering I calculated the Mean, Variance, and the Z value.
7. Minimum distance was calculated using MIN() function 
8. I used Excel Solver to come up with optimal minimum value for the distance 

#Note 
1. Clustering gives different values for every iteration 
2. Data sets of newly joined employees (2019) was removed as previous years entries were blank

# Source 

The data was retrieved on 26th February 2020 from https://data.baltimorecity.gov/City-Government/Baltimore-City-Employee-Salaries-FY2019/6xv6-e66h
