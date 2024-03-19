---
layout: default
title: "Week 7: Analysis III"
has_children: false
parent: "Assignments"
nav_order: 7
---

# Week 7: Analysis III

---

### Questions 1, 2, 3

---

**Model Summary:**

| Model | R      | R Square | Adjusted R Square | Std. Error of the Estimate |
| ----- | ------ | -------- | ----------------- | -------------------------- |
| 1     | .873^a | .762     | .749              | 874.779                    |

_a. Predictors: (Constant), Income_

**ANOVA^a**

| Model | Sum of Squares | df          | Mean Square | F           | Sig.   |        |
| ----- | -------------- | ----------- | ----------- | ----------- | ------ | ------ |
| 1     | Regression     | 44182633.37 | 1           | 44182633.37 | 57.737 | .000^b |
|       | Residual       | 13774291.07 | 18          | 765238.393  |        |        |
|       | Total          | 57956924.44 | 19          |             |        |        |

_a. Dependent Variable: Price_

_b. Predictors: (Constant), Income_

**Coefficients^a**

| Model        | Unstandardized Coefficients |            | Standardized Coefficients |       |      |
| ------------ | --------------------------- | ---------- | ------------------------- | ----- | ---- |
|              | B                           | Std. Error | Beta                      | t     | Sig. |
| 1 (Constant) | 8286.786                    | 1852.256   |                           | 4.474 | .000 |
| Income       | .564                        | .074       | .873                      | 7.598 | .000 |

_a. Dependent Variable: Price_

Considering the above SPSS output of a simple linear regression, answer the following three questions (1, 2 and 3).

1. According to SPSS output above, what does the R-squared (R²) value of .762 in the model summary indicate about the regression model?

   1. _76.2% of the variance in the dependent variable, Price, can be explained by the independent variable, Income._ <!--- Correct. --->
   2. _The regression line passes through 76.2% of the data points._
   3. _Income accounts for 76.2% of the Price._
   4. _The correlation between Income and Price is 76.2%._

2. According to SPSS output above, considering the p-value associated with the F-statistic in the ANOVA table, what can be concluded about the regression model?

   1. _The model is not statistically significant, and Income does not predict Price._
   2. _The model is statistically significant, but the relationship is weak._
   3. _The model is statistically significant, suggesting the regression model provides a good fit to the data._ <!--- Correct. --->
   4. _There is not enough information to determine the statistical significance of the model._

3. According to SPSS output above, based on the coefficients table, if Income increases by 1000 units, how much change would you expect in Price, keeping all other factors constant?

   1. _It would increase by 564 units._ <!--- Correct. --->
   2. _It would increase by .564 units._
   3. _It would increase by 8286.786 units._
   4. _It would decrease by .564 units._

---

### Questions 4, 5, 6

---

**Model Summary:**

| Model | R      | R Square | Adjusted R Square | Std. Error of the Estimate |
| ----- | ------ | -------- | ----------------- | -------------------------- |
| 1     | .910^a | .828     | .820              | 5.234                      |

_a. Predictors: (Constant), Number of Features Used, Ease of Navigation, Visual Appeal_

**ANOVA^a**

| Model      | Sum of Squares | df  | Mean Square | F       | Sig.   |
| ---------- | -------------- | --- | ----------- | ------- | ------ |
| Regression | 1234.567       | 3   | 411.522     | 153.401 | .000^b |
| Residual   | 5678.910       | 96  | 59.155      |         |        |
| Total      | 6913.477       | 99  |             |         |        |

_a. Dependent Variable: Time Spent on App_

_b. Predictors: (Constant), Number of Features Used, Ease of Navigation, Visual Appeal_

**Coefficients:**

