#Spam Mail Detection System

This project is a machine learning-based spam mail detection system that classifies email messages as either spam or non-spam (ham). Using a dataset of labeled emails, the system preprocesses the text, extracts key features using TF-IDF (Term Frequency-Inverse Document Frequency), and applies logistic regression to accurately detect spam.

##Features

Text Preprocessing: Cleans and tokenizes email content.
Feature Extraction: Utilizes TF-IDF to convert text into numerical data.
Model Training: Logistic regression is employed to classify messages.
Evaluation: Tests the accuracy of the model on unseen data.

##Dataset

The dataset consists of two columns:

1. `Category` - Label indicating whether the email is spam or ham.
2. `Message` - The text content of the email.

##Prerequisites

Ensure that you have the following installed:
1.Python 3.7+
2.Jupyter Notebook (for running the project in a notebook environment)

##Installation

###Clone the Repository
```
git clone https://github.com/yourusername/spam-mail-detection.git
cd spam-mail-detection
```
###Install Required Libraries

Run the following command to install the required Python libraries:

```
pip install -r requirements.txt
```
`requirements.txt` should contain:

```
numpy
pandas
scikit-learn
jupyter
```
###Run the Project

1.Open the Jupyter Notebook:
```
jupyter notebook Spam_Mail_Detection.ipynb
```
2.Execute the cells in the notebook to preprocess the data, train the model, and evaluate its performance.

##Usage

Preprocess the dataset to remove unwanted characters and extract relevant features.
Train the logistic regression model on the processed data.
Test the model’s accuracy using the provided test set or new data.

##Contributing

If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are welcome!

##License

This project is licensed under the MIT License.
