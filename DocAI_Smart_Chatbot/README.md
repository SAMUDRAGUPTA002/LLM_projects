# 🤖 SHIV-AI: The Intelligent Document & Web Assistant

"Indian-AI Where wisdom meets future innovations 🇮🇳"

SHIV-AI is an advanced, conversational AI assistant built using Python, Flask, and LangChain. It leverages the power of Large Language Models to provide insightful answers from both user-uploaded documents and real-time internet searches.

---

## ✨ Features
- **Dual Knowledge Base**: Answers questions from both uploaded documents (PDF, TXT, CSV) and real-time web searches.  
- **Dynamic Document Management**:  
  - Upload multiple documents  
  - Add/remove files during a chat session  
- **Rich UI**:  
  - Futuristic theme with glowing effects  
  - Light & Dark mode toggle  
  - Persistent chat history (saved in sidebar with localStorage)  
  - Session management (start new chat / delete chats)  
- **Voice Interaction**:  
  - Voice input (Speech-to-Text)  
  - Voice output (Text-to-Speech)  
- **User Tools**:  
  - Feedback buttons (👍 / 👎)  
  - Active file display  

---

## 🛠️ Tech Stack
- **Backend**: Python, Flask  
- **AI Framework**: LangChain  
- **LLM**: Google Gemini (`gemini-1.5-flash-latest`)  
- **Embeddings**: Google AI Embeddings (`models/embedding-001`)  
- **Frontend**: HTML, Tailwind CSS, JavaScript (Web Speech API)  
- **Vector Store**: FAISS (in-memory)  
- **Web Search**: Tavily AI  

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/SAMUDRAGUPTA002/LLM_projects.git
cd LLM_projects/DocAI_Smart_Chatbot
````

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate it:

* **Windows (PowerShell)**:

```bash
.\venv\Scripts\Activate.ps1
```

* **Mac/Linux**:

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Setup Environment Variables

Create a `.env` file in project root:

```bash
GOOGLE_API_KEY="your-google-api-key-here"
TAVILY_API_KEY="your-tavily-api-key-here"
```

### 5. Run the Application

```bash
python app.py
```

Now open in browser:
👉 [http://127.0.0.1:5000]

---

## 📁 File Structure

```
LLM_projects/
└── DocAI_Smart_Chatbot/
    ├── app.py
    ├── requirements.txt
    ├── templates/
    ├── static/
    ├── .env
    └── README.md
```

---

## 🔗 Project Link

[Doc\_AI\_smart\_assistant\_chatbot](https://github.com/SAMUDRAGUPTA002/LLM_projects/tree/main/DocAI_Smart_Chatbot)

---

## 🧠 Powered By

* Google Gemini
* LangChain
* Flask
* FAISS
* Tavily AI

---

## 📃 License

This project is licensed under the MIT License.
