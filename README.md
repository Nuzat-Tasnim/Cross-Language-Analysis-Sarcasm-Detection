# A Cross-Language Analysis on Sarcasm Detection

This repository contains the Python code for the research work titled **"A Cross-Language Analysis on Sarcasm Detection"**.

## Overview

The project investigates the viability of the hypothesis - "*Performance variations in Sarcasm Detection models due to single model component changes (e.g., embeddings, classifiers) are independent of the target language*". Key components include:

- **Data Preprocessing**: Text data is preprocessed using the spaCy package (English), and BNLP and Bangla-Stemmer package (Bangla) in Python.
- **Feature Extraction**: Pre-trained models XLM-RoBERTa, mBERT and mT5 are used for feature extraction.
- **Classification**: Classification is performed with nine different classifiers - Support Vector Machine, Random Forest, Multinomial Naive Bayes, Logistic Regression, Decision Tree, K-Nearest Neighbour, LSTM, BiLSTM and XGBoost
- **Statistical Analysis**: A statistical Analysis was performed with the Wilcoxon Signed-Rank Test using the classification performances.

## Dataset
For this cross-language study, a Bangla dataset was used from [here](https://huggingface.co/datasets/sanzanalora/Ben-Sarc) and an English dataset was used from [here](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection).


## Results
 The Wilcoxon Signed-Rank Test yields a *p*-value of 0.21, unable to reject the hypothesis.


