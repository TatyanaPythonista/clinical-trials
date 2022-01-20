# Clinical trials

Definition of Odds Ratio to get well after different treatment.

[Download Data here](https://cloud.mail.ru/public/QetG/9b9QEZLS5)

## Describtion of data

* SITEID and SUBJID – variables  that identifies subject
* TRTPN – treatment code (1 or 2)
* Response Category – best response achieved by subject as a result of treatment exposure (CR – Complete Response, PR – Partial response, SD – Stable Disease,  PD – Progressive Disease, NE – Not Evaluable). Subjects are considered as having response to treatment if they have CR or PR and non-responders in all other cases for analysis purpose.
* Gender – Gender of the subject

## Task
1. Create logistic regression model with Response (responder / non-responder binomial variable, where response is an event) as dependent variable and Intercept and Treatment as independent variables.

- Report an odds ratio derived from this model of treatment 1 over treatment 2.

- Give a definition of Odds Ratio.

- Give definition of confidence interval

- How it is related with regression coefficients estimated in this model?

2. Create logistic regression model with Response (responder / non-responder binomial variable, where response is an event) as dependent variable and Intercept, Treatment, Gender and Treatment*Gender (interaction of Treatment and Gender) as independent variables.

- Report an 4 conditional odds ratio derived from this model:

    treatment 1 vs treatment 2 | Male

    treatment 1 vs treatment 2 | Female

    Female vs Male | treatment 1

    Female vs Male | treatment 2.

- How these 4 odds ratio are related to estimated coefficients?

            - Report pvalue for interaction (of Treatment*Gender) significance.

            - Give definition of the pvalue.

- Based on this pvalue – do we need to update model (simplify it)? Why?
