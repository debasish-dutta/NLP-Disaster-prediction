# NLP-Disaster-prediction

# 1. Problem Statement
> ### This model will aim to predict which tweets are about real disaster and which of them are not using `natural language processing`.
# 2. Data
### This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ [website](https://www.figure-eight.com/data-for-everyone/) but this dataset is readily avaliable on [Kaggle](https://www.kaggle.com/c/nlp-getting-started/overview).

The Dataset has two csv- one with train data and other with test data. The dataset contains 4 features.
# 3. Evaluation
> #### The evaluation metrics for this competition is the f1 score.
# 4. Features
- id: Used for submission
- keyword: Keyword of the tweet
- location: Location the tweet was sent from
- text: The Tweet itself
# 5. Modelling
> #### I used a [Multinomial Naive Bayes model](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html#sklearn.naive_bayes.MultinomialNB) for this project.
