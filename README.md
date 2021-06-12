# Final Project - Data Mining 

![Imgur Image](https://imgur.com/uE9Rfuy.jpg)

# Synopsis - Red Wine Quality 

As the publisher of this dataset suggests; due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.). This specific dataset can be viewed as classification or a regression task. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones). As the publisher suggest, we will classify the wines by setting an arbitrary cutoff for our dependent variable (wine quality) at e.g. 7 or higher getting classified as ‘good/1’ and the remainder as ‘not good/0’. For this specific kernel we will be doing some basic data explorations and will be doing classification utilizing a quick random forest as our baseline model.

# Data Introduction

In this dataset there are specifically red wine variants of Poteguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.). For more information, read [Cortez et al., 2009].

In the data set, there 1599 different wine as row data and 12 features as columns. Furthermore, there is no nun value to deal with it and all values are numeric means that input values are float and only output value is integer.


# Correlation Heatmap of Variables

![Imgur Image](https://imgur.com/H6L1tYN.jpg)

We’re trying to predict wine quality, so we care about the final 2 columns/rows in order to know which among the variables has the strongest relationship with wine quality. As the heatmap suggests, alcohol has the strongest correlation with wine quality.


# Topics in this project

- Classification Tree
- Pruning
- confusionMatrix
- Bagging and Random Forests
- Boosting
- Logistic Regression
- Optimum Cutoff
- Receiver Operating Characteristic Curve (ROC)
- Multicollinearity
- K-means clustering 
- Hierarchical clustering  
- Cutting Tree
- Elbow method
- Average Silhouette Method
- Gap Statistic Method











