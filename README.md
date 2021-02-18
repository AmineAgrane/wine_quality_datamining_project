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

##### *Dataset description*
The wine dataset is composed by a total of 13 different variables : 

**1- fixed acidity (tartaric acid - g/dm3)** : most acids involved with wine or fixed or nonvolatile (do not evaporate readily)

**2- volatile acidity (acetic acid - g/dm3)**: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste

**3- citric acid (g/dm3) **: found in small quantities, citric acid can add ‘freshness’ and flavor to wines 

**4- residual sugar (g/dm3)** : the amount of sugar remaining after fermentation stops, it’s rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet

**5- chlorides (sodium chloride - g/dm3) **: the amount of salt in the wine

**6- free sulfur dioxide (mg/dm3) **: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine

**7- total sulfur dioxide (mg/dm3) **: amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine

**8- density (g/cm3)** : the density of water is close to that of water depending on the percent alcohol and sugar content

**9- pH** : describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale

**10- sulphates (potassium sulphate - g/dm3)** : a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant

**11- alcohol (% by volume)** : the percent alcohol content of the wine Output variable (based on sensory data):

**12- quality**: score between 0 and 10 that describes the quality of the wine.

**13- color**: color of the wine. There are two type wine, red wine and white wine.
