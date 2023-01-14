**Problem Statement**

An education company named X Education sells online courses to industry professionals.The company markets its courses on several websites and search engines like Google.

Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals.

Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The average lead conversion rate is around 30%. To make it more efficient,company needs to identify potential leads,who are more likely to convert,and the sales team can contact these potential lead instead of calling everyone.

**Business Goal**

Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads.
A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.
There are some more problems presented by the company which the model should be able to adjust to if the company's requirement changes in the future; so these need to be handled as well.

**Analysis Approach**
1. Reading and understanding Data - basic inspection
2. Data Cleaning - Handling missing values, dropping unwanted columns
3. Perform Outlier treatment - capping or dropping
4. Data Preparation - perform EDA, one hot encoding(dummy variable creation), scaling and perform train test split -
5. Modelling - RFE and manual approach (p value and VIF)
6. Performance on test data
7. Predict lead score using probabilty score
8. Conclusion and derived insights
