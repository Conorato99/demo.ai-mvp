# demo.ai-mvp
Demo.AI # Demo.ai MVP

Welcome to **Demo.ai**, an AI-powered platform that crafts lively, custom product demos, partnering with or replacing Sales Engineers to deliver engaging, scalable experiences for B2B and B2C software companies in a bold, future-ready world.

This repository contains the Minimum Viable Product (MVP) for Demo.ai, built to showcase AI-driven product demonstrations with basic Q&A and analytics.

## 🚀 Features
- **AI-Driven Demos**: Generates scripted product demos from user-uploaded product details.
- **Interactive Q&A**: Prospects can ask questions (e.g., "Does it integrate with Slack?") via a web interface, powered by a lightweight NLP model.
- **User Dashboard**: Simple interface for companies to input product features and FAQs.
- **Basic Analytics**: Tracks prospect engagement (e.g., questions asked, session time).
- **Scalable Design**: Cloud-ready for handling multiple demo sessions.

## 🛠️ Tech Stack
- **Frontend**: React.js for a responsive demo interface.
- **Backend**: FastAPI (Python) for API and AI integration.
- **AI**: Hugging Face Transformers (DistilBERT) for Q&A (or xAI’s Grok API, see [xAI API](https://x.ai/api)).
- **Database**: SQLite for storing product details and demo scripts.
- **Hosting**: GitHub Pages (frontend), Heroku/AWS (backend, optional).

## 📦 Installation
### Prerequisites
- Node.js (v16+)
- Python (3.8+)
- Git
- Hugging Face Transformers (`pip install transformers`)
- Optional: Heroku CLI for backend deployment

### Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Demo.ai-MVP.git
   cd Demo.ai-MVP
