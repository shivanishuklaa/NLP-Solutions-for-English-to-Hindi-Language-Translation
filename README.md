# NLP-Solutions-for-English-to-Hindi-Language-Translation

This repository hosts a comprehensive language translation application designed to translate English text into Hindi. It leverages the state-of-the-art Helsinki-NLP/opus-mt-en-hi model from Hugging Face's Transformers library and provides a user-friendly interface powered by Streamlit.

# Key Features

1. Real-time Translation: Effortlessly translate English text into Hindi with minimal latency.
2. Pre-trained Model Integration: Utilizes the robust Helsinki-NLP/opus-mt-en-hi model for accurate and reliable translations.
3. Intuitive Interface: Built with Streamlit, offering a seamless user experience.
4. Customizable and Extendable: Easy to modify and adapt for other language pairs or additional features.

# Installation and Setup

Prerequisites
Ensure you have the following installed:

Python 3.9
# Set Up Hugging Face Token:

Obtain a Hugging Face API token by signing up here.
Replace the placeholder in app.py:
os.environ['HF_TOKEN'] = 'your_hugging_face_token'

# Run the Application:
Launch the Streamlit application by executing the following command:

streamlit run app.py

# Access the App:
Open your browser and navigate to:

http://localhost:8501

# Usage Guide

Launch the Streamlit application.

1. Enter the English text into the input text box.
2. Click the "Translate" button to generate the Hindi translation.
3. View the translated text displayed below the button.

# Dependencies

The project depends on the following Python libraries:

1. streamlit: For building the interactive web interface.
2. transformers: For utilizing the Hugging Face pre-trained model.
3. tensorflow: For running the TensorFlow-based translation model.
