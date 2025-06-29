# 🤖 Gemini Pro ChatBot

A simple Streamlit web application to chat with **Google Gemini-Pro**, a powerful generative AI model. This project demonstrates how to build a conversational interface using Streamlit and the Google Generative AI SDK.

## 🔧 Features

* Interactive chatbot interface with real-time messaging
* Chat history persisted through the session
* Emoji support and custom page settings
* Secure handling of API keys using `.env` files

## 📦 Requirements

* Python 3.7+
* Google Generative AI SDK (`google-generativeai`)
* Streamlit
* python-dotenv

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/SAMUDRAGUPTA002/LLM_projects/tree/6ff5a5751184a96a3b8d71dbe38703cc7b0a8690/Gemini_chatbot
   ```

2. **Create and activate a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your environment variables:**
   Create a `.env` file in the root directory with your Google API key:

   ```
   GOOGLE_API_KEY=your_google_api_key_here
   ```

## 🚀 Usage

To run the chatbot app:

```bash
streamlit run main.py
```

Then open the displayed URL in your web browser.

## 📁 File Structure

```
main.py          # Main Streamlit app
.env             # Contains your API key (excluded from version control)
README.md        # Project documentation
requirements.txt # Python dependencies
```

## 🧠 Powered By

* [Google Generative AI](https://ai.google.dev/)
* [Streamlit](https://streamlit.io/)

## 🛡️ Disclaimer

Ensure your API key is kept secret and never shared publicly. Do not commit your `.env` file to version control.

## 📃 License

This project is licensed under the [MIT License](LICENSE).
