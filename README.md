A simple FAQ chatbot answering common questions about Iron Lady’s leadership programs (program details, duration, mode, certification, mentors, etc.). Optionally integrates an AI API for smarter responses.

🛠 Tech Stack

Frontend: HTML, CSS, JavaScript (or React if you upgrade)

Backend (optional): Flask / Node.js (only if using AI API)

AI Integration (bonus): OpenAI API, Rasa, or similar

🚀 Features

Predefined FAQ responses

Search or keyword match for user queries

Optional AI-powered fallback for unlisted questions

Responsive chat UI

git clone <repo-url>
cd task1_chatbot

Run locally

Static version: open index.html in browser

With backend:

# Example if using Flask
pip install flask openai
flask run


Configure API keys if integrating AI (store securely in .env).# task1_faq_chatbot
