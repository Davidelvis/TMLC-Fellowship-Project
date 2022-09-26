## Business Overview

Text Classification is one of the essential applications of Natural Language Processing. Neural network-based methods have obtained significant progress on various natural language processing tasks. As deep learning is emerging, training complex data has become faster and easier with networks like RNNs and LSTM.

 In this Project, we will Classify the description of E-commerce products into 4 categories by implementing any NLP approach for analysis and modeling on the provided dataset.


## Objective

To perform text classification on the E-commerce products dataset using RNN and LSTM models

## Data Description

The dataset contains more than fifty thousand descriptions about E-commerce products. We have two columns, where one contains the actual text of the description of the products and one column containing the products.


## Approach

1. Installing the necessary packages through pip command

2. Importing the required libraries

3. Defining configuration file paths

4. Process glove embeddings
    - Read the text file
    - Convert embeddings to float array
    - Add embeddings for padding and unknown items
    - Save embeddings and vocabulary

5. Process Text data
    - Read the CSV file and drop the null values
    - Replace duplicate labels
    - Encode the label column and save the encoder and encoded labels

6. Data Preprocessing
    - Conversion to lower case
    - Punctuation removal
    - Digits removal
    - Additional spaces removal
    - Tokenization

7. Building Data loader

8. Model Building
    - RNN architecture
    - LSTM architecture
    - Train function
    - Test function

9. Model training
    - RNN model
    - LSTM model

10. Prediction on Test data