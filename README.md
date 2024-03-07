## Supervised machine learning
In this project, I will use the famous housing price prediction data and employ the two supervised ml algorithms (classification and regression). The dataset contains total 80 features with In doing so, I will apply many useful techniques (hyperparameter tuning, *scikit-learn* pipelines) to find the best performing model. The best model will be then used to test the unlabeled data provided for an internally organized competition. For more detailes on the data used, [click here](https://github.com/sumitdeole/supervised-ml/blob/main/data/data_description_full.docx)

### Classification: Predict whether the house is expensive (or not)
For this task, the dataset contains the binary label "Expensive", which takes the value of 1 if the price of the house is above certain threshold, e.g., $200,000, and 0 otherwise. I tested numerous state-of-the-art models, e.g., *DecisionTreeClassifier()*, *RandomForestClassifier()*, *KNeighborsClassifier()*, "LogisticRegression()*, and *SVC()*. 

The *RandomForestClassifier()* performed the best with the training (accuracy = 95.5%) and test data (accuracy = 95.9). 
The test accuracy of the best model on the unlabeled competition data was 97.3%.  


Complete code is available in this reposatory [click here](https://github.com/sumitdeole/supervised-ml/blob/main/code/classification_code.ipynb).



### Regression: Predict the exact price of the house