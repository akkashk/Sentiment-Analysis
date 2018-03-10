# Sentiment-Analysis
Sentiment analysis of movie reviews

Working from Thumbs up? Sentiment classification using machine learning techniques by Pang et al. I started this project by reproducing results from the paper after which I tried a few extensions:

- The results from the papers were achieved with a small dataset. The Stanford movie review dataset is a much larger dataset from the same source (IMDB), so I investigated the effects of using a larger dataset on test accuracy.

- I also extended the methods from document-level to sentence-level sentiment analysis and incorporated methods to detect neutral sentiments in reviews by training on a dataset from Rotten Tomatoes. I found that sentence-level analysis provides more useful results for users especially in the domain of movie reviews since different people value different aspects of a film, so automatically extracting a summary of the good and bad aspects of a review is more useful that assigning a single sentiment.
