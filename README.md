Project Overview

This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.
## Data Description
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

Data includes:
- Reviews from Oct 1999 - Oct 2012
- 568,454 reviews
- 256,059 users
- 74,258 products
- 260 users with > 50 reviews

Data link: [Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
## EDA Goals
To determine whether reviews are positive, negative, or neutral, I'll using 2 natural language processing (NLP) techniques following:
- VADER (Valence Aware Dictionary and sEntiment Reasoner). Model link: [VADER](https://github.com/cjhutto/vaderSentiment)
- RoBERTa-base for Sentiment Analysis. Model link: [RoBERTa](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment)   
