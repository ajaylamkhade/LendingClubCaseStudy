# Lending Club Case Study
> Lending Club Case Study - Possible Driving Factors Behind The Loan Default.

![loan_image](https://user-images.githubusercontent.com/42746311/51308684-acd3e680-1a68-11e9-838d-f24825a1de16.png)

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
- The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default
- Data set has 39717 rows and 111 columns. 
- Data set consist of relevant information of loan characteristics and customer behavior variables

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
We cannot simply consider one or two variables to predict the default. We have defined 14 parameters which need to be considered while giving a loan. In an a application if more than 5 matching parameters are there then we should avoid giving loan for such applications, Only few are mentioned here

- term - Loan tenure selected is 60 months
- loan_amnt - Loan amount is 15K or above
- grade - Grades given by LC are C,D,E,F or G
- verification_status - Verification status is Verified
- add_state - States are one of the following CA, FL or NV
- annual_income - Annual income is 10K or less than 10K
- inq_last_6mths - 2 or more inquiries in last 6 months

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies & Libraries Used
- numpy - 1.21.6
- pandas - 1.3.5
- seaborn - 0.12.2
- matplotlib - 3.1.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
  Give credit here:
- https://www.geeksforgeeks.org/multi-plot-grid-in-seaborn/
- https://stackoverflow.com/questions/51070985/find-out-the-percentage-ofmissing-values-in-each-column-in-the-given-dataset
- https://www.geeksforgeeks.org/select-columns-with-specific-data-types-inpandas-dataframe/
- https://www.geeksforgeeks.org/how-to-set-a-seaborn-chart-figure-size/
- https://stackoverflow.com/questions/63373194/how-to-plot-percentage-with-seaborn-distplot-histplot-displot
- https://seaborn.pydata.org/generated/seaborn.histplot.html
- https://seaborn.pydata.org/generated/seaborn.pairplot.html
- https://stackoverflow.com/questions/56942670/first-and-last-row-cut-in-half-of-heatmap-plot


## Contact
Created by [@ajay_lamkhade and @nachiket_sali] - Please feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

