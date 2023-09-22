# Sentiment-Analysis

1. Performing Sentiment analyis on Disaster tweets Data
2. Data Preprocessing involves:
   a) Converting to lowercase
   b) removing punc  --> List of sentences
   c) Word tokenization --> List of list of words
   d) Removing the stopwords
   e) Lemmatization
   f) Words to sentence formation
3. Transform the words into vectors using
   a) Count Vectorizer
4. Selecting x(independent feature) as tweets after preprocessing and target as y(dependent feature).
5. Split data into training and test data.
6. Applying Different models on the training dataset and generate the predicted value for the test dataset
   a) Multinomial Naïve Bayes Classification
   b) Logistic Regression
   c) KNN Classification
7. Predict the target for test data
9. Computing Confusion matrix and classification report for each ofthese models
10. Reporting the model with the best accuracy
