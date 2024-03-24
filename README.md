#### 2012-Obama-Voters-Participants-of-the-General-Social-Survey-GSS

##### data from package(socviz)
[Lab_Assignment_2_by_Yiqiu_Wang.pdf](https://github.com/Yiqiu-W/2012-Obama-Voters-Participants-of-the-General-Social-Survey-GSS/files/14735806/Lab_Assignment_2_by_Yiqiu_Wang.pdf)

##### the predictors of voting for Barack Obama in the 2012 US presidential election.

#### Data Preparation and Description:

##### Prepare Data:

##### Create a new variable for religion with categories: Catholic, Protestant, Other, and None (keeping NAs). Generate a new variable indicating if either parent has a bachelor or graduate degree. Filter data for non-missing values in the religion, education, obama, age, and sex variables.

##### Describe Sample:

##### Calculate descriptive statistics for the new religion and education variables, age, sex, and obama. Present shares of observations for categorical variables and mean/standard deviations for continuous ones. Perform analysis for the full sample and separately for Obama and non-Obama voters.

##### Brief Discussion:

##### Discuss the composition of the sample across religion, education, age, sex, and Obama voting status.

#### Model Estimation and Odds Ratios:

##### Logistic Regression Models:
##### a) Religion variable only.
##### b) Religion and parental education variables.
##### c) Religion, parental education, sex, and age variables.

##### Presentation:

##### Show odds ratios with confidence intervals for all three models in a single table. Include key model statistics (N, log-likelihood) at the bottom of the table. Present odds ratios from Model c in a graph without the intercept, with confidence intervals.

##### Discussion:

##### Interpret results of logistic regression models, considering the impact of religion, education, sex, and age on voting for Obama.

#### Predicted Probabilities:

##### Graphical Visualization:

##### Plot predicted probabilities of voting for Obama at different ages for each religion category.Base predictions on Model c, assuming a female with at least one college-educated parent.

##### Discussion:

##### Interpret how predicted probabilities vary across age and religion categories, considering parental education.

#### Model Fit:

##### Nested Models:

##### Explain nesting relationships between models a, b, and c. Perform likelihood ratio tests comparing model b to model a and model c to model b.

##### Fit Statistics:

##### Calculate Nagelkerke’s pseudo-R2 and share of correctly predicted observations for all three models. Present fit statistics in a well-formatted table.

##### Discussion:

##### Interpret results of model fit comparisons, assessing the improvement in model fit with added variables.
