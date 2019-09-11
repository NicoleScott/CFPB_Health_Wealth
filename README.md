# Capstone Project:  "Does Wealth = Health?"
*Predicting health based on indicators of financial wellbeing*

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  
---
#### ![](https://s3.amazonaws.com/storage.citizensforethics.org/wp-content/uploads/2018/12/11154222/cfpb.png)

---

## Executive Summary

This analysis takes a look at *2016 Financial Wellbeing Survey Data* from the Consumer Financial Protection Bureau (CFPB). Data from about 6,500 survey respondents across the United States contains information about various life factors which may contribute to an individual's financial well being. Some health-related elements are also a part of this dataset. The CFPB's intended use for the survey data is to provide individuals, financial counselors and advisors with a tool (a "Financial Well-Being" score) to measure an individual's state of financial well being over time. Based on this data, our objective is to try and predict an individual's quality of health ("optimal" or "sub-optimal") based on their "Financial Well-Being" score and other related variables.

---

## Problem Statement

Can we predict an individual’s quality of health, based on indicators of financial wellbeing?

---

## Technical Report
A detailed technical report includes statistical analysis and data visualizations of *2016 Financial Wellbeing Survey Data* to illustrate findings. This report spans multiple Jupyter notebooks, which can be accessed via links in the Contents section below.

### Contents:
- [CFPB Stub Starter](./code/00_Stub_Starter.ipynb)
- [Exploratory Data Analysis](./code/01_EDA.ipynb)
- [Feature Selection](./code/02_Feature_Selection.ipynb)
- [Modeling](./code/03_Modeling.ipynb)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)
- [Additional Research and References](#Additional-Research-and-References)


---

## Conclusions and Recommendations

Conclusions -
After testing and tuning several machine learning models, we are able to predict quality of health with 68% accuracy, based on financial wellbeing indicators. This level of accuracy does not indicate that this a compelling dataset for an alternative use case related to individual or population health outcomes.

Recommendations -
Additional steps can be taken to continue to gain insights from the CFPB data, including:
 * More Feature Selection (only 40 of the original 217 features were modeled)
 * More Feature Engineering
 * More Parameter Tuning
Find additional relevant datasets like from the Healthy People 2020 website:
https://www.nidcd.nih.gov/healthy-people-2020


---

## Additional Research and References

Resources used for analysis and recommendations:
* Financial well-being.    The Consumer Financial Protection Bureau’s National Financial Well-Being Survey collected more than 6,000 responses to the agency’s 10-question Financial Well-Being Scale, plus additional demographic and financial information. The survey results, which were collected in late 2016, come with a detailed methodology and data dictionary. Plus: You can take the questionnaire yourself, anonymously. [h/t Amy Cesal]    
https://www.consumerfinance.gov/data-research/financial-well-being-survey-data/
https://www.consumerfinance.gov/consumer-tools/financial-well-being/
https://s3.amazonaws.com/files.consumerfinance.gov/f/documents/cfpb_nfwbs-puf-user-guide.pdf
https://www.consumerfinance.gov/consumer-tools/financial-well-being/
https://twitter.com/amycesal

#### Advancing financial well-being through research
#### Understanding factors that support consumer financial well-being can help practitioners and policymakers empower more families to lead better financial lives to serve their own goals.

A person’s financial well-being comes from their sense of financial security and freedom of choice—both in the present and when considering the future. We measured it using our 10-item Financial Well-Being Scale.
The survey dataset includes respondents’ scores on that scale, as well as measures of individual and household characteristics that research suggests may influence adults’ financial well-being, including:
 - Income and employment
 - Savings and safety nets
 - Past financial experiences
 - Financial behaviors, skills, and attitudes

*Following a rigorous research effort to develop a consumer-driven definition of financial well-being, the CFPB developed and tested a set of questions–a “scale”–to measure financial well-being.*

#### In total, there are 217 variables in the public use dataset (Public Use File or PUF).


