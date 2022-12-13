# shiva_krishna
Machinehack-ML-Merchandise-Popularity-Prediction


We need to predict the popularity from all the other data from dataset like Store_Ratio, Basket Ratio, Store Score. 
Big Brands spend a significant amount on popularizing a product.  Nevertheless, their efforts go in vain while establishing the merchandise in the hyperlocal market. Based on different geographical conditions same attributes can communicate a piece of much different information about the customer. Hence, insights this is a must for any brand owner.

Dataset link: https://www.kaggle.com/datasets/oossiiris/machinehack-ml-merchandise-popularity-prediction
Train.csv - 18208 x 12  (Includes popularity Column as Target variable)

** Observations from correlation matrix**

1. store ratio is strongly correlated with basket ratio , store score, score3 ,store presence score1 , score3
2. basket ratio is correlatd to store score, store presence, score1 score3.
3. category1 is correlated with category2
4. score presence is correlated with score1, score2, score3, popularity
5. score1 is correlated with score3 , score4, time, popularity

### CONCLUSION

We have performed EDA, preprocessing, build different models, visualized feature importance, did hyper parameter tunning of each model and did prediction.
store ratio is most important data in the dataset.
we used  voting classifier for prediction
