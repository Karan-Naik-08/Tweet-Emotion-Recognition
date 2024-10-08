# Tweet Emotion Recognition with TensorFlow
This project is a guided Coursera project focused on building a Tweet Emotion Recognition model using TensorFlow. The goal of the project is to predict the emotion conveyed by a tweet, classifying it into one of six different emotion categories.

## Project Overview
The project involves creating a machine learning model that can classify a tweet into one of the following emotion categories:
- Anger
- Fear
- Joy
- Sadness
- Surprise
- Love
The dataset used for training the model consists of labeled tweets, each corresponding to one of the six emotion classes.

## Key Steps
### Data Preprocessing:
Loaded and cleaned the tweet dataset.
Performed tokenization and padding of the tweets using TensorFlow's Tokenizer and pad_sequences.
Converted the target emotions into numeric labels for training.

### Model Building:
Built a deep learning model using TensorFlow and Keras.
The model consists of an embedding layer, followed by LSTM (Long Short-Term Memory) layers to capture sequential dependencies in the tweets.
Fully connected (dense) layers were used for classification into one of the six emotion categories.

### Model Training:
The model was trained on a dataset of tweets labeled with emotions.
Applied various optimizers and techniques to improve accuracy and minimize loss.

### Model Evaluation:
Evaluated the model's performance using metrics like accuracy and loss.
Tested the model on unseen tweets to predict their emotions.

## Tools and Libraries Used
- TensorFlow: For building and training the neural network.
- Keras: High-level API for designing deep learning models.
- Pandas: For data manipulation.
- NumPy: For numerical operations.
## Conclusion
The project successfully creates a machine learning model that can predict the emotion of a given tweet with reasonable accuracy. The model can be further improved with additional tuning and a more diverse dataset.

