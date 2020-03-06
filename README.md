# Pokemon Machine Learning Classification and Clustering
This is my Machine Learning Classification for the Pokemon Dataset from Kaggle. I am trying to make Classification Model for the Pokemon Dataset. You can find the dataset from :
https://www.kaggle.com/abcsds/pokemon

So actually I am using the CRISP-DM framework which consists of 6 steps as below :
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modelling
5. Evaluation
6. Deployment *not done in this repo, deployment is the phase where you deploy your ML to your business process to improve efficiency

I am using python in jupyter notebook. My findings of my ML model is as follows :
1. My model performance (accuracy) is still low (< 70%)
2. My model is not good enough might be caused by :

a. Features are not distinctive between each Pokemon Type

b. The label consists of too many categorical label

3. All of the features is important to the model (Variable Importance)

Future Improvement :
1. Make a better model by :

a. Use a better, more distinctive and characterized input data (features)

b. Pick two or more features (not all features) to feed the model

c. Pick top 3 Pokemon Type labels and group other Pokemon Type to "Others"

d. Group the data in each feature and encode it to integer 0 and 1 (ex. 0 = HP > 100, 1 = HP <= 100)

2. Pick another Classification technique
3. Create another Machine Learning Model with different goal


Hope you find my repo useful and you can make some improvements based on my work. Thank you. Cheers.


Addition : I am uploading another Machine Learning model : Clustering Machine Learning with R Programming. I use the K-Means Clustering technique and divide the population into 3 clusters. You can find the RMD file and the Chrome HTML documents R Programming - Clustering folder.

