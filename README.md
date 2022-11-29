# Fake-news-analysis

“Fake news” is a term that has come to mean different things to different people. At its core, we are defining “fake news” as those news stories that are false: the story itself is fabricated, with no verifiable facts, sources or quotes.

Methodology

The categories, bs (i.e. bullshit), junksci(i.e. junk science), hate, fake, conspiracy, bias, satire and state declare the category under which untrustworthy or false news fall under.

The first step, which is text preprocessing was performed using the following:

1.Taking care of null/missing values

2.Transforming categorical data with the help of label encoders

3.Uppercase to lowercase

4.Number removal

5.Tokenization

6.Stop Word Removal, Stemming and Lemmatization (with POS tagging) using the Natural Language Toolkit Library

For feature engineering, the TF-IDF technique is used. TFIDF works by proportionally increasing the number of times a word appears in the document but is counterbalanced by the number of documents in which it is present.
