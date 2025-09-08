# Global-News-Aggregator-Chatbot
This project is a Python-based news aggregator chatbot that fetches, processes, and displays news from multiple global sources such as NewsAPI, Google News, Reuters, BBC, Al Jazeera, AP News, and more.
"politics news from Germany"

"technology updates today"

"natural disasters last week"

Key features:

✅ Integrates with NewsAPI (primary source).

✅ Falls back to Google News RSS scraping if API returns fewer results.

✅ Deduplicates news articles and prioritizes based on source credibility.

✅ Supports categories (politics, business, technology, health, science, sports, entertainment, vehicle).

✅ Supports country-based filtering (India, US, UK, Germany, etc.).

✅ Supports date-based queries (today, yesterday, last week, or exact date like 2024-09-01).

✅ Console-based chatbot interface.

This project can be extended to build a Telegram bot, web app, or voice assistant for real-time global news delivery.

🔹 README.md for GitHub
# 🌍 Global News Aggregator Chatbot

A Python-based **news aggregator chatbot** that fetches and displays news from multiple global sources using **NewsAPI, Google News RSS, and fallback news sites**.

---

## ✨ Features
- Fetches **real-time global news** from multiple trusted sources.
- Natural language query support:
  - `politics news from Germany`
  - `technology updates today`
  - `natural disasters last week`
- Supports **categories**: politics, business, technology, sports, health, science, entertainment, vehicle.
- Supports **country-based filtering** (India, US, UK, Germany, etc.).
- Supports **date-based queries** (today, yesterday, last week, or exact dates).
- Deduplicates news results and sorts them by **source credibility**.
- Console-based chatbot interface.

---

## 🚀 How It Works
1. User enters a query like `"business news from India last week"`.
2. The chatbot:
   - Fetches results from **NewsAPI** using your API key.
   - Falls back to **Google News RSS** if needed.
   - Deduplicates and ranks the news results.
3. Displays the top 15 news articles with:
   - Title  
   - Source (with credibility stars ⭐)  
   - Published date  
   - URL  

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/global-news-aggregator-chatbot.git
   cd global-news-aggregator-chatbot


Install dependencies:

pip install requests


Add your NewsAPI Key inside the code:

NEWS_API_KEY = "your_api_key_here"

▶️ Usage

Run the chatbot:

python news_aggregator.py


Example queries:

politics news from Germany
natural disasters last week
technology updates today
business news from India


Type exit to quit.

🔧 Project Structure
├── news_aggregator.py   # Main chatbot code
├── README.md            # Project documentation

📌 Future Improvements

Add Telegram Bot integration.

Build a Flask/Django web app.

Use feedparser for better RSS parsing.

Add voice assistant integration.

Add support for more languages.

📜 License

This project is licensed under the MIT License – free to use and modify.


---
