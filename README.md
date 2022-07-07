# DNWLab_AmazonNMF
DMW Lab Project with LT4 SLT (John Gacal)

Executive Summary

In this report, we used Amazon's customer review data of books and e-books sold in Amazon's website. This dataset was extracted from Jojie's repository of data. First, we preprocess the data by cleaning (removing null values, getting only words and ignoring numbers/ html tags, removing stopwords). We performed preliminary exploratory data analysis (EDA) through the use of word clouds and plots to see some descriptive statistics. We then vectorized the customer reviews of each book and e-book using the TF-IDF in order to get a matrix representation of the words found in the reviews for each book and e-book. Once vectorized, Non-Negative Matrix Factorization (NMF) was performed to be able to unearth the latent factors. The latent factors were visualized in bar plots to be able to interpret the topics that can be found for each star rating and for each type of rating (eg for Amazon Verified Purchases and for Amazon Vine reviews).

