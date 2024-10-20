# icecream project

An innovative chatbot device that combines advanced AI capabilities with real-time voice interaction and dynamic visual feedback.

## Overview

This project showcases a cutting-edge chatbot that leverages GPT-4 for natural language processing, integrates voice recognition and synthesis, and incorporates Stable Video Diffusion for generating responsive animations. It's designed to provide an engaging, multi-modal interaction experience.

## Key Features

- AI-driven conversational abilities powered by GPT-4
- Real-time voice input and output using Pipecat and Daily
- Dynamic animation generation using Stable Video Diffusion
- Seamless video conferencing integration via Daily.co
- Persistent conversation logging and retrieval

## Technical Stack

- Backend: Python with FastAPI
- AI Model: custom model
- Real-time Communication: Pipecat and Daily
- Speech Processing: PyAudio
- Video Conferencing: Daily.co API
- Database: Supabase

## Quick Start

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/ai-interactive-chatbot.git
   cd ai-interactive-chatbot
   ```

2. Set up the environment:
   ```
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

3. Configure your environment:
   ```
   cp env.example .env
   # Edit .env with your API keys and configurations
   ```

4. Launch the application:
   ```
   python server.py
   ```

5. Access the chatbot interface at `http://localhost:7860/start`

## Project Structure

- `server.py`: Main application server
- `bot.py`: Core chatbot logic
- `client/`: Client-side scripts
  - `pyaudio-run.py`: Voice interaction handler
  - `notes-run.py`: Conversation logging system
- `requirements.txt`: Python dependencies

## Acknowledgements

- OpenAI for GPT-4
- Daily.co for video conferencing capabilities
- Pipecat for real-time communication
- The open-source community for various libraries and tools used in this project
