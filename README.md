# Product Purchase Experimental Study (A/B Testing)

1. Data analysis - Project Background

This project is based on the data provided at https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing?datasetId=1660669. 

1.1 About Dataset

Marketing A/B testing dataset Marketing companies want to run successful campaigns, but the market is complex and several options can work. To understand user behaviour, organisations collect data and analyse this through e.g.  A/B tests. This is a method used in marketing, product development, and experimentation to compare two versions to determine which one performs better. In A/B testing, the two versions are referred to as the control and the treatment group. The control group is the existing or standard version, whereas the treatment group receives a modified version being tested. The majority of the people will be exposed to ads (the experimental group). On the other hand, a small portion of people (the control group) instead see a Public Service Announcement (PSA) in the exact size and place the ad would normally be.

The idea of the dataset is to analyse the groups, find if the ads were successful, how much the company can make from the ads, and if the difference between the groups is statistically significant.

1.2 Data dictionary:

The following variables are part of the analysis:

- Index: Row index
- User id: User ID (unique)
- Test group: If "ad" the person saw the advertisement, if "psa" they only saw the public service announcement
- Converted: If a person bought the product then True, else is False
- Total ads: Amount of ads seen by person
- Most ads day: Day that the person saw the biggest amount of ads
- Most ads hour: Hour of day that the person saw the biggest amount of ads
