# ChatBot
Chatbot Using Bag of Words Model

## Overview:

This project implements a chatbot using a Bag of Words (BoW) model combined with a neural network for text classification. The chatbot is designed to classify user inputs into predefined categories and provide relevant responses based on the classification.

## Libraries Used:
json: For handling JSON data.
string: For string operations and manipulations.
random: For generating random numbers and shuffling data.
nltk: The Natural Language Toolkit, used for text preprocessing tasks such as tokenization and lemmatization.
numpy: For numerical operations and array manipulations.
tensorflow: A popular machine learning library used for building and training the neural network model.
tensorflow.keras: High-level API for building and training neural network models.


## Setup
Prerequisites
Ensure you have the following Python libraries installed:

1.numpy
2.nltk
3.tensorflow
You can install these dependencies using pip:

pip install numpy nltk tensorflow


## Data Preparation
Text Preprocessing: The chatbot uses the Bag of Words model to convert text into numerical features. Texts are tokenized and lemmatized to standardize and normalize the data.
Model Training: The features are used to train a neural network, which classifies input text into different categories.
Usage


## Clone the Repository:
git clone https://github.com/Jiya003/ChatBot.git
Note: Please navigate to the Project Directory

cd your-repository


## Prepare Your Data: 
Ensure you have your data ready in the required format. The repository includes scripts for processing text data and training the model.
Run Training Script: Execute the script to preprocess the data and train the neural network.


python chatbot.py

License
This project is licensed under the MIT License. See the LICENSE file for details.
