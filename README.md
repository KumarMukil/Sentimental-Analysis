🧠 Sentiment Analysis on Women’s E-Commerce Clothing Reviews
A machine learning project that performs sentiment analysis on real-world customer reviews from a women’s clothing e-commerce platform using Natural Language Processing (NLP) techniques.

📁 Dataset
Source: Kaggle - Women's E-Commerce Clothing Reviews

Description: Contains 23,000+ reviews with attributes like review text, rating, title, age, product ID, and recommendation status.

🛠️ Technologies Used
Language: Python

Libraries:

pandas, numpy for data manipulation

matplotlib, seaborn for data visualization

nltk for NLP and text preprocessing

scikit-learn for machine learning models

✨ Key Features
✅ Exploratory Data Analysis (EDA)

✅ Text Preprocessing:

Lowercasing

Punctuation removal

Stopword removal

✅ Sentiment Labeling:

Rating ≥ 4 → Positive

Rating ≤ 2 → Negative

Rating = 3 → Neutral (excluded for binary classification)

✅ Feature Engineering using TF-IDF Vectorization

✅ Training of multiple ML models:

Logistic Regression

Multinomial Naive Bayes

Random Forest

✅ Performance Evaluation using Accuracy and F1-Score

📊 Results
TF-IDF Vectorization improved classification accuracy.

Logistic Regression and Multinomial Naive Bayes provided the best performance.

Achieved high accuracy for binary sentiment classification.
