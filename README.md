# SMS Spam Detection System 
## STEMMING + BAG OF WORDS + MULTINOMIAL NAIVE BAYES
This project implements an SMS spam detection system. The goal is to classify SMS messages as either "spam" or "ham" (not spam). The following steps outline the process involved in building and evaluating the model:

## Steps:
1. **Text Preprocessing and Cleaning**: This involves preparing the SMS data by removing unnecessary elements, dropping null values, and applying stemming to reduce words to their root forms.

2. **Train-Test Split**: The dataset is divided into training and testing sets to evaluate the model's performance effectively.

3. **Text Vectorization - Bag of Words (BOW)**: The SMS text data is converted into numerical format using the Bag of Words model, enabling the machine learning algorithms to process the data.

4. **Train ML Model**: A Multinomial Naive bayes model is trained on the training data to learn the characteristics of spam and non-spam messages.

5. **Evaluation**: The trained model is evaluated using the test set, and performance metrics are calculated to assess its accuracy and effectiveness in detecting spam messages.

## Dataset: 
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset
