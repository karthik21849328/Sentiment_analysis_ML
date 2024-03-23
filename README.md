# Sentiment_analysis_ML


In this module we should classify the given text into positive sentiment or negative sentiment using Machine Learning Algorithm 

When there is training data avialable we should go with Machine Learning model.

Approach to classify the the given text 

Preprocessing the text 
* By eliminating the HTML tags, Accented Character, stopwords and special character
* HTML tags are eliminated by using BeautifulSoup 
* Accented characters are converted by using UNICODE library
* Special Chracters are eliminated using REGULAR EXPRESSION

Machine Learning model used to classify the text is RandomForestClassifier

Accuracy obtained of RandomForestClasssifier is 77%

Output- 1 denotes Positive Sentiment
Output- 0 denotes Negative Sentiment 
