# 🤖 Groq LLM Streamlit Chatbot

An interactive and powerful **AI chatbot with UI**, built using [Groq API](https://console.groq.com/) and the **LLaMA 3.3–70B Versatile model**. This Streamlit project allows users to have real-time, intelligent conversations with a large language model through a modern and user-friendly web interface.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://choudary-ai.streamlit.app)

---

## 📌 Features

* ⚡ Powered by `llama-3.3-70b-versatile` from Groq
* 💬 Beautiful Streamlit-based UI chat interface
* 🧠 Optional context-aware assistant replies (memory on/off)
* 💾 Downloadable chat history in `.txt` format
* 🎨 Custom CSS for enhanced UI and centered sidebar image
* 🔐 Secure API key handling via `.env`

---


## 📸 Screenshots

![Screenshot (31)](https://github.com/user-attachments/assets/cc92dfe1-0edf-4a22-b2b5-d79334f18192)

![Screenshot (32)](https://github.com/user-attachments/assets/2fa19a28-e115-4bb3-bf00-e3fa92c02d08)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/reth0608/nlp_project/
cd groq-streamlit-chatbot
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Set up your `.env` file

Create a `.env` file in the root directory and add your [Groq API key](https://console.groq.com/):

```
GROQ_API_KEY=your_groq_api_key_here
```

### 4. Run the chatbot

```bash
streamlit run app.py
```

---

## 💾 Project Structure

```
groq-streamlit-chatbot/
│
├── app.py              # Main Streamlit chatbot application
├── .env                # API key (excluded from version control)
├── README.md           # Project documentation
└── requirements.txt    # List of Python dependencies
```

---

## 🧠 Example Conversation

```
💬 Type your message: Hello! What can you do?

🤖 Assistant: Hi there! I’m an AI assistant powered by the LLaMA 3.3 model. I can help answer questions, explain topics, and chat with you in natural language!

💬 Type your message: Tell me a joke.

🤖 Assistant: Why did the computer show up at work late? Because it had a hard drive! 😄
```

---

## 📄 License

This project is proprietary and confidential. All rights reserved.

```
© 2025 HUSSAIN ALI. This code may not be copied, modified, distributed, or used without explicit permission.
```

---

## 📬 Contact

For questions or collaboration requests:

* 📧 Email: [choudaryhussainali@outlook.com](mailto:choudaryhussainali@outlook.com)
* 🌐 GitHub: [choudaryhussainali](https://github.com/choudaryhussainali)

---

> ✨ Built using [Groq](https://groq.com), [Streamlit](https://streamlit.io/), and the blazing-fast LLaMA 3.3 models
