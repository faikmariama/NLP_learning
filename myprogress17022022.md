# NLP_learning
 Natural Language Processing (NLP)  with Classification and Vector Spaces
## 1. Supervised ML & Sentiment Analysis
In supervised machine learning, we usually have an input x, which goes into our prediction function to get your Z. And then we compare our prediction with the true value ZZ. This gives us our cost which we use to update the parameters θ. 
In NLP To perform sentiment analysis on a tweet, we have to represent the text  as features, and then train the logistic regression classifier, and then we can use it to classify the text either, for 1 a positive sentiment , or 0, for a negative sentiment. 
To do so, we first need to represent the text with a vector of dimension 3. To do so, we will have to create a dictionary to map the word, and the class it appeared in (positive or negative) to the number of times that word appeared in its corresponding class.

In this week we learned the first step into  NLP:
### 1.1 Preprocessing (check the script "preprocess" associated):
When preprocessing, we have to perform the following:

1. Eliminate handles and URLs

1. Tokenize the string into words. 

1. Remove stop words like "and, is, a, on, etc."

1. Stemming- or convert every word to its stem. Like dancer, dancing, danced, becomes 'danc'. You can use porter stemmer to take care of this. 

1. Convert all your words to lower case. 
