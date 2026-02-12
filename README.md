# RNN
Project Overview

Movie reviews contain natural language, and understanding whether a review expresses a positive or negative sentiment is a classic NLP task.

In this project:

IMDb dataset is loaded from TensorFlow

Text reviews are preprocessed and padded

A SimpleRNN model is built and trained

EarlyStopping callback is used to prevent overfitting

The trained model is saved as a .h5 file

A sample review is tested and achieved:

Prediction = 0.99

Sentiment = Positive
📂 Dataset Information

The dataset is the IMDb Movie Reviews dataset, containing:

50,000 movie reviews

25,000 for training

25,000 for testing

Each review is labeled:

1 → Positive

0 → Negative
🧠 Model Architecture

The model is built using Keras with the following layers:

Embedding Layer → converts word IDs into dense vectors

SimpleRNN Layer → learns sequential patterns in text

Dense Output Layer → sigmoid activation for binary classification
🧪 Testing on Custom Review

A custom review can be tested by:

Converting review text into sequences using the word index

Padding the sequence

Passing it to the model for prediction

The model returns a probability between 0 and 1.
🛠️ Technologies Used

Python

TensorFlow / Keras

Google Colab

NumPy

IMDb dataset (Keras)

🌟 Key Learning Outcomes

Through this project, I learned:

How to use IMDb dataset from Keras

Text preprocessing using word indexing

Padding sequences for RNN input

Building an RNN model for NLP tasks

Using EarlyStopping for better training

Saving and loading trained models

Predicting sentiment from real-world text input

