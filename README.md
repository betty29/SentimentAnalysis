# SentimentAnalysis
A combined project on natural language processing and deep learning.Sentiment Analysis is the most common text classification tool that analyses an incoming message and tells whether the underlying sentiment is positive, negative our neutral.
Here it is a basic project that analyse movie reviews and predicts how good the movie is.Naive Bayes Classifier algorithm which is a classification algorithm under supervised learning is used here.

There are many algorithms to implement sentiment analysis and here I have used the automatic approach, which uses machine learning techniques. The sentiment analysis task is usually modeled as a classification problem where a classifier is fed with a text and returns the corresponding category, e.g. positive, negative, or neutral. 

Training Process
The model learns to associate a particular input (i.e. a text) to the corresponding output (tag) based on the test samples used for training. The feature extractor transfers the text input into a feature vector. Pairs of feature vectors and tags (e.g. positive, negative, or neutral) are fed into the machine learning algorithm to generate a model.

Prediction Process
The feature extractor is used to transform unseen text inputs into feature vectors. These feature vectors are then fed into the model, which generates predicted tags (again, positive, negative, or neutral).

Feature extraction from text
The basic idea is to transform the text into a numerical representation ,a vector.

Performance metrics is obtained using cross validation, where it is split into training and testing data and the traning folds is used to test the classifier. The process is repeated multiple times and an average for each of the metrics is calculated.
