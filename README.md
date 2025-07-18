AI Meeting Assistant


An AI-powered web application built with Flask that allows users to upload meeting audio files, receive transcriptions, and gain valuable insights through AI analysis. The application is designed to create a searchable, intelligent knowledge base from your meeting content.

Features


Secure File Upload: Drag-and-drop or browse to upload meeting audio files (MP3, WAV, M4A, etc.).

AI-Powered Transcription: Utilizes an AI service to transcribe audio files with high accuracy.

Content Analysis: Generates summaries, action items, key decisions, and discussion topics from your transcripts.

Semantic Search: Search across all your meeting content using natural language to find concepts, not just keywords.

Multi-Language Translation: Translate transcribed content into various supported languages.

Cross-Meeting Insights: Discover recurring themes and patterns across multiple meetings.

Modern UI: A clean, responsive, and intuitive user interface built with Bootstrap.

Tech Stack


Backend: Python, Flask

Frontend: HTML, Bootstrap, JavaScript

Core Libraries: See requirements.txt for a full list of dependencies.

Installation
To set up and run this project locally, follow these steps:

Clone the repository:

git clone https://github.com/natamelikishvili/AI-Assistant.git
cd AI-Assistant

Create and activate a virtual environment:

For Windows
python -m venv venv
venv\Scripts\activate

For macOS/Linux
python3 -m venv venv
source venv/bin/activate

Install the required dependencies:

pip install -r requirements.txt
Set up environment variables:

You will need an API key for the AI services used. Create a .env file in the root directory and add your keys:

OPENAI_API_KEY=your_api_key_here

Usage
Once the setup is complete, you can run the application with a single command:

python app.py
Navigate to http://127.0.0.1:5000 in your web browser to access the application.

Workflow:
Upload: Go to the "Upload" page and add a meeting audio file.

Transcribe: From the meeting details page, start the transcription process.

Analyze: Once transcribed, run the AI analysis to generate a summary, action items, and more.

Search: Use the "Search" feature to find information across all your analyzed meetings.
