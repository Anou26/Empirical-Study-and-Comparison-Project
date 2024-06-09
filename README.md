### Overview

This project presents an empirical study on sentiment analysis of COVID-19 tweets during the pandemic. Various Machine Learning (ML) and Deep Learning (DL) techniques are utilized to analyze and predict the sentiments expressed in tweets.

### Objectives

- Analyze people's attitudes (positive, negative, neutral) during the COVID-19 pandemic using tweets.
- Compare the performance of different ML and DL models based on evaluation metrics like accuracy, precision, recall, and F1-score.

### Methods

- **Data Collection**: Tweets related to COVID-19 were collected from the Twitter dataset on GitHub.
- **Preprocessing**: Natural Language Processing (NLP) techniques such as tokenization, lemmatization, and vectorization were applied.
- **Models Used**:
  - Machine Learning: Naive Bayes, Logistic Regression, Extreme Gradient Boost (XGBoost), Stochastic Gradient Descent (SGD), Random Forest, Support Vector Machine (SVM).
  - Deep Learning: Bidirectional Long Short-Term Memory (BiLSTM), Backpropagation Neural Networks (BPNN).

### Key Steps

1. **Text Mining and NLP**: Clean and preprocess tweet data to remove redundancies.
2. **Exploratory Data Analysis (EDA)**: Visualize data distributions and sentiment trends.
3. **Model Training**: Train various ML and DL models on the preprocessed data.
4. **Evaluation**: Compare model performances using metrics such as accuracy, precision, recall, and F1-score.

### Results

- The **Stochastic Gradient Descent (SGD)** model achieved the highest accuracy of 92%.
- **Random Forest** and **Logistic Regression** models also performed well with accuracies of 91% and 90% respectively.
- **Deep Learning models (BiLSTM and BPNN)** achieved accuracies of 83% and 84%.

### Conclusion

The study successfully analyzed sentiments during the COVID-19 pandemic and provided valuable insights. Future work could focus on multilingual tweets and enhancing model accuracies.
