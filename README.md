# Bag of Words Meets Bags of Popcorn
A solution for the competition from Kaggel [Bag of Words Meets Bags of Popcorn](https://www.kaggle.com/c/word2vec-nlp-tutorial)

I'm achive score **0.95893** using simple [TfidfVectorizer](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html) and [LogisticRegression](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html). Also use [RandomizedSearchCV](http://scikit-learn.org/0.17/modules/generated/sklearn.grid_search.RandomizedSearchCV.html) for search the best parameters for the vectorizer and model.

# Data analysis
Using the **coefficients** of the model and '**features**' from vectorizer, I tried recognize what words mark reviews as positive or negative. 

All code is precompiled, so you can find more information in the ipython notebook.
