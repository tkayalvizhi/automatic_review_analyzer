# Automatic Review Analyzer
This project was done as part of the **Machine Learning with Python-From Linear Models to Deep Learning** course (MITx MicroMasters in Statistics and Data Science)

## Project Description
The goal of this project is to design a classifier to use for sentiment analysis of product reviews using linear classifiers including 

1. Perceptron Algorithm
2. Average Perceptron Algorithm
3. Pegasos Algorithm

The training set consists of reviews written by Amazon customers for various food products. The reviews, originally given on a 5 point scale, have been adjusted to a +1 or -1 scale, representing a positive or negative review, respectively.

Below are two example entries from the dataset. Each entry consists of the review and its label. The two reviews were written by different customers describing their experience with a sugar-free candy.

| Review | Label |
|-|-|
|Nasty No flavor. The candy is just red, No flavor. Just plan and chewy. I would never buy them again| -1|
|YUMMY! You would never guess that they're sugar-free and it's so great that you can eat them pretty much guilt free! i was so impressed that i've ordered some for myself (w dark chocolate) to take to the office. These are just EXCELLENT!|+1|

## Setup Details
1. [project1.py](https://github.com/tkayalvizhi/automatic_review_analyzer/blob/454187ac153c56298523b1f5dff693c4c1356852/project1.py) contains various functions that I will use to implement learning algorithms.
2. main.py is a script where these functions are called and to run experiments.
3. utils.py contains utility functions that the course staff implemented.
4. test.py is a script which runs tests on a few of the methods I implemented also written by course staff.

## Functions and algorithms implemented by me
1. [hinge_loss_single](https://github.com/tkayalvizhi/automatic_review_analyzer/blob/454187ac153c56298523b1f5dff693c4c1356852/project1.py#L20)
2. hinge_loss_full
3. perceptron_single_step_update
4. perceptron
5. average_perceptron
6. pegasos_single_step_update
7. pegasos
8. classify
9. classifier_accuracy
10. bag_of_words
11. bag_of_words_without_stopwords
12. extract_bow_feature_vectors
