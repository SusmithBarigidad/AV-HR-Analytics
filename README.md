# AV-HR-Analytics
Problem Statement :client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time

Finished 8th on the Public leader board
Solution Approach

Missing value Treatment
- Mode value for Education for level [department, region, gender, recruitment_channel]

Feature Engineering
- Binning of features
- Number of training hours, joining age
- Education importance for Masters, Bachelor & Below secondary
- Age bucketing
- Label Encoder for all the string columns

Model Used

- XGB Classifier with Gridsearch
