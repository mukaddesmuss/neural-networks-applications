# Neural Networks: Machine Learning Applications

## About the Project

This project explores different Artificial Neural Network architectures through practical classification tasks using text and image datasets.

Four neural network approaches were implemented to examine their structures, training processes, and performance in different classification problems.

## Project Applications

### 1. Multilayer Neural Network (MLNN) – News Classification

- **Dataset:** Reuters
- **Objective:** Classify news articles into 46 different categories.
- **Approach:** A Sequential neural network with two hidden Dense layers (64 neurons each) and a 46-neuron output layer.
- **Techniques:** One-hot encoding, categorical cross-entropy, RMSprop optimization.
- **Validation Accuracy:** Approximately 81–82%.

### 2. Convolutional Neural Network (CNN) – Image Classification

- **Dataset:** Dogs vs. Cats
- **Objective:** Classify images as either cats or dogs.
- **Approach:** Conv2D, MaxPooling2D, Flatten, and Dense layers.
- **Techniques:** Image resizing (150x150), pixel normalization, binary classification, and RMSprop optimization.

### 3. Recurrent Neural Network (RNN) – Sentiment Analysis

- **Dataset:** IMDB Movie Reviews
- **Objective:** Classify movie reviews as positive or negative.
- **Approach:** Embedding and SimpleRNN layers followed by a Dense output layer.
- **Techniques:** Sequence padding, word embeddings, binary cross-entropy, and Adam optimization.

### 4. Long Short-Term Memory (LSTM) – Sentiment Analysis

- **Dataset:** IMDB Movie Reviews
- **Objective:** Perform binary sentiment classification of movie reviews.
- **Approach:** Embedding and LSTM layers with a sigmoid output layer.
- **Techniques:** Sequence preprocessing, word embeddings, and RMSprop optimization.

## Tools & Technologies

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Artificial Neural Networks
- Deep Learning
- Natural Language Processing
- Image Classification
- Sentiment Analysis

## Key Learning Outcomes

- Understanding different neural network architectures.
- Implementing MLNN, CNN, RNN, and LSTM models.
- Applying neural networks to text and image classification problems.
- Understanding data preprocessing techniques for different data types.
- Monitoring training and validation accuracy and loss.
- Identifying potential overfitting during model training.

## Project Status

**Completed – Academic Project (2026)**

## Keywords

Artificial Neural Networks, Deep Learning, MLNN, CNN, RNN, LSTM, Reuters, IMDB, Image Classification, Sentiment Analysis, Python, TensorFlow, Keras
