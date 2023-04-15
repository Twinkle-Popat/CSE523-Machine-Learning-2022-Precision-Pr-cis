# CSE523-Machine-Learning-2022-Precision-Pr-cis
Our project is based on Text Summarization using Machine learning models

# Abstract
Text summarization plays an important role in interpreting a large amount of text data by extracting only the most important parts of the text. The project aims at exploring the application of Machine Learning techniques in Natural Language Processing (NLP). The project involves creating several models with different combinations of features such as Entity Count, TFIDF, Count Vectorizer and Sentence length. These models are then trained using different SVM kernels and their accuracies are compared. Based on these accuracies, two models were selected for hyperparameter tuning. <br>

# Methodology
The project can be divided into four parts as follows:
A.	Preprocessing the data
This involves sentence tokenization that is breaking the sentence into individual terms. Further stop words and punctuation are removed since they do not add meaning to the summary. 
B.	Training a basic SVM model using Named Entity Recognition and Count vectorizer 
A count vectorizer matrix and a binary array are created from the articles and are used as input to train a SVM model. Count Vectorizer is method that is used to convert the text into a matrix of counts while NER is used to find entity words to form the binary array. 
C.	Training various models using different kernels of SVM
To add more context to the summary, four important features are identified, and five models are formed by different combinations of these features. The features include Entity Count, TD-IDF score, Count Vectorizer and sentence length. The models are trained by using different kernels of SVM and their accuracies are noted.
