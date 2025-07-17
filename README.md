# Text_Sentimental-Analysis
> This project uses machine learning to classify over 7,900 tweets about mobile phones into positive and negative sentiments.
> By analyzing real user opinions from social media, it uncovers public perception and emotional response to mobile brands.
> The labeled data enables robust training and evaluation of sentiment models for high accuracy.
> These insights guide product strategy, customer engagement, and brand positioning in a competitive market.

This Text/Sentiment Analysis project focuses on analyzing tweets to determine public sentiment about mobile phones. Using NLP and machine learning, it classifies tweet reviews as positive or negative, revealing customer perceptions and brand reputation. The model helps identify product strengths and pain points directly from real user feedback. These insights enable companies to refine marketing strategies and improve product offerings based on actual sentiment data.


# 🎯 Objective #
The main objective of this project is to:

1) Analyze customer sentiments (positive or negative) based on their Twitter reviews about phones.

2) Use Natural Language Processing (NLP) techniques to process raw text data and build a classification model that accurately predicts the sentiment of a tweet.

# ⚠️ Key Challenges #
1) Noisy and Unstructured Text Data:

.  Tweets often contain slang, abbreviations, emojis, hashtags, and user mentions that make processing difficult.

2) Data Imbalance:

.  Sentiment classes may not be evenly distributed (e.g., more positive tweets than negative).

3) Preprocessing Complexity:

.  Cleaning involves removing special characters, stopwords, and performing stemming or lemmatization.

4) Feature Extraction:

. Converting text into numerical vectors using TF-IDF or CountVectorizer while preserving semantic meaning.

5) Model Generalization:

.  Ensuring the model doesn’t overfit due to over-cleaning or high dimensionality of vectorized features.

# 🧭 Approach #
1. Data Collection:

. Imported a dataset (tweets.csv) containing tweet texts and their associated sentiment labels.

2. Data Preprocessing:

. Removed URLs, mentions, special characters, and stopwords.

. Applied stemming using the Porter Stemmer.

. Tokenization of tweets.

3. Exploratory Data Analysis (EDA):

. Plotted sentiment distributions.

. Word clouds generated for both positive and negative sentiments to understand common terms.

4. Feature Engineering:

. Applied TF-IDF Vectorization to convert text into numerical format for model consumption.

5. Model Building:

. Trained multiple classifiers: Logistic Regression, Naive Bayes, Support Vector Machines (SVM), and Random Forest.

. Evaluated using accuracy, confusion matrix, and classification report (precision, recall, F1-score).

6. Model Evaluation:

. Compared performance across models.

. Logistic Regression and Naive Bayes provided better accuracy on the processed dataset.

# 🔍 Key Findings #
1. **Logistic Regression** and **Naive Bayes** achieved high performance in predicting tweet sentiment with relatively less computational cost.

2. Most positive sentiments used common marketing words like "best", "amazing", etc., while negative ones focused on issues like "battery", "hang", "worst".

3. Text cleaning and preprocessing significantly improved model performance.

# 🧾 Conclusion #
. The sentiment analysis model successfully classifies the polarity (positive or negative) of tweets about phones.

. NLP techniques such as tokenization, stemming, and TF-IDF vectorization are crucial for handling textual data.

. Logistic Regression and Naive Bayes are strong baseline models for this type of binary classification.

. This project provides a scalable approach for analyzing customer feedback on social media, which can be expanded to other domains and product categories.


