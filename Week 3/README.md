# Week 3: Building Your First Fake News Detector 

Welcome to Week 3! 

In the last two weeks, you mastered Python basics and learned the theory behind NLP and Machine Learning. Now, it's time to bridge the gap between theory and practice.

This week, you will build your **first Machine Learning model** (Logistic Regression) to classify news as **Real** or **Fake**. 

> ** Note:** Don't be intimidated by the new libraries. We are using `scikit-learn`, which is the industry standard for machine learning in Python. It is designed to be user-friendly!

---

##  Files You Need
Please ensure you have downloaded the following files from this repository folder before starting:

1.  **`dataset1.csv`**: This is your data. It contains news text with labels (`1` for Real, `0` for Fake).
2.  **`samplenotebook.ipynb`**: This is your workspace. I have created a skeleton code for you. Your task is to fill in the blanks, understand the code, and run it.

---

##  Resources (Read These First!)
To successfully complete the notebook, you need to understand the tools we are using. Go through these resources in the **exact order** below:

### 1. The "Grammar" of Scikit-Learn 
Before you write a single line of ML code, you need to understand how the library works. In `scikit-learn`, almost every model follows the same pattern: `Fit` (train) → `Predict` (test).
* **Read this:** [Scikit-Learn Getting Started](https://scikit-learn.org/stable/getting_started.html)
    * *Focus mainly on the "Fitting and predicting: estimator basics" section.*

### 2. Cleaning Text with Regex 
Real-world data is messy (URLs, punctuation, weird symbols). We use **Regular Expressions (Regex)** to clean it.
* **Practice this:** [RegexOne Interactive Tutorial](https://regexone.com/)
    * *Action:* Complete the first **5 lessons**. This will teach you how to target specific characters, which is crucial for our cleaning function.

### 3. Turning Words into Numbers (TF-IDF) 
Computers can't read English; they only understand math. We use **TF-IDF** to turn our news articles into numerical vectors.
* **The Concept:** [TF-IDF Term Weighting](https://scikit-learn.org/stable/modules/feature_extraction.html#tfidf-term-weighting) (Read only the 6.2.3.4 section).
* **The Tool:** [TfidfVectorizer Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html).
    * *Look closely at parameters like `stop_words` and `max_df`. You will need them in the notebook!*

---

##  Your Assignment: The Walkthrough

1.  **Download** the `samplenotebook.ipynb` file and open it in Google Colab or Jupyter Notebook.
2.  **Upload** the `dataset1.csv` file to your notebook environment.
3.  **Run the notebook**
4.  **Analyze:** Look at the "Major Features" section at the end. Which words does the model think are "Fake"? Does it make sense?
5.  **Mail** the notebook after running it to me

---
