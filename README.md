# 📌 Sentiment Prediction Using TensorFlow

A simple sentiment analysis model built using TensorFlow and Keras. This project tokenizes text, applies word embeddings, and classifies sentiments.

## 🚀 Features
- Tokenization and padding of text sequences
- Word embedding using Keras' `Embedding` layer
- Binary classification of sentiment (positive/negative)
- Simple sequential model architecture

## 🛠️ Installation
To run this project locally, follow these steps:

1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/sentiment-prediction.git
   cd sentiment-prediction
   ```
2. **Install dependencies**
   ```sh
   pip install tensorflow numpy
   ```
## 📂 Dataset
The dataset consists of manually labeled sentences indicating positive (1) or negative (0) sentiment.

## 🔧 Model Architecture
Embedding Layer: Converts words into dense vectors
Flatten Layer: Flattens the embeddings
Dense Layers: Fully connected layers for classification

## 🏃 Usage
Run the Jupyter Notebook:
```sh
jupyter notebook sentiment_prediction.ipynb
```

## 🔍 Example Sentences:
```sh
sentences = ["I am feeling good", "The food tasted very bad", "Momo tastes great"]
```
