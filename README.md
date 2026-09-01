# Spotify App Review Analysis — NLP

A product-analytics project that uses Natural Language Processing to analyze Spotify user reviews, classify sentiment, and identify recurring themes in customer feedback.

## Business Question

How can large volumes of app-review text be converted into structured product insights that help teams understand user satisfaction and recurring pain points?

## Approach

The project applies a standard NLP workflow:

1. Review-text cleaning
2. Tokenization and text normalization
3. Stopword and punctuation handling
4. Lemmatization
5. Sentiment classification
6. Context/theme analysis
7. Visualization and interpretation

## Findings from the Analysis

The documented review analysis highlights several recurring themes:

- negative sentiment associated with **advertising and playback issues**
- positive feedback around **playlist personalization and music recommendations**
- technical problems such as **app crashes** appearing as a source of dissatisfaction

These findings are descriptive signals from the project dataset and are not presented as representative of Spotify's complete user base.

## Product Relevance

Review analytics can help product and customer-experience teams:

- identify recurring customer pain points
- prioritize areas for deeper product investigation
- track sentiment themes over time
- complement quantitative product metrics with qualitative feedback

## Tech Stack

- **Python / Jupyter Notebook**
- **pandas**
- **NLTK**
- **TextBlob**
- **Matplotlib**
- **Seaborn**

## Repository Contents

- [`Natural_Language_Processing_context_analysis_Aprip26.ipynb`](Natural_Language_Processing_context_analysis_Aprip26.ipynb) — NLP analysis notebook
- `Spotify reviews.csv` — review dataset

## Skills Demonstrated

Natural Language Processing · Sentiment analysis · Text preprocessing · Product analytics · Customer feedback analysis · Python · Data visualization

## Potential Extensions

- topic modeling for more systematic theme extraction
- transformer-based sentiment classification
- time-based sentiment monitoring
- integration with product KPIs for deeper product analysis
