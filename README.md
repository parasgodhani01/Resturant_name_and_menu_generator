# Resturant_name_generator
This project uses LangChain and OpenAI's GPT to generate creative restaurant names and corresponding menu items based on the selected cuisine. The app is built with Streamlit for an interactive user interface.

Features
Cuisine Selection: Choose from a variety of cuisines (Indian, Italian, Mexican, Arabic, American).
AI-Powered Name Generation: Generate unique and fancy restaurant names using OpenAI's language model.
Menu Creation: Get a list of suggested menu items tailored to the restaurant name.

## Project Structure
restaurant-name-generator/
│
├── main.py               # Streamlit app to interact with the user
├── langchain_helper.py   # Contains LangChain logic for name and menu generation
├── secret_key.py         # Stores API keys (DO NOT share this publicly)
└── requirements.txt      # Required Python libraries
