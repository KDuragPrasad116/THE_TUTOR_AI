# The Conquerors - AI-Powered Productivity Platform

## Project Overview
The Conquerors is an AI-driven platform designed to enhance productivity through structured daily schedules, interactive AI chat, an advanced login system, and a sleep detection alarm. This project integrates multiple technologies, including AI models, animations, and interactive web elements.

## Features
### 1. AI Chatbot
- Built using Flask (`app.py`) and the Ollama AI model (Llama 2).
- Accepts user input and generates AI-powered responses.
- Hosted on a local server at port `5000`.
- Uses `fetch` in `script.js` to communicate with the backend.

### 2. Futuristic Login Page
- Designed with cyberpunk aesthetics.
- Features dynamic animations and an interactive UI.
- Uses `login.html`, `login.css`, and a background video (`background.mp4`).
- Includes a validation script for login authentication.

### 3. Book Collection Page
- Displays a collection of books with descriptions.
- Styled using `books.css`.
- Dynamically presents books with interactive hover effects.

### 4. Sleep Detection Alarm
- Detects user drowsiness using the TensorFlow.js FaceMesh model.
- Triggers an alarm (`alarm.mp3.mpeg`) when eyes remain closed for more than 10 seconds.
- Reads a daily schedule (`example.txt`) aloud when the user wakes up.
- Implemented in `alarm.html` with Web Speech API for voice interaction.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript (Locomotive Scroll, Swiper.js, Ionicons)
- **Backend:** Flask (Python), Ollama AI
- **AI & ML:** TensorFlow.js, FaceMesh model
- **Audio & Video:** Web Speech API, HTML5 Video & Audio

## Installation & Setup
### 1. Run AI Chatbot
```sh
pip install flask ollama
python app.py
```
Access at `http://localhost:5000/chat`.

### 2. Serve the Website
Use a local server (e.g., Live Server in VS Code) to open `login.html`.{email:abc@123, Password:123}

### 3. Run Sleep Detection Alarm
Open `alarm.html` in a browser with webcam permissions enabled.

## File Structure
```
├── app.py             # Backend API for AI chatbot
├── books.html         # Book collection page
├── books.css          # Styling for books page
├── login.html         # Login page
├── login.css          # Login page styles
├── index.html         # Main website page
├── script.js          # JavaScript for animations & AI chatbot
├── alarm.html         # Sleep detection alarm
├── example.txt        # Daily schedule text file
├── background.mp4     # Animated background video for login page
├── alarm.mp3.mpeg     # Alarm sound
├── icon.png           # Favicon/icon for the site
├── NeueHaasDisplay*.ttf  # Custom fonts
├── styles.css          # CSS file for designing main page
├── vedio.mp4          # Vedio to be played on the main page 
└── README.md          # Documentation
```

## Future Enhancements
- **Gesture & Voice Interaction:** Implement full AI assistant capabilities.
- **User Authentication System:** Connect login with a database.
- **Personalized AI Assistant:** Enhance chatbot with memory and learning capabilities.

## Credits
- AI Chatbot powered by **Ollama AI**.
- Sleep detection implemented using **TensorFlow.js**.
- UI animations & design inspired by **Cyberpunk aesthetics**.

---
Developed by [K Durga Prasad].{https://github.com/KDuragPrasad116} 🚀
Developed by [Arun G].{https://github.com/wolf6905} 🚀
