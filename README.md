# Wine-Class-Id-Predictions

This data set has predictions of the wine class id.

Description of Dataframe 

This df includes the Class Id, Alcohol, Malic Acid, Ash, Alcalinity Ash, Magnesium,	Total Phenols,	Flavanoids,	Non-Flavanoid Phenols,	Proanthocyanins,	Color Intensity,	Hue, OD280 OD315 DWines,	Proline.

Visuals 

<img width="600" alt="Screen Shot 2022-06-30 at 11 39 51 PM" src="https://user-images.githubusercontent.com/103530342/176838665-d042ef1f-4764-4786-8b5a-f1e70f897ca8.png">
Class Id of Wines bar graph. Id 2 seems to be the highest one in this dataframe. Id 1 is the second highest. Id 3 falls last.

Preprocessing and Predictions

Scaled the whole df, the dataframe was only numeric. Made 2 different models with 2 different hyperparameters, also added Principal Component Analysis on the better version of each model. The model that would perform the best would be the knn model 2 with the pca at .95, n_neighbors at 9, and p at 2. The classification report on the training and testing set is almost perfect. The precision, recall, and f1-score are high on both the testing and training set, all close to 1. This model would do extremely well with the least amount of errors.

For any additional questions, please contact **sabrinnapearl@gmail.com**

