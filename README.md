# 🧠 Quora Question Pair Detection
## 📘 Project Overview
This project tackles the widespread issue of duplicate questions on the Quora platform using advanced Natural Language Processing (NLP) techniques. By analyzing over 400,000 question pairs from a Kaggle dataset, our goal is to classify whether two questions are semantically equivalent. Duplicate question detection not only declutters the platform but also ensures better content relevance and user experience.

Implemented and compared several models:

- TF-IDF and Doc2Vec: As traditional similarity-based baselines.

- LSTM (Long Short-Term Memory): A sequential neural network to capture contextual relationships.

- Siamese BERT: A state-of-the-art transformer-based architecture using twin BERT encoders and L1 distance to assess semantic similarity.

## 📊 Summary
After extensive preprocessing, feature engineering, and model experimentation, Siamese BERT emerged as the top-performing model, achieving an accuracy of 89%. The project demonstrates how deep learning and transformer-based models can effectively outperform traditional NLP techniques in understanding sentence-level semantics. While our original plan included building a platform to return the top 5 most similar questions, data limitations shifted our focus to binary classification, providing a strong foundation for further development.
