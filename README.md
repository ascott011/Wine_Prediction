# Wine Predictor

## The Project

I wanted to be able to predict the variety of wine based on it’s description by examining keywords and characteristics of the wine. I also created a predictor that predicts whether the wine is red or white through the same process of examining keywords and characteristics. I examined wine reviews using natural language processing(NLP). I love wine, so I thought this would be interesting for me to learn more about key characteristics of different types of wine. 


## The Data

My comes from Wine Enthusiast Magazine where zackthoutt scraped wine reviews from their website. This is a link where the dataset can be found: https://www.kaggle.com/zynicide/wine-reviews. For my project, I narrowed down the wine reviews from 150K to 48K because I wanted to use the top 5 most popular red and the top 5 most popular white wines from the dataset. There were 29,562 red wines and 18,533 white wines in my final 48K. 

## The Predictors

### Count Vectorizer using Multinomial Naive Bayes (Red VS White Wine)

This predictor uses a count vectorizer and then multinomial naive bayes to predict whether the wine review is referring to a red or white wine. This model’s accuracy is 98%. I was curious about which keywords the model was using to make it’s predictions, so I pulled out the top features in the reviews. These are some of the top feature words for red wine: Spice,
 chocolate, dark, berry, 'shows', 'soft', 'blackberry' ,'rich', 'black',  'cherry,' 'tannins'


### Count Vectorizer using Multinomial Naive Bayes (Wine Variety)

This predictor also uses a count vectorizer and multinomial naive bayes to predict the wine variety. This model’s accuracy is 64%



### Random Forest Classifier

## Going Forward



***image of points hist***
***image of countries***



Pinot Noir                  9283
Chardonnay                  9159
Cabernet Sauvignon          8270
Bordeaux-style Red Blend    5170
Sauvignon Blanc             4033
Syrah                       3661
Riesling                    3583
Merlot                      3178
Pinot Gris                   899
Viognier                     859

***image of red vs white wines***
***image of wine variety***

Using the wine reviews, I began predicting what wine variety was being reviewed. I first used a CountVectorizer and a test train split to train the data and create a confusion matrix. 
The accuracy: ***

***include confusion matrix***


RANDOM FOREST CLASSIFIER