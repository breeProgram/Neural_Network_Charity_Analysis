# Neural_Network_Charity_Analysis
## Introduction

With knowledge of machine learning and neural networks, this project was to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team, a dataset with a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years will be asseted using Pandas, Scikit-learn, and Tensorflow with a goal of over 75% accuracy in predicting success. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Results

![summary_layers_nodes](https://user-images.githubusercontent.com/56700719/167463594-53ae5c00-037f-44de-9e85-d8a7179b69a5.JPG)

- The best resuts I was able to achieve evaluating this model using the test data was using three hidden layers with 70 nodes in the first layer followed by 50 then 30 running 100 epoches.

![Accuracy](https://user-images.githubusercontent.com/56700719/167463130-5491b9c3-8f22-49b9-bb76-f3cbf1a7b594.JPG)

- The highest accuracy achieve was 0.7247 and loss of 0.5736.

## Summary

The overall results of the deep learning model weren't 75% but the accuracy I was getting was not to far off. If I were to try any imporvements, I would try to use a different 
