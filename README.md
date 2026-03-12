# Next Word Prediction using LSTM RNN

This project builds a deep learning model that predicts the next word in a sentence using an LSTM-based Recurrent Neural Network. The model learns patterns from text data and generates the most probable next word based on the input sequence. A tokenizer converts words into numerical sequences, which are then used to train the LSTM model.

The trained model and tokenizer are saved and later loaded in a Streamlit web application that allows users to enter a sentence and receive a predicted next word in real time.

This project demonstrates key NLP concepts such as text preprocessing, tokenization, sequence padding, and sequence modeling using LSTM networks.

Technologies used include Python, TensorFlow/Keras, NumPy, and Streamlit.

Repository Structure

model/ – contains the trained LSTM model and tokenizer
notebook/ – data preprocessing and model training notebook
app.py – Streamlit application for prediction
requirements.txt – project dependencies

How to Run

Install dependencies

pip install -r requirements.txt

Run the Streamlit app

streamlit run app.py

Use Case

Next word prediction is used in real-world applications like autocomplete systems, smart keyboards, search suggestions, and chatbots.
