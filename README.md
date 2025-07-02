# Text_Sentimental-Analysis
> This project uses machine learning to classify over 7,900 tweets about mobile phones into positive and negative sentiments.
> By analyzing real user opinions from social media, it uncovers public perception and emotional response to mobile brands.
> The labeled data enables robust training and evaluation of sentiment models for high accuracy.
> These insights guide product strategy, customer engagement, and brand positioning in a competitive market.

This Text/Sentiment Analysis project focuses on analyzing tweets to determine public sentiment about mobile phones. Using NLP and machine learning, it classifies tweet reviews as positive or negative, revealing customer perceptions and brand reputation. The model helps identify product strengths and pain points directly from real user feedback. These insights enable companies to refine marketing strategies and improve product offerings based on actual sentiment data.


### 🎯 **Project Objective**

To build an end-to-end sentiment analysis model that classifies tweet-based phone reviews into **positive** or **negative**, enabling insights into customer perception, product satisfaction, and brand reputation on social platforms.

---

### 🔄 **Key Changes & Preprocessing**

* **Data Cleaning** using:

  * Removal of mentions, hashtags, URLs, special characters
  * Contraction expansion (e.g., *“I'm” → “I am”*)
  * Lemmatization (reducing words to base form)
  * Stopword removal (combined from NLTK + sklearn)
* **Label Mapping** to match standard binary classification (1 = positive, 0 = negative)
* **EDA** (Exploratory Data Analysis):

  * Class balance check
  * Word frequency plots
  * Word clouds for visual sentiment vocabulary

---

### 🤖 **Machine Learning & NLP Pipeline**

1. **Text Preprocessing & Normalization**

   * Cleaning raw tweets, lemmatizing, removing stopwords
2. **Feature Engineering**

   * **Bag of Words (BoW)**
   * **TF-IDF (Term Frequency–Inverse Document Frequency)**
3. **Modeling**

   * **Logistic Regression** with:

     * Default hyperparameters
     * TF-IDF features
     * Class imbalance handling (`class_weight='balanced'`)
     * Regularization techniques (`L1`, `L2`, `C` tuning)
4. **Evaluation**

   * Accuracy on train/test datasets
   * Word frequency distributions by sentiment

---

### 📌 **Approach**

* **Supervised Learning**: Binary classification (positive/negative)
* **Data Split**: 80/20 training-test split with stratification
* **Interpretability**: Frequent word plots and word clouds
* **Class Imbalance Handling**: Weighted loss functions in logistic regression

---

### 🛠️ **Skills Required**

* **Python Programming**
* **NLP Techniques**: Tokenization, Lemmatization, Stopword Removal, BoW, TF-IDF
* **ML Modeling**: Logistic Regression, Hyperparameter Tuning
* **Libraries**: `pandas`, `numpy`, `nltk`, `sklearn`, `matplotlib`, `seaborn`, `wordcloud`
* **Data Visualization**: Frequency plots, WordClouds
* **Problem Solving & Data Interpretation**


