## Chatbot Project
<img src="./images/chatbot.png"/>
The goal of this project is to create a chatbot that can understand and respond to user input based on intents. The chatbot is built using Natural Language Processing (NLP) library and Logistic Regression, to extract the intents and entities from user input. The chatbot is built using Streamlit, a Python library for building interactive web applications.

## Overview
The project is divided into two parts:
1. NLP techniques and Logistic Regression algorithm is used to train the chatbot on labeled intents and entities.

2. For building the Chatbot interface, Streamlit web framework is used to build a web-based chatbot interface. The interface allows users to input text and receive responses from the chatbot.

## Features
- Interactive web interface for user interaction.
- Logs conversation history to a CSV file.
- Trained using Logistic Regression for intent classification.

## Requirements
To run this project, you need to install the following Python packages:
- `nltk`
- `streamlit`
- `scikit-learn`

You can install the required packages using the following command:
```
pip install -r requirements.txt
```

## Usage
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run the chatbot using Streamlit:
   ```
   streamlit run app.py
   ```
4. Open the provided URL in your web browser to interact with the chatbot.

# Dataset
The dataset used in this project is a collection of labelled intents and entities. The data is stored in a list.
- Intents: The intent of the user input (e.g. "greeting", "budget", "about")
- Entities: The entities extracted from user input (e.g. "Hi", "How do I create a budget?", "What is your purpose?")
- Text: The user input text.

# Streamlit Chatbot Interface
The chatbot interface is built using Streamlit. The interface includes a text input box for users to input their text and a chat window to display the chatbot's responses. The interface uses the trained model to generate responses to user input.

# License
This project is open-source and available under the MIT License.
