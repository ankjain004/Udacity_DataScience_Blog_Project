# Udacity : DataScience_Blog_Project&Post

# Project Overview

Objective of this project is to apply Data Science principles and follow CRISP-DM process at every stage of project life cycle to have presentable deliverables.
Project implementation is performed under the umbrella of Udacity Data Scientist Nanodegree Project.

# Source of DataSet
https://insights.stackoverflow.com/survey

# Project LifeCycle

CRISP-DM (Cross Industry Standard Process for Data Mining)

## Business Understanding

Stack Overflow 2017 is golden source data and used as baseline to perform various analysis. Though data can be analyzed at various angles and prospects but here we focused on following questions

1. **Diversity & Inclusion is an big initiative in many organizations which helps to improve gender ratio and empower Women.** 

- How is the response from Female respondents?
- What is Job/Career Satisfaction rating by existing Female respondents?  
- What are preferrable Job roles ? How does education impacts professional life of Female respondents? 
- Which scale of companies successfully implented D&I?

2. **Technology plays big role into Industry and the way it is evolving, biggest challenges is to cope with new technology to have professional growth.** 

- Which Development Framework,databases, languages are being used by professionals and what is in their to-do list for learning to get better opportunity?

3. **Stack Overflow has collected responses inline with Job Assessment which helps companies to understand & introduce or improve policies to handle employee attrition.**

- How job assessment makes difference in Job/Career Satisfaction? What are key Job assessment paramenters to be considered for improvement?
- What parameters possibly can trigger high employee attrition?

## Data Understanding

Stack Overflow 2017 is source dataset. The rows are the different respondants to the survey, and the columns are the answer to the various survey questionnaires. It contains data that comes as numerical, categorical and text. It also has missing values and outliers as well.

## Data Preparation

For the data preparation phase, we have used learnings from Data Wrangling lessons. Source excel sheet is imported into python code to extract data, assessed and trasnformed into python data frame. We maintained master copy as it is and created multiple deep copy and prepared subset of data using fliters based on columns of interest. We have used imputing methods whereever it is appropriate to apply and performed analysis using python libraries of Numpy,Pandas,matplotlib.

## Modeling

Modeling can be perfomed based on mathematical data but Stack Overflow has only 5-6 columns with numerical values so we considered 2 of such columns and incorporate them with other Categorical columns for analysis.

## Evaluation

Our business questions have subjective evalution from quantitative analysis.

**Diversity & Inclusion** 

Key contributors to achieve decent satisfaction rating could be educational qualification and professional role. Parent's educational background somehow helped for broader prospect for respondants to purse good degrees which in-turn helped for right career direction and roles which turned out to good satisfaction rating.
Small to Medium scale companies (Based of no. of employees) are picking good pace to acheieve this goal.

Feedback is provided by just 8% of whole dataset so increased % of feedack will helps to get more accurate or divserfied result.

**Technology Drives**

- **Languages**: Java, JavaScript, PHP, SQL, C# and their combination is most popular languages but Python is in choice of learning since it is fast emerging progamming language for Coding and analysis.
- **Database**:MySQL, SQL Server,PostgreSQL and their combination is very popular DB platform but open source DB tech. like Mongo, Cassandra, PostgreSQL are attracting both employees and employers.
- **Farmework**:.NET Core and Angular JS are most preffered Framework and React, Spark, Hadoop which is also gaining popularity.

**Job Assessment Factors to Satisfaction**

- **Excellent (9 or 10)** : Respondent are satisfied with role,company, professionl growth, work-life balance, policies, leadership, compensation.
- **Meet Expectation (7 to 8)** : Factors could be Prof. development, Company policy, work-life balance, Diversity or Compensation and such respondents are seeker for improvement.
- **Average (5 to 6)** : Those respondents are seriously looking for better opportunities and decision possibly based on Job role, Compensation, Remote working.
- **Below Expectation (Lower than 5)** : Need more depth analysis since there could be many reasons includes individual skill set, existing technology, department, leadership, financial aspects.

## Deployment

Python code is developed to perform analysis and make some conclusion to inline with business questions.
Reference file is attached. 

# Medium Blog Post
