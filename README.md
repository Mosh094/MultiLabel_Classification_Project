# Multi_Label_Classification_Project

### This repository presents a solution to a MultiLab Classification challenge 

The question required recommendation of relevant work categories offered by customers based of their description. The project focuses on building a machine learning algorithm that recommends possible offerings from clients, based on the details extracted from thier provided description

### Problem Statement

- The task is obviously not a astraight forward recommender system activity, as it focuses on extracting categories of business from the provided details, rather than follow any historical or inherent pattern as required for recommender system
- The fact that it is a supervised learning approach removes any element of clustering.
- The approach employed (Classification of recommend relevant work categories to customers based of their description) is closely related to topic modelling, as we are required to use description provided by clients, to predict the possible category of their activities, by extracting key topics from their details. This is however rulled out a the presented data has features and label, erasing any unsupervised learning approach
- The eventual approach deployed model is multi-label classification. As a classification approach, the model helps to classify categories bassed on the corresponding inherent relationship with the description. Muli-label classification deiffers from binary and multi-class classification.
- Binary refers to classification done with two possible outcomes, i.e yes/no. Multiclass refers to classification involving more than two possible outcomes.
- However, while, binary and multi-class refers to possibility of outputing only one result per obseration, multi-label classification refers to the case of possibly outputing one or more results for every observation, as it is in our case
