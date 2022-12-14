# Solutions to Assignments 2 -- Word Importance #

## Problem 1: With or without function words ##

Compare the top 100 most frequent words in all horoscopes with and without stopwords (i.e. function words), what seems to be the most striking differences? You should include your stopword list (or a link to) in the answer. You can use a wordcloud to visualize the comparison (requires that you `pip install wordcloud` from the terminal). 

## Problem 2: Sign-specific indexing ##

Compare top 200 most frequent words for at least three different Zodiac signs (ex. virgo, leo, pisces) using the `difference` set function from Problem 1. Are there any apparent characteristics/distinct differences between the signs?

## Problem 3: Document similarity ##

Generate a document-term matrix from the horoscope data and extract $n$ documents, where $n > 5$. Compute the similarity between all extracted documents and, in natural langauge, explain the extrema (the similarity between the two least and two most similar documents).