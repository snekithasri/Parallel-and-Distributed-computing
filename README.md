# Parallel-and-Distributed-computing
Text pre-processing using parallel computing

### Abstract
Text preprocessing is a method to clean the text data and make it ready to feed data to the model. Text data contains noise in various forms like emotions, punctuation, text in a different case.When it comes to human language, we have different words with the same definition which is a problem because machines can't understand them so we use text preprocessing to convert human language to machine readable format.

Text preprocessing involves converting upper case letters to lowercase,removing punctuations,removing blank lines,converting numbers to words,etc.

### Data Set Description
The dataset is called “20 Newsgroups” and it's a collection of 18,000 newsgroup documents from 20 different newsgroups. sklearn provides a method to download and load the dataset.

### Results And Discussion
Text preprocessing is one of the most important and time consuming steps of NLP. By using parallel computing we can reduce the time taken for performing this complex process.For parallelization we have used the DASK library in python language.