| Model | Variable                | B     | Std. Error | Beta | t     | Sig. | 95% Confidence Interval for B |
| ----- | ----------------------- | ----- | ---------- | ---- | ----- | ---- | ----------------------------- |
| 1     | (Constant)              | 2.056 | 1.320      |      | 1.558 | .123 | [0.432, 3.680]                |
| 1     | Number of Features Used | 1.742 | 0.268      | .511 | 6.500 | .000 | [1.210, 2.274]                |
| 1     | Ease of Navigation      | 3.310 | 0.415      | .600 | 7.976 | .000 | [2.490, 4.130]                |
| 1     | Visual Appeal           | 2.088 | 0.521      | .401 | 4.008 | .000 | [1.050, 3.126]                |

_a. Dependent Variable: Time Spent on App_

Considering the above SPSS output of a multiple linear regression, answer the following three questions (4, 5 and 6).

4. Based on the SPSS output above for a multiple linear regression analysis with 'Time Spent on App' as the dependent variable, which of the following statements is correct?

   1. _The visual appeal of the app does not significantly affect the time users spend on the app, as indicated by the high significance level._
   2. _User engagement, as measured by time spent on the app, is most strongly influenced by the number of features used during a session._
   3. _Ease of navigation is negatively related to the time spent on the app, meaning as navigation becomes easier, users spend less time on the app._
   4. _The adjusted R Square value indicates that over 82% of the variance in the time users spend on the app can be explained by the number of features used, ease of navigation, and visual appeal combined._ <!--- Correct. --->

5. Given the hypothetical SPSS output for a multiple linear regression with 'Time Spent on App' as the dependent variable, what can be inferred about the importance of 'Ease of Navigation' as a predictor?

   1. _'Ease of Navigation' is an insignificant predictor since its coefficient is smaller than that of 'Visual Appeal'._
   2. _The t-value for 'Ease of Navigation' being the highest among predictors indicates it is the most statistically significant predictor of 'Time Spent on App'._ <!--- Correct. --->
   3. _'Ease of Navigation' has no predictive power as its confidence interval includes zero._
   4. _'Ease of Navigation' has a Beta value of .600, indicating it contributes to a 60% increase in 'Time Spent on App' for each unit increase in its score._

6. What does the significance value (Sig.) imply for the 'Number of Features Used' coefficient in relation to 'Time Spent on App'?

   1. _The Sig. value of .000 for 'Number of Features Used' suggests that it is statistically insignificant and should not be considered in the model._
   2. _Since the Sig. value is .000, it implies that the 'Number of Features Used' has no effect on 'Time Spent on App'._
   3. _The 'Number of Features Used' is highly significant in predicting 'Time Spent on App', as indicated by a Sig. value of .000._ <!--- Correct. --->
   4. _A Sig. value of .000 indicates that 'Number of Features Used' negatively impacts 'Time Spent on App'._

---

---

7. If the Pearson correlation coefficient between two variables is 0.8, what can we conclude?

   1. _There is a strong positive linear relationship between the variables._ <!--- Correct. --->
   2. _There is a strong negative linear relationship between the variables._
   3. _One variable can be perfectly predicted from the other variable._
   4. _The relationship between the variables is non-linear._

8. One of the key differences between correlation and regression is that:

   1. Correlation quantifies the strength of the relationship, while regression quantifies the direction. <!--- Correct. --->
   2. Correlation assumes the independent variable is fixed, while regression treats both variables as random.
   3. Correlation is a single statistic, while regression produces an equation.
   4. Correlation is symmetric, while regression is asymmetric with respect to the independent and dependent variables

9. You are examining the relationship between users' ratings for 'Ease of Use' and 'Overall Satisfaction' for a newly released mobile application. You calculate both Pearson and Spearman correlation coefficients. The Pearson correlation coefficient is 0.65, while the Spearman correlation coefficient is 0.85. What can you infer from these results?

   1. _The relationship between 'Ease of Use' and 'Overall Satisfaction' is perfectly linear since both correlation coefficients are positive._
   2. _The higher Spearman correlation suggests that the relationship between the variables is monotonic but not necessarily linear._ <!--- Correct. --->
   3. _The discrepancy between the Pearson and Spearman coefficients indicates that there must be a calculation error._
   4. _A lower Pearson correlation suggests that 'Ease of Use' does not affect 'Overall Satisfaction' at all._
