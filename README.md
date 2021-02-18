# Project and Dataset Presentation      
In this notebook we will use the data from the Kaggle Repository (https://www.kaggle.com/rajyellow46/wine-quality) by P. Cortez, A. Cerdeira, F. Almeida, T. Matos, and J. Reis. The data include examples of red and white wines from Portugal-one of the world’s leading wine-producing countries. 

For each wine, a laboratory analysis measured characteristics such as acidity, sugar content, chlorides, sulfur, alcohol, pH, and density. The samples were then rated in a blind tasting by panels of no less than three judges on a quality scale ranging from zero (very bad) to 10 (excellent). In the case of judges disagreeing on the rating, the median value was used.

##### *Objective of this notebook*



The objective that we want to achieve through this notebook is to build a machine learning model of classification type, that will predict if a wine is considered as good or not. The model takes as input some wine characteristics (alcohol content, acidity, sugar proportion, etc), and gives as output a binary variable that describes the quality of the wine ("Good" or "Bad"). We'll use a decision tree as our classification model. We'll then use Random Forest to improve our classification scores.


##### *Used libraries*



The execution of this notebook needs the following library : 

 - caret
 - forcats
 - ggplot2
 - rpart
 - rpart.plot
 - randomForest
