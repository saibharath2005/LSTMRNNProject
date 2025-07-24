# 🔤 Next Word Prediction using LSTM with Streamlit

This project is an NLP application that uses a trained **LSTM (Long Short-Term Memory)** neural network to predict the **next word** in a given sequence of text. It includes a **Streamlit web interface** for real-time interaction.

---

## 🚀 Demo

📥 Input: `To be or not to`  
🔮 Next Word PRediction: `in't`

---

## 📌 Features

- 🔡 Predicts the next word in a sentence using LSTM
- 🧠 Trained on Shakespearean-style text (or any corpus of your choice)
- 🧪 Real-time word prediction via a simple Streamlit UI
- 📊 Displays predicted word

---

## 🧰 Tech Stack

- Python 3.10+
- TensorFlow / Keras
- NumPy
- Pickle
- Streamlit
- LSTM model (Trained using Tokenizer & Sequential input text)

---

## 🧠 How It Works

1. User enters a partial sentence (e.g., "to be or not to")
2. The text is tokenized using a pre-trained tokenizer
3. Sequence is padded and passed into the LSTM model
4. The model predicts the most probable next word
5. The predicted word is shown in the UI
