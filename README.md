## Metis Project 4: Natural Language Processing & Unsupervised Learning
### NLP of Joe Biden's 2020 Election Tweets

by [Matt Ranalletta](https://www.linkedin.com/in/matthewranalletta/)

## Summary

This project was my first foray into natural language processing and topic modeling using Joe Biden's 2020 election tweets - an 18-month period from his declaration of candidacy on April 25, 2019 through October 31, 2020, right before the general election. The goal was to find topic trends over the course of the campaign, especially in the primary vs. general election and through the COVID-19 pandemic.

## Methodologies

1. Found a [Kaggle set of Joe Biden's tweets](https://www.kaggle.com/rohanrao/joe-biden-tweets).
2. NLP preprocessing: 
    - removal of apostrophes, special characters, non-English words, etc.
    - lemmatization
    - removal of stop words, min_df and max_df set
    - TD-IDF vectorization
3. NMF topic modeling and optimization
4. Visualization
    - Wordlcloud
    - K-means clustering
    - Document Type similarity with PCA and t-SNE

## Findings and Conclusions

I found 10 pretty discrete topics in the tweets, with the top two most occurring topics being about Trump and healthcare. The 2020 election was a repudiation of Donald Trump, so it makes sense that many tweets would be about him. The consensus is that healthcare and the defending of the Affordable Care Act was a big reason Democrats won back the House of Representatibes in 2018, so it's no surprise that it continued to be the biggest policy issue in 2020, especially during the COVID-19 pandemic.

## Deliverables

- [NLP Notebook](https://github.com/mattranalletta/04_biden_election_tweets_NLP/blob/main/code/biden_tweets_NLP.ipynb)
- [Presentation - Google Slides](https://docs.google.com/presentation/d/1YA9d4hFXM-0iyGGHcCYHzsSTAXSwLso-KszxsPpfrBg/edit?usp=sharing) / [PDF](https://github.com/mattranalletta/04_biden_election_tweets_NLP/blob/main/presentation/Joe%20Biden's%20Election%20Tweets.pdf)

## Technologies and Libraries Used

- Jupyter Notebook
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Wordcloud
- NLTK
- TDIDF vectorizer
- PCA
- t-SNE

## Skills Demonstrated

- Natural Language Processing
- Unsupervised Learning
- Dimensionality Reduction
- Topic Modeling
- Clustering
- Visualization
