Chama FAQ Bot

An AI-powered command-line assistant that helps Chama members get quick and reliable answers about Chama rules, meeting schedules, contributions, and fines.

Built with Python and Google Gemini API.

Features

- AI-powered Chama FAQ assistant
- Controlled knowledge base using a system prompt
- Interactive command-line chatbot
- Conversation history for follow-up questions
- English and Swahili support
- Input validation
- API error handling
- Prevents guessing outside the provided Chama information

Technologies

- Python
- Google Gemini API
- Google GenAI SDK
- python-dotenv

Installation

Clone the repository:

git clone <YOUR_REPOSITORY_URL>
cd chama-faq-bot

Install dependencies:

pip install -r requirements.txt

Create a ".env" file:

GEMINI_API_KEY=your_api_key_here

Never commit your API key to GitHub.

Usage

Run the application:

python tool.py

Example:

Member: When is the next meeting?

Assistant: The next Chama meeting will be held at Kakamega Police Camp on 12 June 2027.

Type "exit" to close the application.

Knowledge Base

The assistant is configured to answer questions about:

1. Chama rules
2. Meeting schedules
3. Required contributions
4. Fines and payment deadlines

If information is outside the knowledge base, the assistant directs the member to the chairman instead of guessing.

Testing

The bot was tested with at least eight different question types, including:

- Meeting questions
- Meeting location
- Chama rules
- Contributions
- Membership fees
- Fines
- Payment deadlines
- Swahili questions
- Out-of-scope questions
- Follow-up questions

The application also handles:

- Empty input
- Invalid API requests
- Server errors
- Unexpected errors

Project Structure

chama-faq-bot/
├── tool.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md

Version

v1.0.0 — Initial Release

Author

Newton.
Python Developer | AI & Automation