# Language-Translation-French-to-English--LSTM


This project implementats **sequence-to-sequence (seq2seq)** model using **LSTM networks** to translate short English sentences into French. It's built using TensorFlow and Keras.

---

## 🚀 Features

- Translates English sentences into French
- Trained on the [Tatoeba Project](https://tatoeba.org/) dataset
- Uses **Encoder-Decoder architecture** with LSTM layers
- Supports **custom sentence inference**
- Easily runnable in **Google Colab** or local environment (Anaconda recommended)

---

## 🧠 Model Architecture

- **Encoder**: LSTM layer processes the input English sentence and returns hidden states.
- **Decoder**: Another LSTM layer uses the encoder's states to predict the French translation one word at a time.
- **Training**: Teacher forcing with start (`<start>`) and end (`<end>`) tokens.
- **Loss Function**: Categorical crossentropy with one-hot encoded targets.

---



