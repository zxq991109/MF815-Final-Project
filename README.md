# MF815-Final-Project

In this project, We used fund summary data to classify the funds by their investment strategies, which constitute of four types with one type of very few samples in the training set. 

We used the skip-gram model to build a word embedding dictionary for the mutual fund summaries and built a knowledge base for each investment strategy by using the TF-IDF scoring model and a self-defined function of finding the closest n words to find out the key words of the knowledge bases.

Then we calculated the distance of the funds in the test set to the knowledge bases to find out their investment strategy.

We treated funds with the investment strategy of very few samples in the training set as outliers and used outlier detection methods to classify those of this category.
