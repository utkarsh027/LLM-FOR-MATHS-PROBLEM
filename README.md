# Text to Math Problem Solver and Data Search Assistant

## Overview
This project is a Streamlit application that uses LangChain and Google Gemma 2 to solve mathematical problems and provide data search assistance. The application combines tools like a Wikipedia search wrapper, a math problem solver, and a reasoning assistant to answer user queries effectively.


## Features

- **Math Problem Solver**: Solve complex math problems step-by-step and provide detailed explanations.
- **Wikipedia Search Tool**: Search and retrieve relevant information from Wikipedia.
- **Reasoning Assistant**: Tackle logic-based and reasoning questions using AI.
- **Interactive Interface**: User-friendly Streamlit app for seamless interaction.

## Requirements

- Python 3.8 or higher.
- A valid Groq API Key.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate
3. **Install Dependencies**:
  ```bash
  pip install -r requirements.txt
```


## Usage
Run the Application:
```bash
streamlit run app.py
```

# Interact with the Application:
- **Enter your Groq API Key in the sidebar**.
- **Input a Question: Here I have already provided one in code**.
- **Click the Find my answer button**.
- **View the result**.
# Key Components
# LangChain Tools:

- **Wikipedia Tool**: Searches and retrieves information from Wikipedia.
- **Math Solver Tool**: Handles mathematical queries and provides step-by-step solutions.
- **Reasoning Tool**: Solves logic-based and reasoning problems.
# Streamlit Interface:

Sidebar for API key input.
- **Chat-style interaction for user queries and responses**.

# Code Structure

- **app.py**            # The main Streamlit application script.
- **requirements.txt**   # Contains all required Python libraries.

# Example Workflow
- **Input a vQuestion**.
- **Provide your Groq API Key**.
- **Click the button to fetch the answer**.
- **Review the answer displayed in the application**.
# Error Handling
Validation:

- **Ensures the Groq API Key and URL inputs are valid**.
- **Displays an error if the URL is invalid or missing**.


