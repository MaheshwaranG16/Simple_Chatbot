# Simple Chatbot in Python using NLTK

This repository contains a simple rule-based chatbot implemented in Python using the Natural Language Toolkit (NLTK). The chatbot responds to user inputs based on predefined patterns and responses.

## Description

A chatbot (also known as a talkbot, chatterbot, Bot, IM bot, interactive agent, or Artificial Conversational Entity) is a computer program or artificial intelligence that conducts a conversation via auditory or textual methods. This simple chatbot uses NLTK's `Chat` module and a set of predefined patterns and responses to simulate a conversational agent.

 ### Features

- Recognizes basic greetings and introductions.
- Responds to questions about its name and well-being.
- Offers simple conversational interactions.
- Exits the conversation when the user types "quit".

- ## Getting Started

### Prerequisites

Ensure you have Python installed. This project requires NLTK, which can be installed using pip:

```sh
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
```
