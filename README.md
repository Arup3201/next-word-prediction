# next-word-prediction
This project is one of the basic one where I use the LSTM and some NLP techniques to make the model for predicting the next word

## Step 1: Building the dataset for Next Word Prediction model
I am using 3 popular datasets to make one large dataset for making this model. My objective here is to make such a model that can be as close as google gmail's prediction model where they smoothly predict the next word when we try to write any email.
Three datasets that are used and made into one large dataset are,
1. DBPedia dataset [Kaggle link](https://www.kaggle.com/datasets/danofer/dbpedia-classes).
2. 20 Newsgroups dataset [Kaggle link](https://www.kaggle.com/datasets/crawford/20-newsgroups?select=talk.politics.misc.txt).
3. IMDB dataset [Kaggle link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

Run to the `combine_datasets.py` file to perform this task. To see the experiment where I tried out some methods to come up with the whole code, refer to `experiment_combine_datasets.ipyb` file.

## Step 2: Using the dataset as tensorflow dataset and tokenizing it
We will use some techniques in tensorflow and speed up the training process with the help of tensorflow datasets.
