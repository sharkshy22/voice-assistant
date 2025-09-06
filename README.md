# voice-assistant
Voice Assistant is a Python project that executes tasks via voice commands. It can search the web, tell time, open apps, play music, and more using speech recognition, pyttsx3, and pyaudio. Lightweight, extendable, and beginner-friendly for AI and automation projects.

# 🎙️ Voice Assistant

A Python-based **Voice Assistant** that allows you to control your computer and perform tasks using just your voice.  
It listens to user commands, processes them, and provides natural voice-based responses.

---

## ✨ Features
- 🔊 Convert speech to text and text to speech  
- 🌐 Search the web (Google, Wikipedia, YouTube, etc.)  
- 📅 Tell the current time and date  
- 📂 Open applications and files  
- 📧 Send emails (with configuration)  
- 📝 Take notes and save them  
- 🎶 Play music from your system  
- ⚙️ Easily extendable to add more features  

---

## 🛠️ Tech Stack
- **Language:** Python 3  
- **Libraries Used:**
  - `speechrecognition` – to capture and process speech  
  - `pyttsx3` – for text-to-speech output  
  - `pyaudio` – for microphone access  
  - `wikipedia` – to fetch summaries  
  - `datetime` – to fetch time and date  
  - `os` & `subprocess` – to open apps/files  

---

## 📂 Project Structure

voice-assistant/
│-- assistant.py # Main script
│-- requirements.txt # Dependencies
│-- README.md # Project documentation
│-- config.json # (Optional) Store user configs like email


---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/voice-assistant.git
cd voice-assistant


⚙️ Example Commands

-"What is the time?"

-"Open YouTube"

-"Search Wikipedia for Artificial Intelligence"

-"Play music"

-"Send an email"

📌 Future Improvements

-Integrate with ChatGPT API for smarter conversations

-Add smart home device support (IoT integration)

-Build a simple GUI interface

-Enable multi-language support

🤝 Contributing

Contributions are welcome! If you’d like to improve this project, please fork the repository and submit a pull request.
