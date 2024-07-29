# **Email Context Spam Detection**

This project investigates using Support Vector Machines (SVMs) to classify emails as spam or non-spam (ham) based on their content.

**Key Points:**

- **Data:** Used a publicly available spam email dataset from Kaggle.
- **Preprocessing:**
  - Balanced the dataset using oversampling.
  - Converted text to lowercase.
  - Performed tokenization, lemmatization, and stopword removal.
  - Removed punctuation and vectorized the text data.
- **Models Compared:**
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machine (SVM)
- **Evaluation:**
  - SVM achieved the highest accuracy (over 98%) on the validation and test sets.
  - Confusion matrices were used to analyze model performance (True/False Positives/Negatives).
- **Testing:** The model accurately classified random spam and non-spam emails.

Overall, the SVM model showed excellent performance in classifying emails based on their content, making it a strong candidate for real-world spam filtering applications.
