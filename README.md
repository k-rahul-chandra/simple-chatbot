# 🤖 AI Chatbot using Streamlit + LangChain + Groq

A simple AI-powered chatbot built using **Streamlit**, **LangChain**, and **Groq's Llama 3.1 model**.

The chatbot provides a clean chat interface where users can interact with an AI assistant in real time. Chat history is maintained throughout the session, making conversations feel natural and continuous.

---

## 🚀 Features

✅ Clean Streamlit UI

✅ Powered by Groq's Llama 3.1 8B Instant Model

✅ Conversation Memory using Session State

✅ Fast AI Responses

✅ Environment Variable Support for API Security

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Groq API
- Python Dotenv

---

## 📂 Project Structure

```bash
.
├── chatbot.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/chatbot.git
cd chatbot
```

### 2. Create Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory.

```env
GROQ_API_KEY=your_groq_api_key
```

Get your API key from:

https://console.groq.com/keys

---

## ▶️ Running the Application

Start the Streamlit server:

```bash
streamlit run chatbot.py
```

The application will open automatically in your browser.

If not, open:

```bash
http://localhost:8501
```

---

## 📦 Requirements

```txt
streamlit
python-dotenv
langchain-community
langchain-groq
```

---

## 🌐 Live Demo

After deploying on Streamlit Cloud, add your URL below:

```text
LIVE APP URL:
https://your-app-name.streamlit.app
```

---

## 📸 Screenshot

Add screenshots of your chatbot here.

![Chatbot Screenshot](images/chatbot.png)

---

## 📖 How It Works

1. User enters a prompt.
2. Streamlit captures the input.
3. LangChain sends the conversation to Groq.
4. Groq's Llama 3.1 model generates a response.
5. Response is displayed and stored in session history.

---

## 🧑‍💻 Author

Rahul Chandra

B.Tech AIML Student | AI & ML Enthusiast

GitHub: https://github.com/your-github-username

LinkedIn: https://linkedin.com/in/your-linkedin-profile
