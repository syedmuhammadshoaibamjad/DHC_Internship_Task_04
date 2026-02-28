# Task 04: Health Inquiry Chatbot

## Overview
A secure, AI-powered chatbot that provides general health information while following strict safety protocols.

## What I implemented:
- **API Security:** Used `python-dotenv` to hide my Hugging Face Token.
- **Modern SDK:** Integrated `huggingface_hub` to handle the new HF Router infrastructure.
- **Safety Filters:** Added a local Python layer to intercept crisis-related keywords.
- **Prompt Engineering:** Configured Llama-3.2 to always provide medical disclaimers.

## How to Run:
1. Activate the venv: `source venv/bin/activate`
2. Select the venv kernel in VS Code.
3. Run the notebook cells.