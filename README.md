# SMS-Spam-Detection-Naive-Bayes
# Overview 
This project is a machine learning model designed to classify SMS messages as Spam or Ham (not spam). It uses the Multinomial Naive Bayes algorithm, which is particularly effective for text classification tasks. The dataset used consists of SMS messages labeled as spam or ham, and the model processes these messages to make predictions.

# Features
Text Preprocessing: Convert raw text data into a format that can be understood by machine learning algorithms.

Feature Extraction: Use CountVectorizer to transform SMS messages into feature vectors.

Train-Test Split: Split the data into training and test sets for validation.

Multinomial Naive Bayes: Train the model to classify SMS messages.

Performance Evaluation: Measure model performance with accuracy score, classification report, and confusion matrix.

# Dataset
The dataset used in this project is a collection of SMS messages labeled as either "spam" or "ham." It is loaded from a CSV file with the following columns:

label: The label for the message (spam or ham).

message: The actual content of the SMS.

Dataset file: SMSSpamCollection.csv

# Model Performance
The model achieves high accuracy, with results as follows:

Accuracy: 99%

Precision/Recall/F1-score: Excellent classification of both "spam" and "ham" messages, as shown in the detailed classification report.

Confusion Matrix: Visualization of the model’s performance.

# Results
Accuracy: 99%

Confusion Matrix:

The heatmap shows the confusion matrix, where the majority of predictions are correct.
