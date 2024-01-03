Author:

# Ryan Ellis
# Problem Statement

We are tasked to create a model that would predict if a specific customer would purchase an add or not, based on a set of features they have. 
    


[Notebook](https://github.com/ryanellis5/logregads/blob/main/project_advertisement_classifier.ipynb)


**Data dictionary** 
Data dictionary for [advertisments.csv](https://github.com/ryanellis5/logregads/blob/main/advertisments.csv):


				
|Feature|Type|Description|
|---|---|---|
|**User ID**|*int64*|ID of the Person|
|**Gender**|*object*|Male or Female|
|**Age**|*int64*|age of the person|
|**EstimatedSalary**|*int64*|Estimated Salary |
|**Purchased**|*int64*|if the person bought the advertisment or not|


# Executive Summary 
1. Import libraries
2. Import data
3. Look at data types
4. One hot encoded gender column
5. Instantiate logistic regression
6. Fit the regression
7. Get score (AUC = 0.737541528239202)
8. Scale features using a Standard Scalar
9. Instantiate new logistic regression on new scaled data
10. Get score (AUC = 0.933856840833585)
Scaled data is much better so I would suggest scaling data before running a regression on it. 
