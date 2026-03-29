# Gemini Chatbot using LangChain

## 📝 Project Summary
This project is a simple AI chatbot built using LangChain, Google Gemini API, and Streamlit. It allows users to ask questions and receive real-time AI-generated responses.

## 🔍 What it does
- Loads API key securely using `.env`
- Uses Gemini model (`gemini-3-flash-preview`) for generating responses
- Formats user input using prompt templates
- Processes input through LangChain pipeline
- Displays output using Streamlit UI

## ⚙️ Tech Stack
- LangChain
- Google Gemini API
- Streamlit
- Python

## 🔄 Workflow
User Input → Prompt Template → Gemini Model → Output Parser → Response

## 🚀 How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
