# NLP
Objective: Classified the tweets about Corona Virus as positive or negative; in the dataset there are 5 classes: 'Extremely Negative', 'Extremely Positive', 'Negative', 'Neutral', 'Positive'.


1. Exploratory Data Analsis (EDA): look closely at you data, the text, the target, any null values, any imbalance, non-numerical data to be converted (in data and target)?, etc.
2. Split the train set into Training, Validation, & validation sets (0.75, 0.21), the test set is a separate file here.
3. Clean Textual Data
4.Vectorize Texts (one hot encoder, tfidf, embeddings (word2vec with gensim, ELMO, BERT, GPT, etc.))
5. ML Classification model(s) or DL model or an ensemble of several ML/DL or both ML and DL models
6. Choose and justify the choice of the evaluation metric
7. Hyperparameter optimization (Cross validation - hyperopt - Gridsearch)
8. Evaluate on Test set
9. Use Lime to explain one text classification
10. Use Shapley to explain globally the text classification
