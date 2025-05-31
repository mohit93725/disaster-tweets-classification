# Disaster Tweets Classification

This project uses the BERT (`bert-base-uncased`) model to classify tweets from the Kaggle competition **“Natural Language Processing with Disaster Tweets”**. The goal is to predict whether a given tweet is about a real disaster (1) or not (0).

---

## Key Features

Fine-tuned BERT (`bert-base-uncased`) for binary classification  
Preprocessing of tweets by combining `keyword`, `location`, and `text` fields  
Achieved ~79% accuracy on the validation set  

---

## Files

- **`natural-language-processing-with-disaster-tweets.ipynb`**: Kaggle Notebook with full data cleaning, BERT fine-tuning, and submission generation  

---

##  How to Run

Clone this repo:  
```bash
git clone https://github.com/mohit93725/disaster-tweets-classification.git
cd disaster-tweets-classification
