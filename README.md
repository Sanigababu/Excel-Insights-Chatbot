# 📊 Excel Chat Assistant

A Streamlit-based conversational assistant to extract insights from Excel files using natural language and open-source LLMs (Groq + LLaMA 3).

---

## 🚀 Features
- 📁 Upload Excel (.xlsx) files
- 🤖 Ask questions in plain English
- 📊 Get text, tables, or charts as answers
- 🧠 Uses LLM (LLaMA 3 via Groq API)
- 🧹 Cleans messy column names
- 🔍 Schema-agnostic: no hardcoded logic

---

## 📸 Demo
![Streamlit APP link](https://excel-insights-chatbot-qlyshw6k9kkf7rwidnaswc.streamlit.app/)
![Screenshot 2025-06-09 031518](https://github.com/user-attachments/assets/1e7dc33d-9279-4816-b251-7880184e3efd)
![Screenshot 2025-06-09 031550](https://github.com/user-attachments/assets/1f539113-5e1f-4145-86ac-d9a9df6d968e)


---

## 🔧 Tech Stack

- Streamlit
- Pandas
- Groq API (LLaMA 3)
- Python
- Matplotlib & Seaborn

---

## 📂 How to Run Locally

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/excel-chat-assistant.git
cd excel-chat-assistant
```
2. **Install dependencies:**

```bash

pip install -r requirements.txt
```

3. **Add your .env:**

```env

# Create a .env file
GROQ_API_KEY=your-api-key-here
```
4.**Run the app:**

```bash

streamlit run app.py
```

