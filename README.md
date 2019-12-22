# Predicting-Multi-Source-Social-Media-Popularity
Course project: IMT 575 Data Science III: Scaling, Applications, and Ethics

![poster](https://github.com/MollyMeng/Predicting-Multi-Source-Social-Media-Popularity/blob/master/575%20poster.png)

### Exploratory Analysis
#### News_data_EDA
Basic popularity check across the platfroms. 
#### News Source EDA
Created categorical features for news channel and explore the popularity distribution across the difference news source. 
#### News text analysis
1. Found no clear connection between the length of the title/headlines and the popularity.
2. Preprocessed the text and vectorized them using tf-idf vectorizor.
3. Created three columns of y for prediction use: top 1%, top5%, and top 25%.
4. Built the most naive logistic regression and the RF
5. Tested the feature and model on facebook top25% news prediction. Recall 33%. 
### News text prediction
