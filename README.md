# Voice Assistant

A Python-based voice assistant that uses artificial intelligence to process user queries, perform tasks, and respond intelligently. Inspired by the concept of Jarvis from the Marvel Universe, this assistant integrates AI and voice recognition to create a seamless interactive experience.

---

## Features
- **Voice Command Recognition**: Uses `SpeechRecognition` and Google Speech API for accurate voice command input.
- **AI-Powered Chat**: Leverages OpenAI's `text-davinci-003` model for intelligent and contextual responses.
- **Web Automation**: Opens popular websites like YouTube, Wikipedia, and Google based on user commands.
- **Time Announcement**: Provides the current time upon request.
- **AI Query Processing**: Handles AI-specific prompts for detailed responses.
- **Session Management**: Allows chat reset and exit commands.

---

## Technology Stack
- **Programming Language**: Python
- **Libraries/Modules**:
  - `speech_recognition` - For voice-to-text conversion.
  - `openai` - For AI-powered responses.
  - `webbrowser` - For automating web navigation.
  - `os` - For system commands.
  - `datetime` - For fetching the current time.

---

## Prerequisites
1. Python 3.8 or higher
2. Install the required dependencies:
   ```bash
   pip install speechrecognition openai
