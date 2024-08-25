---
layout: post
author: Lim Wee Kiat - 3774162M
title: "Applied Data Science Project Documentation"
categories: ITD214
---
## Project Background
Our team wants to empower married couples with predictive insights into HDB resales prices to better prepare them in decision making and stratgic planning. 

The project business goal; 
1. Able to predict the HDB prices violatility for the next 30 years
2. Classify into 3 price ranges from low, medium, high
3. Create recommendation system to suggest HDB flats based on user requirement
4. Classify buyer review in their housing experience. (My task)

## Work Accomplished
1. We choose the following Dataset from haggle.
2. Explore Dataset
- Look into the dataset to check if there is sensitive data which may incurred PDPA.
3. Transform
4. Prepare 
5. Train the model
6. Evaluate

### Data Preparation
The initial dataset was small. We manually downloaded additional review from Reddit to increase the dataset size. We went through the additional dataset labelling them either to positive or negative to be used as train data. We loaded the dataset using NLTK to preprocess the data. We trained the model giving us an Accuracy: 0.859375. 

### Modelling
We create a link to allow user to enter their review to predict if they are positive or negative. 

### Evaluation
We did a realtime evaluation and record the finding.

## Recommendation and Analysis
Our analysis revealed that due to the sentivity and maybe PDPA, there are no many sentiment analysis dataset to start in this business goal. The dataset we hae gathered are smaller in size and the machine learing isn't performing well. 

## AI Ethics
Privacy: some of the feedback containes sensitive data of individual. We have to spend a lot of time to anonymize data to protect individuals' identities.
Bias in Data: The review contents may be bias according to the study. 

## Source Codes and Datasets
https://github.com/Pencil1978/itd214_proj_Pencil/upload/main 
