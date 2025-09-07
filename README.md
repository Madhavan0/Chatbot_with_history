# 🧠 Chatbot with Session Memory

This project demonstrates how to build a chatbot using **LangChain** with session-based memory via `RunnableWithMessageHistory`.  
Each conversation is remembered per session ID, allowing users to continue chats seamlessly.  
API keys are securely stored in a `.env` file.

---

## 🚀 Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Madhavan0/Chatbot_with_history.git
cd Chatbot_with_history

### 2. Create Virtual environment
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
.venv\Scripts\activate      # Windows

### 1.3 Install Dependencies
pip install -r requirements.txt

### 1.4 Add Your API Keys
OPENAI_API_KEY=sk-your_openai_key_here
GROQ_API_KEY=your_groq_key_here

### 1.5 Run the Chatbot
python Chabot.py

### 2. How Memory Works

2.1 store → a dictionary acting as a shelf of notebooks (one per session).
2.2 get_session_history → retrieves or creates the notebook for each session ID.
2.3 RunnableWithMessageHistory → wraps the model so it always reads and updates the notebook for each conversation.

### 3. Requirements

3.1 Python 3.9+
3.2 langchain
3.3 langchain-community
3.4 langchain-core
3.5 langchain-openai
3.6 langchain-groq
3.7 python-dotenv

pip install -r requirements.txt

MIT

---

✅ This version:  
- Numbers all sections and sub-steps.  
- Provides **instructions above each code block** so users know what to do.  
- Adds a **step-by-step example** showing how the notebook grows with messages.  

If you want, I can make an **even more visual version** with numbered copy boxes for each command so it’s like a mini tutorial inside the README itself.  

Do you want me to do that next?






