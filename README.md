# 🤖 AI Research Chatbot

The **AI Research Chatbot** is a Python-based project that helps users quickly gather and summarize research information from Wikipedia using Natural Language Processing (NLP) and Hugging Face Transformers. It automates research assistance by fetching relevant content and generating concise summaries — no API keys required.

---

## 📘 Features

* Fetches research summaries directly from **Wikipedia REST API**.
* Automatically simplifies and summarizes text using **Hugging Face Transformers**.
* Works offline once dependencies are installed (except for Wikipedia requests).
* User-friendly CLI (Command Line Interface).
* Easily extendable for API or web integration (Flask/FastAPI).

---

## 🧠 Technologies Used

* **Python 3.x**
* **Hugging Face Transformers (BART model)**
* **Requests** (for Wikipedia API)
* **NLP** (for text summarization)

---

## ⚙️ Installation

1. **Clone this repository:**

   ```bash
   git clone https://github.com/nitisha-lgtm/ai-research-chatbot.git
   cd ai-research-chatbot
   ```

2. **Install dependencies:**

   ```bash
   pip install transformers requests torch
   ```

3. **Run the chatbot:**

   ```bash
   python research_bot.py
   ```

---

## 🚀 How It Works

1. User enters a research topic (e.g., *Artificial Intelligence*).
2. The chatbot fetches a brief Wikipedia summary using the REST API.
3. The text is summarized using the **BART large CNN model** from Hugging Face.
4. Both original and simplified summaries are displayed in the terminal.

---

## 🧩 Example Output

```
Enter your research topic: Artificial intelligence

📘 Original Wikipedia Summary:
Artificial intelligence (AI) is intelligence demonstrated by machines, unlike the natural intelligence displayed by humans...

⏳ Generating simplified summary...

✅ Simplified Summary:
AI refers to the capability of machines to perform tasks that typically require human intelligence such as reasoning, learning, and problem-solving.
```

---

## 🧾 File Structure

```
ai-research-chatbot/
│
├── research_bot.py       # Main chatbot script
├── README.md             # Project documentation
└── requirements.txt      # Dependencies list
```

---

## 🧠 Future Improvements

* Add **Flask/FastAPI** integration for web interface.
* Enable multi-source data fetching (e.g., arXiv, ResearchGate).
* Implement keyword extraction and topic clustering.

---


---

## 🪪 License

This project is open-source and available under the **MIT License**.
