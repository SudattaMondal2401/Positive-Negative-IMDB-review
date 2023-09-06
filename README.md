# Positive-Negative-IMDB-review

### Introduction 

The following jupyter notebook uses a movie review dataset found on kaggle to train ML models that can detect whether a IMDB  review is positive or negative based on their content.

The link to the dataset can be found [here](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

We compare the various ML models available and see which one gives the highest accuracy and f1 score. 

### Splitting the dataset

We applied the spacy preprocessing to remove the stop words and lemmatize the texts to get more accurate results.

Since there was an equal number of positive and negative messages, we used normal train_test_split to split the data.

### Conclusion

According to our work, the top 5 models with the highest accuracy and f1 scores are as follows:

i. *Stacking Classifier*

ii. *Soft Voting Classifier*

iii. *Hard Voting Classifier*

iv. *SVC Classifier with sigmoid kernel*

v. *Linear SVC Classifier*
