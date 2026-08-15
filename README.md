AI Voice Assistant
A beginner-friendly AI Voice Assistant built with Python and Streamlit.

The application can:

Record a spoken question
Convert speech into text
Generate an AI response
Convert the response back into speech
Play the spoken answer inside the application
This project is part of the AI Projects Series on Karthik's Show.

How It Works
Voice Input
   ↓
Speech-to-Text with Whisper
   ↓
AI Response with Groq LLM
   ↓
Text-to-Speech with gTTS
   ↓
Spoken Answer
Technologies Used
Python
Streamlit — application interface and microphone input
Groq Whisper — speech-to-text
Groq LLM — AI response generation
gTTS — text-to-speech
GitHub Copilot — code review and software-testing suggestions
Project Structure
ai-voice-assistant/
│
├── app.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
Installation
1. Clone the repository
git clone https://github.com/KarthiksShow/ai-voice-assistant
cd ai-voice-assistant
2. Create a virtual environment
python -m venv venv
Activate it on Windows:

venv\Scripts\activate
Activate it on macOS or Linux:

source venv/bin/activate
3. Install the dependencies
pip install -r requirements.txt
Environment Variable
Create a .env file in the project folder:

GROQ_API_KEY=your_groq_api_key_here
Do not upload the .env file to GitHub.

Add this to .gitignore:

.env
venv/
__pycache__/
Run the Application
streamlit run app.py
Allow microphone access when prompted by the browser.
