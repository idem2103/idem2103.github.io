---
layout: default
title: "Week 6: Analysis II"
has_children: false
parent: "Assignments"
nav_order: 6
---

# Week 6: Analysis II

1. Consider a clinical trial designed to evaluate the effectiveness of a new drug for treating chronic pain. The researchers formulate their hypotheses as follows:

   **H0**: The new drug is no more effective than the placebo.

   **H1**: The new drug is more effective than the placebo.

   What statistical test is **most appropriate** for comparing the mean effectiveness between the two groups, **assuming normal distribution and equal variances**?

   1. _Chi-Square test_
   2. _Mann-Whitney U test_
   3. _Independent samples t-test_ <!--- Correct. --->
   4. _One-way ANOVA_

2. You are analyzing data from a study comparing the effects of different diets on weight loss. There are three diet groups in the study: Diet A, Diet B, and Diet C. You want to determine if there is a significant difference in the mean weight loss among the three diet groups. Which statistical test is **most appropriate** for this analysis, and why?

   1. _Independent samples t-test_
   2. _Paired samples t-test_
   3. _ANOVA_ <!--- Correct. --->
   4. _Chi-square test._

3. When preparing data for a parametric test, it's important to ensure certain assumptions are met for the validity of the test results. Which of the following is **NOT** an assumption of parametric tests?

   1. _The data must follow a normal distribution._
   2. _Observations must be independent._
   3. _Variances within groups must be equal (homoscedasticity)._
   4. _The dependent variable must be measured on an ordinal scale._ <!--- Correct. --->

4. Given the results of the ANOVA table below, which of the following interpretations can be derived?

   | Source       | Sum of Square | df  | Mean Square | F     | Significance |
   | ------------ | ------------- | --- | ----------- | ----- | ------------ |
   | Task type    | 2745.188      | 1   | 2745.188    | 1.410 | 0.242        |
   | Entry method | 17,564.625    | 2   | 8782.313    | 4.512 | 0.017        |
   | Task\*entry  | 114.875       | 2   | 57.437      | 0.030 | 0.971        |
   | Error        | 81,751.625    | 42  | 1946.467    | —     | —            |

   1. _'Entry method' significantly affects task completion times, but 'Task type' does not._ <!--- Correct. --->
   2. _Both 'Entry method' and 'Task type' significantly affect task completion times without any significant interaction._
   3. _'Task type' significantly affects task completion times, but 'Entry method' does not._
   4. _There is a significant interaction effect between 'Entry method' and 'Task type' that affects task completion times._

5. In an experiment to assess the impact of a new teaching method on student performance, the researcher decides to perform a Shapiro-Wilk test on the pre-test scores. What is the purpose of this test in this context?

   1. _To determine if the scores are homoscedastic._
   2. _To check the linearity of the scores._
   3. _To assess the normality of the distribution of scores._<!--- Correct. --->
   4. _To compare the mean scores of different groups._

6. In a study comparing the mean IQ scores of individuals in two distinct occupations, the researcher performs a Levene's test for equality of variances and obtains a **p-value of 0.045**. Considering **an alpha level of 0.05**, which of the following statements is true?

   1. _The variances are significantly different, indicating heteroscedasticity._<!--- Correct. --->
   2. _The variances are significantly, thus the condition of equal variances assumed._
   3. _Results suggest that non-parametric tests are unsuitable for further analysis._
   4. _The p-value is irrelevant to the assumptions of the t-test._

7. A researcher wants to compare the scores of two independent groups on a psychological well-being scale. Before choosing the appropriate statistical test, the researcher checks the score distribution and finds it to be **heavily skewed**. Which test is most appropriate for this scenario?

   1. _Independent samples t-test_
   2. _Paired samples t-test_
   3. _Mann-Whitney U test_<!--- Correct. --->
   4. _ANOVA_

8. Devise an analysis plan for an A/B testing study aimed at evaluating the effectiveness of two web page designs, Design A and Design B, in terms of user engagement. In your plan, outline the steps for ensuring the assumptions of the statistical tests are verified. Additionally, describe how you would proceed with the analysis if these assumptions are met as well as the approach you would take if they are violated.
