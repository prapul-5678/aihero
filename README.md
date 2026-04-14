# AI FAQ Agent
An intelligent AI agent that can answer questions about any GitHub repository documentation using natural language.

## Overview 
Ever wanted to ask about the github repository instead of reading everthing in documentation?
This project does exactly that! It:
- Downloads any GitHub repository
- Indexes all documentation
- Lets you ask questions in plain English
- Gives accurate answers with source references using llm models


Try my live app that answers your doubts about the github repository.
🔗 Live App: https://aihero-d9whq7qkzoxwrqnqugeqqj.streamlit.app/

## Execution 
<img width="1920" height="866" alt="{1CD98C49-9E10-46E4-84CE-4C835DA9F3DE}" src="https://github.com/user-attachments/assets/61f3f8d7-c879-4ce4-9a3b-9a6269cc20fb" />
<img width="1920" height="866" alt="{8B851A16-FF86-4E14-9217-4C51E7B5F7A4}" src="https://github.com/user-attachments/assets/c463bf52-7cb7-467d-acea-ee83fcc90edc" />

## Features
- 📥 Downloads any GitHub repository automatically
- 🔍 Intelligent text search using Minsearch
- 🤖 AI-powered answers using Groq LLM
- 💬 Clean chat interface built with Streamlit
- 📝 Conversation logging for every interaction
- Evaluates the FAQ questions 

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Main language |
| Pydantic AI | AI agent framework |
| Groq | LLM provider (free!) |
| Minsearch | Search engine |
| Streamlit | Web interface |
| GitHub API | Data source |

## Installation

1. Clone the repository:
git clone https://github.com/prapul-5678/aihero.git
cd aihero

2. Install dependencies:
uv sync

3. Set your API key:
export GROQ_API_KEY="your-key-here"

4. Run the app:
uv run streamlit run app.py

## Evaluation

The agent was evaluated on FAQ questions using Groq LLM 
as the evaluator.

Results:
- Accuracy: Good — answers match source material
- Relevance: High — search returns correct documents
- Response Quality: Clear and well formatted

## Project Structure

aihero/
├── app.py           # Streamlit web interface
├── ingest.py        # Data pipeline
├── search_tools.py  # Search functionality
├── search_agent.py  # AI agent setup
├── logs.py          # Conversation logging
├── main.py          # CLI interface
└── requirements.txt # Dependencies

## Credits

- Course by Alexey Grigorev
- https://alexeygrigorev.com/aihero/
- Built with Pydantic AI, Groq, Streamlit

## instructions to push into github 

- cd "$env:USERPROFILE\aihero\app"
- notepad README.md
- git add README.md
- git commit -m "added README"
- git push origin main
