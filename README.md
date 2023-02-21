# Spam_mail_detection

This project  implements a spam mail detection system using the decision tree classifier. The project loads email data from a CSV file, pre-processes it by replacing null values and labeling spam emails as 1 and ham emails as 0. It then splits the data into a training set and a test set, uses the TfidfVectorizer to extract features from the text data, and trains a decision tree classifier model on the training data. The project evaluates the accuracy of the model on both the training data and the test data, and allows the user to input a mail message and predicts whether it is spam or ham.

### Requirements
Python 3.x
numpy
pandas
scikit-learn

### Usage
Clone the repository to your local machine
Install the required libraries using pip install -r requirements.txt
Run python spam_mail_detection.py
Enter a mail message when prompted and the system will predict whether it is spam or ham.

### Dataset
The dataset used for this project can be found in mail_data.csv. It contains email messages labeled as spam or ham.
