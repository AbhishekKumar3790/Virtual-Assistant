# Virtual-Assistant
 # Project Title: Allina – AI-Based Voice Assistant with GUI (PyQt5)

## Description

**Allina** is an intelligent voice-controlled desktop assistant developed using Python and enhanced with a PyQt5 GUI for interactive user experience. It leverages SpeechRecognition for capturing voice commands and pyttsx3 for spoken responses. The assistant performs tasks like opening applications, browsing the internet, sending emails, playing music, fetching IP addresses, and telling jokes. Key technologies include PyQt5, SMTP, pywhatkit, Wikipedia API, and requests, making it a multifunctional, AI-driven automation tool with both voice and graphical interface support.

This assistant combines Artificial Intelligence features like speech recognition, text-to-speech, and natural language processing with a user-friendly GUI for seamless interaction. The PyQt5 interface offers buttons, menus, and status displays to make the assistant more intuitive and accessible for users who prefer or require a visual interface.

## Core Features

- Voice Command Recognition (SpeechRecognition)
- Text-to-Speech Responses (pyttsx3)
- GUI with PyQt5: Start/Stop listening, visual feedback, log display
- Wikipedia summaries on voice query
- Email sending via SMTP
- Music playback and YouTube integration
- WhatsApp messaging automation
- Open web apps: Google, YouTube, GitHub, etc.
- Public IP address detection
- Joke generation (pyjokes)
- Smart greetings based on time
- System-level commands: shutdown, restart, open apps

## GUI Features with PyQt5

- Start/stop listening toggle
- Display recognized text and system responses
- Voice activity status (LED-style indicators or labels)
- Visual logs of actions taken
- Menu bar for quick-access commands (e.g., open browser, email, music)

## Technologies Used

- Python 3
- PyQt5 – GUI Framework
- SpeechRecognition – Voice input
- pyttsx3 – Text-to-Speech
- Wikipedia API
- pywhatkit – YouTube & WhatsApp automation
- smtplib – Email sending
- pyjokes – Joke generation
- requests – IP detection
- Standard Libraries: webbrowser, os, datetime, subprocess

### Setup and Installation

#### Step 1: Install Python

Make sure Python 3.7+ is installed on your system. You can download and install it from [python.org](https://www.python.org/downloads/).

#### Step 2: Install Dependencies

After cloning or downloading the repository, you need to install the required dependencies.
 
## Installation Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/AbhishekKumar3790/Virtual-Assistant.git
   cd virtual_ai.py
  ``
##### Create a Virtual Environment (Optional but Recommended)

- **Windows**:
  ```bash
  python -m venv virtual_ai_env
  .\virtual_ai_env\Scripts\activate

 2. Install Required Packages
   - pip install -r requirements.txt
   - pip install pipwin
   - pipwin install pyaudio
   - pip install pyttsx3 speechrecognition requests wikipedia pywhatkit pyjokes opencv-python

3. Configuration (Optional for Gmail Email)
   - For email functionality using Gmail:
   - Ensure you have 2-step verification enabled in your Gmail account.
   - Create an App Password and replace it in the sendEmail function with your app-specific password (for security).
     
4. Running the Assistant
   - python virtual_ai.py
  
   ### Dependencies
  Below are the required Python packages:
- PyQt5==5.15.9
- SpeechRecognition==3.10.0
- pyttsx3==2.90
- pywhatkit==5.4
- wikipedia==1.4.0
- pyjokes==0.6.0
- requests==2.31.0
- pyaudio==0.2.13
- datetime
- os
- random
- requests
- webbrowser
- smtplib (standard library)
- sys (standard library)
- opencv-python

