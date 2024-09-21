# Transport-Prefrence-ML
## Problem Statment 1:
### Context:
#### You are in discussions with ABC Consulting company for providing transport for their employees. For this purpose, you are tasked with understanding how do the employees of ABC Consulting prefer to commute presently (between home and office). Based on the parameters like age, salary, work experience etc. given in the data set ‘Transport.csv’, you are required to predict the preferred mode of transport. The project requires you to build several Machine Learning models and compare them so that the model can be finalized.
### Objective
#### The objective is to build various Machine Learning models on this data set and based on the accuracy metrics decide which model is to be finalized for finally predicting the mode of transport chosen by the employee.
### Data Dictionary
#### Age: Age of the Employee in Years
#### Gender: Gender of the Employee
#### Engineer: For Engineer =1 , Non Engineer =0
#### MBA: For MBA =1 , Non-MBA =0
#### Work Exp: Experience in years
#### Salary: Salary in Lakhs per Annum
#### Distance: Distance in km from Home to Office
#### license: If Employee has Driving Licence -1, If not, then 0
#### Transport: Mode of Transport
### Observations
#### Comparing all the performance measure, Random Forest model is performing the best. Although there are some other models which is performing almost same as that of Random Forest. But AdaBoost Classifier is very consistent when train and test results are compared with each other. Along with other parameters such as Recall value, Precision etc, those results were pretty good is this model.
- Over 60% of workers say they would rather use public transportation than their own vehicle.
- When it comes to public transportation, men prefer it over women.
- As one gets older and has more work experience, the preference for private transportation grows.
- It is more common for employees with less job experience to favor public transportation.

    ![image](https://github.com/user-attachments/assets/4b9bfaa4-9a28-425a-931c-7f19210418e1)


#### Figure shows that "Age" is the most crucial factor in determining the chosen mode of transportation. This makes sense because experience increases with age. Thus, it can be said that workers in higher positions have a preference for private transportation, whereas those with less and intermediate experience have a preference for public transportation.

## Problem Statment 2: -
### Context
#### A dataset of Shark Tank episodes is made available. It contains 495 entrepreneurs making their pitch to the VC sharks. You will ONLY use “Description” column for the initial text mining exercise.

   ![image](https://github.com/user-attachments/assets/3d0bb228-4758-4fbc-8ce1-f982a4826306)
Word Cloud of Secured Deals

   ![image](https://github.com/user-attachments/assets/5bec2592-1f75-4c48-b991-2dda6df11d18)
Word Cloud of Deals Not Secured

