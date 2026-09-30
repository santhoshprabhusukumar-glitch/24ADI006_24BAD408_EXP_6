# Experiment No. 6 – Implementation of LSTM for Sentiment Analysis

This experiment implements a Long Short-Term Memory (LSTM) neural network for sentiment analysis of text reviews. The IMDB Movie Reviews dataset is used to classify reviews into positive and negative sentiments. The experiment involves loading and exploring the dataset, preprocessing the text data, tokenizing the reviews, converting words into numerical sequences, and applying sequence padding to make all input sequences equal in length. An Embedding layer is used to convert the numerical sequences into dense vector representations, followed by an LSTM layer to learn sequential dependencies and a Dense output layer to perform binary sentiment classification. The model is trained and validated using TensorFlow/Keras, and its performance is evaluated using accuracy, precision, recall, F1-score, and a confusion matrix. Accuracy and loss graphs are also plotted to analyze the training performance. Sample reviews are given to the trained model to predict whether their sentiment is positive or negative. This experiment demonstrates how LSTM networks can effectively learn contextual and sequential information from text for sentiment classification.

**Technologies Used:** Python, TensorFlow/Keras, NumPy, Pandas, Matplotlib, Scikit-learn, and Google Colab.

**Dataset:** IMDB Movie Reviews Dataset.

**Model Architecture:** Embedding Layer → LSTM Layer → Dense Layer with Sigmoid Activation.

**Result:** The trained LSTM model classifies movie reviews into positive and negative sentiment categories and is evaluated using standard classification metrics.

# 24ADI006_24BAD408_EXP_6
