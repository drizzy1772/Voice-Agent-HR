# Voice-Agent-HR

Voice-Agent-HR is a real-time voice interface that helps automate HR recruitment tasks through natural conversation. The assistant can collect candidate information, answer questions about job vacancies, schedule interviews, and manage the hiring process while maintaining a professional tone.

## Tech Stack

Python 3.13+ - Core programming language
Flask - Web framework for serving the HTML interface
WebSockets - Real-time bidirectional communication
Deepgram API - Speech-to-text (Nova-3) and text-to-speech (Aura-2-Thalia)
OpenAI GPT-4o-mini - Natural language processing and conversation logic
μ-law Audio Encoding - 8kHz audio format for telephony integration


## Setup

Clone the repository

bash   git clone <repository-url>
   cd voice-agent-project/myvoice

Install dependencies

bash   pip install python-dotenv websockets flask

Create .env file

   DEEPGRAM_API_KEY=your_deepgram_api_key_here
   OPENAI_API_KEY=your_openai_api_key_here

Run the server

bash   python main.py

Open the web interface
Navigate to http://localhost:5000 in your browser

## Usage

Click "Connect to Server" to establish WebSocket connection
Click "Start Recording" to begin speaking with the HR assistant
Ask questions about job vacancies or provide your candidate information
The assistant will guide you through the conversation professionally
Click "Stop Recording" when finished

## WARNING
This project is provided as-is for educational and commercial use.
