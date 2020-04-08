# Quora-Question-Pairs
A Machine Learning based approach to classify whether a pair of given questions are identical/duplicate/have same intent or not using NLP techniques.

<h1> 1. Problem Description </h1>

- Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

- This is a simple Machine Learning based approach to classify whether a pair of given questions are identical/duplicate or not using NLP techniques.

- Few highlights of the code:
    - Performed feature extraction.
    - Analysed the extracted features graphically.
    - Preprocessing of text
        - Removing html tags
        - Removing Punctuations
        - Performing stemming
        - Removing Stopwords
        - Expanding contractions etc.

    - Performed advanced Feature Extraction (NLP and Fuzzy Features)
    - Featurized text data with tfidf weighted word-vectors.
    - The following Machine Learning models were used:
        - Logistic Regression with hyperparameter tuning
        - Linear SVM with hyperparameter tuning
        - Random Forest with hyperparameter tuning
        
    -  Since this is a binary classification problem, appropriate performance measures such as log loss, accuracy, precision and recall scores have been used. 
    - The best results were obtained from The Random Forest Classifier with Log loss minimised to 0.36
