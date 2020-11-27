# Sentiment_Analysis_IMDB_Review_NLP

**1. Introduction**

***Dataset***

This dataset contains CSV versions of the Large Movie Review dataset by Maas, et al. (2011) from its original Stanford AI Repository. It contains 50k highly polar movie reviews, evenly split to 25k positives and 25k negatives. Each sample is labeled with a 0 (positive) or 1 (negative). 

***Objective***

The objective is to build the model that helps identify whether a movie review is positive or negative.  


**2.Technique**

In this project, I used the natural language processing (NLP) technique in order to deal with text data. 

For the sake of learning process, I chose three algorithms: Logistic regression, Naives Bayes and Convolutional Neural Network. 

With the two first algorithms, I tried to use N-gram technique (Unigram and Bi-gram) to improve the result of the models. 
As for Convolutional Neural Network algorithm, it is one of deep learning algorithms. For the sake of the learning objective, the work performed with this algorithm was quite standard, there was no hyperparameter tunning done for this model.

**3. Outcomes**

- Logistic Regression gave the highest accuracy score (88%) with Unigram technique.
- Bi-gram technique has not much impact on the result of Logestic regression and Naives Bayes models
- In terms of key words choosen by each model in order to identify the negative or positive sense of the comment, Logistic Regression has a quite good list of key word for positive and negative comments, while Naives Bayes has a list of quite non sense key words.
- The deep learning algorightm (Convolutional Neural Network) gave the lowest score of accuracy (84%). However, hypperparameter tunning could be used to improve the result. 

**Please refer to the presentation file and the Jupyter Notebook file for more detailed work and findings**

**Thank you**


