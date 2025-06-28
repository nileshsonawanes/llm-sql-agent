# llm-sql-agent


# 🧠💬 SQL Chatbot using LangChain, Groq & Streamlit

A conversational chatbot that allows users to query their SQL databases (SQLite or MySQL) using natural language. Powered by [LangChain](https://www.langchain.com/), [Groq LLMs](https://console.groq.com/), and [Streamlit](https://streamlit.io/).

---

## 🚀 Features

- 🔌 Connect to **SQLite** or **MySQL** databases
- 🤖 Ask questions in **natural language**
- ⚡️ Powered by **Groq LLMs** (e.g., `Llama3-8b-8192`)
- 🧱 Built with **LangChain SQL Agent Toolkit**
- 🖥️ Simple and clean **Streamlit interface**
- 🔐 User can enter their **API key at runtime**

---

## 📦 Requirements

- Python 3.9+
- Groq API key ([get it here](https://console.groq.com/))
- SQLite `.db` file or MySQL database credentials

---

## 🛠️ Installation

```bash
# Clone the repo
git clone https://github.com/nileshsonawanes/llm-sql-agent
cd sql-chatbot

# Create a virtual environment
python -m venv myenv
# Activate it
.\myenv\Scripts\activate        # For Windows
# source myenv/bin/activate     # For Mac/Linux

# Install dependencies
pip install -r requirements.txt

🔑 Set Up
Make sure you have your Groq API Key ready.

You can either:

Paste it directly into the Streamlit sidebar input, or

Set it as an environment variable before running:

# Windows
set GROQ_API_KEY=your-key-here

# Mac/Linux
export GROQ_API_KEY=your-key-here

🧪 Run the App
streamlit run app.py
