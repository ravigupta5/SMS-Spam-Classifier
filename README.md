# SMS-Spam-Classifier
The aim of our model is to classify SMS as spam or non-spam(ham)

### About Data:
- The data has been sourced from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection.
- The collection is composed by just one text file, where each line has the correct class followed by the raw message.

### EDA
![alt text](https://github.com/ravigupta5/SMS-Spam-Classifier/blob/master/spam_ham_count.PNG?raw=true)

### Text Pre-processing
- Removed punctuations and stopwords
- Used NLTK library
- Bag of words (Vectorization)
- Applyed term frequency-inverse document frequency (TF-IDF)

### Naive-Bayes Model
Applied Naive-Bayes Model to get f1 score of 0.98 and 0.86 for ham and spam prediction respectively
