### Project Title = Electric Vehicle Charging Analysis

**by Rajesh Radhakrishnan (Feb 2025)**

#### Executive summary

#### Rationale
Why should anyone care about this question?

The cost of electric vehicle charging is based on the energy consumed for the charging session. Based on the regression model 
formulated in this project, the amount of energy consumed can be predicted based on the change in the state of charge and the 
peak rate of charging thus providing an estimate to the user of the charging cost for the session.

#### Research Question
What are you trying to answer?

What is the relationship between Energy used for charging (Wh) and the characteristics of the Electric Vehicle's Battery?

#### Data Sources
What data will you use to answer you question?

Dataset: https://github.com/DESL-EPFL/Level-3-EV-charging-dataset/blob/main/Session_data.xlsx

#### Methodology
What methods are you using to answer the question?

Regression Analysis, Classification algorithms like Logistic Regression, KNN, DecisionTrees and Support Vector Machines

#### Results
What did your research find?

The regression analysis indicates that the Energy Wh has a positive relationship with the Energy Capacity, Max Power Requested 
and the change in the State of Charge. The coefficients on the variables CCS1 and CCS2 (type of plug for charging) are also positive. 
The Energy Wh for charging can thus be estimated from these variables prior to charging (a good estimate of the Change in State of 
Charge required for the Battery can be determined) and thus it can be used to calculate the cost of the EV Charging session.

#### Next steps
What suggestions do you have for next steps?

#### Outline of project

- [Link to notebook 1]()
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information