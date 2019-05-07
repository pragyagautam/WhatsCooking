The project __"What's Cooking"__ demonstrates various machine learning techniques. It predicts the category of a dish's cuisine given a list of its ingredients, such as garlic, tomato, onion.  There are 20 different cuisines, and 6714 unique ingredients in the dataset.
***
__The data__ we are using is from the Kaggle “ What’s Cooking? ” competition:
https://www.kaggle.com/c/whats-cooking-kernels-only

There are training set and testing set in the data and both in JSON format. 
- train.json – 39774 records containing recipe id, type of cuisine and list of ingredients
- test.json – 9942 records containing recipe id and list of ingredients 

one example of recipe record in train.json: {"id": 24717,"cuisine": "indian","ingredients": ["tumeric","vegetable stock","tomatoes","garam masala","naan","red lentils","red chili peppers","onions","spinach","sweet potatoes"]},

***
__Technology Utilized:__


- Two clusterings: K-means clustering and Gaussian clustering with 3, 4 or 5 clusters.

- 4 Machine Learning models: linear SVC algorithm, logistic regression, decision tree and random forest

- Data validation and testing: confusion matrix and classification report (precision, recall, f1-score, support for each type of cuisine) 

- Two preprocessing techniques: TF-IDF transformer and PCA 

- Two techniques for preparing data: Label Encoder, and Tf-Idf Vectorizer
***
__Training Details/Pre-processing:__
- Term frequency–Inverse document frequency (TF-IDF)
- Principal Component Analysis (PCA)
- Label Encoder
