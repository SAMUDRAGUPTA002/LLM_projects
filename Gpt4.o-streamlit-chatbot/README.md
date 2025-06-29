
# 💬 GPT-4o ChatBot

This is a simple chatbot web app built with [Streamlit](https://streamlit.io/) that interfaces with OpenAI's GPT-4o model to simulate a conversational assistant. Users can interact with the model directly through a clean, browser-based interface.

## 🚀 Features

* 🤖 Real-time conversation with GPT-4o
* 💾 Chat history stored during the session
* 🎨 Custom Streamlit page configuration
* 🔐 Secure API key configuration via `config.json`

## 📁 Project Structure

```
.
├── main.py            # Streamlit app entry point
└── config.json        # Contains OpenAI API key (not included)
```

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/SAMUDRAGUPTA002/gpt4o-chatbot.git
```

### 2. Install Dependencies

Ensure you have Python 3.7+ and install required libraries:

```bash
pip install -r requirements.txt
```

**`requirements.txt` (if not included yet):**

```
streamlit
openai
```

### 3. Add OpenAI API Key

Create a `config.json` file in the root directory with the following format:

```json
{
  "OPENAI_API_KEY": "your-openai-api-key-here"
}
```

> 🔒 Do **not** share this file publicly as it contains your secret API key.

### 4. Run the App

```bash
streamlit run main.py
```

The app will launch in your default web browser.

## 🧠 Powered By

* [Streamlit](https://streamlit.io/)
* [OpenAI GPT-4o API](https://platform.openai.com/docs)

## 📜 License

This project is licensed under the MIT License.

