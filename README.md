# Employee-Attrition
We are going to find major causes of attrition in employees. Attrition results in lack of productivity which reults in lack of profit ,which ultimately leads to unemployment. It seems simple to point out few factors behind attrition such as low wages, working environment,relationship with boss etc, but actually there are a lot more from one's personal reason to his education. And this is where Statistics come in. This field of concern is so wide thatit has given birth to new ML research called "Interpretability".

# Content
The data contains
* employee id
* employee record date ( year of data)
* birth date
* hire date
* termination date
* age
* length of service
* city
* department
* job title
* store number
* gender
* termination reason
* termination type
* status year
* status
* business unit

These might be typical types of data in hris
 
 # Data Cleaning
 * Remove the not useful columns ,Few of the predictors are useless carrying same value for all the observations ,thus having no significance in the desired output variable:
  'EmployeeCount' ,  'EmployeeNumber' ,  'Over18' , 'StandardHours
 * Removing Null values from data
 
 # Finding different relation between data
 Such as 
 * Department
 * Education
 * BusinessTravel
 * MaritalStatus
 
 # Training Model 
 * Logistic Regression
 * RandomForestClassifier
 * DecisionTree Clasifier
 * Gradiant Boosting
