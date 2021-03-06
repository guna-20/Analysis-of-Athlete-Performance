# Analysis-of-Athlete-Performance
Predicting-Athlete-Performance
An athlete performance can be determined by many factors such as height, age, and weight. Hence, we analyse which of these factors affect the performance of the athlete the most. Here we use statistical methods like correlation, regression and hypothesis testing. This project helps us to predict the chance of winning in the Olympic games and also helps to choose the most appropriate one among all the athletes by a country for the Olympic games.

# METHODOLOGY

We use R language and MS Excel for this project. First using MS Excel, we filtered our dataset which contained unwanted data’s like name, nationality, year. In R, we have stored the data of each sport in an index of a list. Then we get input from the user to select the sports we want to know about. After the sports is selected by the user, the p value is checked for the variables. Further analysis can be done only if the p-value is lesser than 0.5. This ensures that there is a strong relationship between the variables and further analysis carried out will be correct. Next we plot correlation matrix and scatter plot to know the relation between medals and age, height and weight. Then finally we find the regression equation so the end user can simply give in age, height and weight inputs and can select the highest value for medal.

# TECHNIQUES USED IN STATISTICS:

1.Correlation

2.Regression

3.P-value

# FUNCTIONS USED IN R:

1.pairs.panel()

2.lm()

3.summary()

Correlation: Correlation is a statistical technique that can show whether and how strongly pairs of variables are related. For example, height and weight are related; taller people tend to be heavier than shorter people. Like all statistical techniques, correlation is only appropriate for certain kinds of data. Correlation works for quantifiable data in which numbers are meaningful, usually quantities of some sort. It cannot be used for purely categorical data, such as gender, brands purchased, or favourite colour. The correlation coefficient that indicates the strength of the relationship between two variables can be found using the following formula:

Where: • rxy – the correlation coefficient of the linear relationship between the variables x and y • xi – the values of the x-variable in a sample • x̅ – the mean of the values of the x-variable • yi – the values of the y-variable in a sample • ȳ – the mean of the values of the y-variable

Regression: In statistical modelling, regression analysis is a set of statistical processes for estimating the relationships between a dependent variable (often called the 'outcome variable') and one or more independent variables (often called 'predictors', 'covariates', or 'features'). The most common form of regression analysis is linear regression, in which a researcher finds the line (or a more complex linear function) that most closely fits the data according to a specific mathematical criterion.

Multiple linear regression analysis is essentially similar to the simple linear model, with the exception that multiple independent variables are used in the model. The mathematical representation of multiple linear regression is: Y = a + bX1 + cX2 + dX3 + ϵ

Where: • b, c, d – slopes • Y – dependent variable • X1, X2, X3 – independent (explanatory) variables • a – intercept • ϵ – residual (error)

P-Values: The p-value for each term tests the null hypothesis that the coefficient is equal to zero (no effect). A low p-value (< 0.05) indicates that you can reject the null hypothesis. In other words, a predictor that has a low p-value is likely to be a meaningful addition to your model because changes in the predictor's value are related to changes in the response variable. Conversely, a larger (insignificant) p-value suggests that changes in the predictor are not associated with changes in the response. The variables used in this test are: • Dependent variable : Medal • Independent variable : Age, Height and Weight

# How to Run

Download the code.R file and the dataset (Extract the athlete_events.rar) to the same directory.

Run the first line of the code seperately i.e., Give the input seperately. For example, Enter the sport : Taekwondo

After giving the input, run the remaining lines of the code.
