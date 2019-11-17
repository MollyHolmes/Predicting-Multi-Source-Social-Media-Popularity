# Predicting-Multi-Source-Social-Media-Popularity
IMT 575 Data Science III: Scaling, Applications, and Ethics

### Exploratory Analysis
#### News_data_EDA
Basic popularity check across the platfroms. 
#### News Source EDA
Created categorical features for news channel and explore the popularity distribution across the difference news source. 
#### News text analysis: 
1. Found no clear connection between the length of the title/headlines and the popularity.
2. Preprocessed the text and vectorized them using tf-idf vectorizor.
3. Created three columns of y for prediction use: top 1%, top5%, and top 25%.
4. Built the most naive logistic regression and the RF
5. Tested the feature and model on facebook top25% news prediction. Recall 33%. 

#### TODO
0. Of all the records which are successfully predicted as true top25%, How many of them are in "obama"? How many of them are in other topics?  
1. Add systematic cross-validation
2. Try GloVe embeddings
3. In the experiments fo TOP 5% classification, the data is highly unbalanced and the classifiers predict no positive labels. Try to solve the unbalanced data by undersample or SMOTE and see the result.
4. TODO: Add topic and source features into the prediction features.
