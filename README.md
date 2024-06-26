# Semantic Similarity Detection

## Project Description
This is a Natural Language Processing project used for Semantic Similarity Detection or Paraphrase Identification, using Siamese Neural Network approach.\
Dataset can be downloaded at: https://drive.google.com/file/d/1EMx67iZn5fsn4FJ1B2rUscEDhPj2zfwH/view?usp=sharing, containing tsv files.\
The "Semantic_Similarity_Detection.ipynb" uses many python Libraries (Numpy, Pandas, Sklearn,...) and Tensorflow, training on Google Colab.

## Project Outline
There are 4 main parts:
1. Preprocess Data: Using a number of techiques like Tokenization, Stop Words Removal, Part-Of-Speech Tagging, Lemmatization, Padding
2. Define Model: With Siamese Neural Network approach using LSTM architecture, defined in the jupyter notebook file.
3. Train the models: Setting the Hyperparameters and using EarlyStopping and Adam Optimizer
4. Evaluation: Using Accuracy and F1-score metrics for evaluation

## Instructions to run the code
In the "Semantic_Similarity_Detection.ipynb" jupyter notebook, select "Run all".
