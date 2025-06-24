# News-Summarizer
Python + Flask web app that applies NLP techniques (tokenization, stopword removal, sentence scoring) to generate real-time extractive summaries from text or news URLs.
# 📰 News Summarizer

A Python-based web application that automatically generates concise summaries of long news articles using Natural Language Processing (NLP). Built with Flask and front-end technologies, the app allows users to enter either raw text or a news article URL and receive a real-time, readable summary.

## 🚀 Live Demo

Coming soon... (Optional: Add link after deployment)

---

## 🧠 Features

- 🔍 Extractive text summarization using NLP algorithms (e.g., frequency-based or TextRank)
- 📰 Accepts both raw text and article URLs as input
- ⚡ Real-time summary generation
- 💻 Clean, responsive web interface
- 🛠️ Lightweight and fast using Flask

---

## 🛠️ Tech Stack

| Layer       | Technologies Used                       |
|-------------|------------------------------------------|
| Backend     | Python, Flask, NLTK / spaCy, Newspaper3k |
| Frontend    | HTML, CSS, JavaScript                    |
| Libraries   | re, string, BeautifulSoup (if used)      |
| NLP Methods | Tokenization, Stopword Removal, Sentence Scoring |

---

## 📦 Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/news-summarizer.git
cd news-summarizer

# 2. Create virtual environment and activate it
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask app
python app.py
