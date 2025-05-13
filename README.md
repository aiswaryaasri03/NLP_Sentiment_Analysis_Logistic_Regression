# NLP Sentiment Analysis on Tamil Movie Reviews using Logistic Regression
This project performs Sentiment Analysis on Tamil movie reviews using Natural Language Processing (NLP) techniques and a Logistic Regression model. The sentiment is categorized into Negative, Neutral, and Positive.

---

## Features

- Text preprocessing: punctuation removal, tokenization, and stopword removal (Tamil-specific).
- Feature extraction using `CountVectorizer`.
- Sentiment classification using `LogisticRegression`.
- Evaluation with:
  - Confusion Matrix
  - Classification Report
  - ROC Curves
  - Precision-Recall Curves
  - Pie chart showing class distribution

---

## Dataset

The dataset (`tamil_movie_reviews_train.csv`) contains Tamil movie reviews with the following columns:

- `ReviewId`: Unique identifier for each review
- `ReviewInTamil`: Text review in Tamil
- `Rating`: Numerical rating
- `Feedback`: Sentiment label (`0 = Negative`, `1 = Neutral`, `2 = Positive`)
