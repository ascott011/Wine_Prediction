# Wine_Prediction

Data scrapped from Wine Enthusiast Magazine by zackthoutt which can be found here: https://www.kaggle.com/zynicide/wine-reviews

There are over 150K reviews in this DataFrame, and I started this project with exploration and making some visuals about the data. The United States had the most wines reviewed in this dataset. There were 632 different types of wine in this dataset, but some of these "types" were blends, and I did not want to use blends to avoid confusion. After eliminating blends, unknown grape varieties, and duplicate enties, I narrowed the field down to 48K reviews. 

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