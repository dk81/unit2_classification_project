# Unit 2 - Classification Project

This contains a project where machine learning classification is done for
a school program.

&nbsp;

---

# Contents

* Project Brief
* Dataset Information
* My Data Analysis Strategy
* Number Of Churns By Contract (Image)
* Survival Analysis Kaplan-Meier Usage & Insights
* Decision Tree Model
* K-Nearest Neighbours Model
* Logistic Regression Model
* Recommendations For Reducing Customer Churn


&nbsp;

---

# Project Brief

Given a telecomunnications dataset, the company would like to know which
customers are likely to leave (churn). A plan also needs to be developed
in an attempt to keep customers from leaving/churning.

* Presentation and analyses is for a (hypothetical) marketing and operations team.

* Telco profits are mostly from cellular plans and overage fees.

* In a competitive telco market, customers can easily switch service providers as they may think the grass is greener on the other side. A loyal customer helps with maintaining cash flows and gaining market share on its competition.

* Data plans not known.

* Telco company is based in the USA.

&nbsp;

---

# Dataset Information

* 7043 customers in the dataset for US Telcom. Business.
* Two services : Phone, Internet (DSL / Fiber Optic).
* Contract Plans: Month-To-Month, One Year, Two Year 
* Variables Of Interest: MonthlyCharges, Tenure (Time In Months), Contract.

&nbsp;

---

# My Data Analysis Strategy

I wanted to explore different classifcation models for customer churn. Three classification models were explored in the notebook.

* K-Nearest Neighbours
* Decision Trees
* Logistic Regression (Ridge, LASSO, ElasticNet)

&nbsp;

## Number Of Churns By Contract (Image)

The image shown below shows that month to month customers churn the most.

![ChurnCounts](churnCounts_contract.png)

&nbsp;

## Survival Analysis Kaplan-Meier Usage & Insights

Survival analysis Kaplan Meier Curves were included to showcase the difference in contract plan groups and their churns. The event of interest is Churn and the time is the customer tenure time.

The probability of a month-to-month customer staying with the telco company is lower versus those who are in one-year or two-year plans.

<put_image>

&nbsp;


# Decision Tree Model




&nbsp;

# K-Nearest Neighbours


&nbsp;

# Logistic Regression




&nbsp;

# Recommendations For Reducing Customer Churn

* Many churns are from month to month customers with tenure times at most at 6 months.
* Can offer one or two year promo plans to existing mth-mth customers during customer’s 5th month. (E-Mail)
* Suugest a promo offer for customers to sign up for one/two year plans one month from end of one/two year contract. 
* Look at month-to-month and > $68 / mth. cases more closely. (1747 Churns)
* Look into internals such as customer service, signal service, competitor pricing.


