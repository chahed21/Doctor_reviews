# Doctor_reviews_Project pipeline

##  Cleaning and pre processing ## 
```Shell
- Text cleaning: This involves removing any irrelevant or unnecessary elements from the text such as punctuation marks, HTML tags, emojis, URLs, etc.
- Tokenization: This is the process of breaking the text into smaller units called tokens, which can be words, phrases, or sentences.
- Stop word removal: Stop words are common words that do not add any significant meaning to the text, such as "der," "das," "ein,etc. Removing stop words can reduce the number of features and improve the performance of the model.
- Stemming or lemmatization: This is the process of reducing words to their root forms to simplify the vocabulary and make it easier to analyze. Stemming involves removing the suffixes of words to obtain the root form, while lemmatization involves converting words to their base form using a dictionary.
```
##  Feature creation ## 
```Shell
- Convert text to numeric representation . 
- Choose a type of transformations: TF-IDF Fast text, bag of words , Word2Vec,etc ....
The choice of TF-IDF in the case study is the fact that it is popular in dealing with sentiment analysis.
```
##  Modeling ## 
```Shell
- Split data into train and test 
- Choose a classification model: traditional models (LogisticRegression,LinearSVC,RandomForestClassifier...) , LSTM models( with pretrained embedding or without) ,and transformers(Bert,GermanGPT2...)
- Fit model on train data
```
##  Evaluation ## 
```Shell
- Evaluate prediction on test data 
- Tune model parameters to improve performance
```
##  Prediction ##
```Shell
-Predict new data
```
