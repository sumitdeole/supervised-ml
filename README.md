## Supervised machine learning
In this project, I will use the famous housing price prediction data and employ the two supervised ML algorithms (classification and regression). The dataset contains a total of 80 features. In doing so, I will apply many useful techniques (hyperparameter tuning, *scikit-learn* pipelines) to find the best-performing model. The best model will be then used to test the unlabeled data provided for an internally organized competition. For more details on the data used, [click here](https://github.com/sumitdeole/supervised-ml/blob/main/data/data_description_full.docx)

### Classification: Predict whether the house is expensive (or not)
For this part of the project, I will predict the binary label "Expensive", which takes the value of 1 if the price of the house is above a certain threshold, e.g., $200,000, and 0 otherwise. I tested numerous state-of-the-art models, e.g., *XGBoostClassifier()* *DecisionTreeClassifier()*, *RandomForestClassifier()*, *KNeighborsClassifier()*, "LogisticRegression()*, and *SVC()*. 

The *RandomForestClassifier()* performed the best with the training (accuracy = 95.5%) and test data (accuracy = 95.9). 
The test accuracy of the best model on the unlabeled competition data was 97.3%.  


A complete code is available in this repository [click here](https://github.com/sumitdeole/supervised-ml/blob/main/code/classification_code.ipynb).



### Regression: Predict the exact price of the house
For this part of the project, I will use the continuous house price column: *SalePrice*. The prediction will take place by applying many regression estimators to get the best prediction performance, i.e., higher *R2 squared* and lower *Root Mean Squared Error (RMSE)* scores. Ultimately, the trained model will be used to predict the house prices of the unlabelled test dataset present on **Kaggle** ([link here](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)).


Complete code is available in this repository [click here](https://github.com/sumitdeole/supervised-ml/blob/main/code/regression_code.ipynb).
