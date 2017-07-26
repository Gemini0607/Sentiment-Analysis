# Sentiment-Analysis
# Text pre-processing
The Data has 1000 positive and 1000 negative labelled files.
In the Pre-Processing ipython notebook, these have been broken down to individual texts, and then preprocessed.
One output contains simply the 60K+ texts seperated by '|' which can be further used as needed.
The second output contains contains those 60K+ labelled text files in .csv format.
There may be some redundancies, which users of this data are free to operate on.

# Classification
1. Text_Classification ipython notebook contains implementation of different classification algorithms available in sklearn package.
These algos have been implemented on the 60K+ data ie individual texts.

2. dataset_of_2000 ipython notebook contains implementation of the same classification algos, but on the original labelled data of 1000 positive and 1000 negative files, which have also been pre-processed.

# Aim
The aim was to compare the accuracies of the different algos used on both versions of the data.

If anyone has annysuggestions on how to improve the pre-processing or the classifier accuracies, do let us know. Thank You
