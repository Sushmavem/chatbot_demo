# Chatbot with OpenAI API

This project demonstrates how to interact with OpenAI's GPT-3.5-turbo model using Python. It provides a simple command-line chatbot interface that allows users to chat with the AI. The chatbot uses OpenAI's API to generate responses based on user input.

## Features

- Chat with OpenAI's GPT-3.5-turbo model.
- Simple command-line interface.
- Error handling for API-related issues.
- Option to exit the chat by typing `quit`, `exit`, or `bye`.

## Requirements

- Python 3.x
- OpenAI Python library
- An OpenAI API key

## Installation

### 1. Clone the repository:

git clone https://github.com/yourusername/chatbot_ex.git
cd chatbot_ex
### 2. Install the required dependencies:
You can install the required dependencies using pip:

pip install -r requirements.txt
Make sure you have openai library installed:

pip install openai
### 3. Set up your OpenAI API key:
To use the OpenAI API, you'll need an API key. Follow these steps to set it up:

Go to OpenAI's API key page.
Create a new API key and copy it.
Set the API key as an environment variable. This is required for the script to authenticate with the OpenAI API.
**For Linux/Mac:**
Open a terminal and run:

export OPENAI_API_KEY="your-api-key-here"
If you want to make it permanent, add the above line to your ~/.bashrc or ~/.zshrc file, depending on your shell.

**For Windows**:
Set the environment variable by running the following command in your Command Prompt:


setx OPENAI_API_KEY "your-api-key-here"
### 4. Running the chatbot:
Once you have set up the environment variable, run the script:

python main.py
The chatbot will ask for user input. Type something and the chatbot will respond. To exit the chatbot, type quit, exit, or bye.

### Code Overview
main.py: This file contains the main chatbot logic. It interacts with the OpenAI API to get responses based on user input.
requirements.txt: Contains the list of dependencies needed for the project.
