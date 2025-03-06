# Gemini-Pro Chatbot

Welcome to the **Gemini-Pro Chatbot**, an interactive AI assistant powered by Google's Gemini-Pro model and built using Streamlit. This chatbot enables real-time conversations with AI, making it a great tool for productivity, research, and entertainment.

## 🚀 Features

- **Conversational AI**: Engage with Google's Gemini-Pro model in real-time.
- **Streamlit Integration**: Simple and interactive UI with chat functionality.
- **Session Management**: Maintains chat history during the session.
- **Environment Configuration**: Uses `dotenv` to load API keys securely.

## 📌 Tech Stack

- **Python**
- **Streamlit**
- **Google Generative AI (Gemini-Pro API)**
- **dotenv** (for environment variable management)

## 🔧 Installation & Setup

1. **Clone the Repository**
2. **Create and Activate Virtual Environment**
3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Set Up API Key**
   - Create a `.env` file in the project directory and add:
     ```plaintext
     GOOGLE_API_KEY=your_google_api_key_here
     ```
   - Replace `your_google_api_key_here` with your actual Google Gemini API key.

5. **Run the Application**
   ```bash
   streamlit run app.py
   ```
