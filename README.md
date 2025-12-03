# Cheeta Voice Assistant 🐆 | Tamil + English Offline Smart Assistant**

Cheeta is a bilingual (Tamil + English) desktop voice assistant designed to provide real-time, natural voice interaction with a futuristic JARVIS-style experience.
It supports offline wake-word activation, Tamil music playback, smart command execution, and a modern animated GUI.

This project focuses on low-latency voice response, user-friendly control, and expandable modular design, making Cheeta a powerful personal assistant for everyday desktop use.

## ✨ Key Features
 
 Offline Wake-Word Detection (“Hey Cheeta”)

* Powered by Porcupine wake-word engine
* Detects the trigger word without internet
* Low CPU usage and fast activation

🗣️ Tamil + English Bilingual Voice Interaction

* Understands and responds in both languages
* Auto-detects which language the user speaks
* Clear and natural female voice

🎶 Tamil Music Player

* Plays Tamil songs from local folders
* “Play Tamil song” or “Play A.R. Rahman song” commands
* Pause/Stop/Resume controls

 🖥️ JARVIS-Style GUI

* Built using Tkinter + animations
* Displays listening, processing, and speaking states

⚙️ Smart System Commands

* Opens YouTube, Google, Gmail, WhatsApp Web
* Weather updates for Chennai by default
* Tells time/date
* System audio control

🧩 Modular Python Architecture

* `main.py` – Main assistant loop
* `wake_word.py` – Wake-word listener
* `voice_engine.py` – Bilingual TTS
* `music_player.py` – Tamil music player
* `gui.py` – Visual interface
* `assets/` – Animations + wake-word model

💡 Project Ideology

The goal behind Cheeta is to create a fast, offline, practical voice assistant tailored for Indian users—especially Tamil speakers.
Most assistants depend heavily on cloud services, causing delay, lag, and privacy issues.

Cheeta was designed with the following ideology:

* Be fully functional even without internet
* Speak the user’s language (Tamil + English) naturally
* Respond instantly like JARVIS
* Make the assistant useful for daily tasks
* Let anyone expand it because of clean modular code

Cheeta is not just a project—but a foundation for a more advanced personal AI system.

📂 Project Structure

```
Cheeta_Voice_Assistant/
│── main.py
│── wake_word.py
│── voice_engine.py
│── music_player.py
│── gui.py
│── requirements.txt
│── README.md
│
└── assets/
     ├── cheeta_windows.ppn
     ├── animation.gif / animation.png
     └── icons/
```

🚀 Installation

1. Extract the ZIP file

Place it anywhere on your computer.

2. Open PowerShell in project folder

```
cd path/to/Cheeta_Voice_Assistant
```

3. Create virtual environment

```
python -m venv venv
```

4. Activate it

```
venv\Scripts\activate
```

5. Install dependencies

```
pip install -r requirements.txt
```

6. Add wake-word model

Place your `.ppn` file inside:

```
assets/
```

---

#▶️ Usage

Run the assistant:

```
python main.py
```

Then say:

* “Hey Cheeta”
* “Play Tamil song”
* “What’s the weather in Chennai?”
* “Open YouTube”
* “Cheeta, time”

Cheeta will listen, understand, and respond instantly.

---

🛠️ Technologies Used

* Python
* Porcupine Wake-Word Engine
* PyAudio
* Pyttsx3
* Tkinter
* Pillow
* VLC / Pygame for music

---
🌱 Future Enhancements

* Online NLP engine (ChatGPT integration)
* Improved Tamil speech recognition
* On-screen voice waveform animation
* Chrome and Windows automation
* Customizable user profile system

📄 License

This project is created for educational and personal innovation purposes.
You may modify or extend it freely.


📢 Author

Created by Gowtham @https://github.com/Gowthamct
Aiming to build a fast, intelligent, and user-friendly desktop AI assistant.
