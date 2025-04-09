# Spam Detection with LSTMs

This project uses Natural Language Processing (NLP) and sequential models, specifically Long Short-Term Memory networks (LSTMs), to detect spam messages. The dataset used for this project is the SMS Spam Collection Dataset from Kaggle.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
Spam detection is a critical task in the field of communication, aimed at filtering out unwanted messages. This project leverages NLP techniques and LSTM networks to classify SMS messages as spam or ham (non-spam).

## Dataset
The dataset used in this project is the [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset) from Kaggle. It contains a collection of SMS messages that have been labeled as either spam or ham.

## Model
The model used in this project is an LSTM network. LSTMs are a type of recurrent neural network (RNN) capable of learning order dependence in sequence prediction problems. This makes them suitable for tasks such as spam detection, where the order of words in a message can be important for classification.

## Installation
To run this project, you need to have Python installed along with the required libraries. You can install the necessary dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage
To train and test the model, run the ```main.ipynb``` notebook. This notebook contains all the steps from data preprocessing, model training, and evaluation.

## Results
The performance of the model can be evaluated using metrics such as accuracy, precision, recall, and F1-score. These metrics help in understanding the effectiveness of the spam detection model.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.
