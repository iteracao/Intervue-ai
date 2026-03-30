# Intervue AI

Real-time desktop AI assistant for live conversations.

Intervue AI is a Windows desktop application that processes live conversations, detects questions, and suggests concise AI-powered answers in real time.

Built with .NET 8 and WPF, it captures system audio, performs real-time transcription, applies heuristic question detection, and generates context-aware responses using AI.

---

## 🚀 Features

- Real-time system audio processing  
- Live transcription (OpenAI, Vosk, Faster-Whisper)  
- Automatic question detection (EN/PT)  
- Context-aware AI answers  
- Local-first desktop architecture  
- Secure credential storage (Windows Credential Manager)  

---

## 🧱 Architecture

- **Desktop (WPF)** – UI and interaction  
- **Core** – orchestration, detection, domain logic  
- **Infrastructure** – audio capture, providers, integrations  

---

## 🧪 How it works

1. Captures system audio output in real time  
2. Segments audio into speech chunks using silence detection  
3. Transcribes speech using the selected provider  
4. Detects likely questions from the transcript  
5. Builds a compact contextual prompt  
6. Generates a concise AI-powered answer  
7. Displays results instantly in the UI  

---

## ⚙️ Requirements

- Windows 10 / 11  
- Audio output device (speakers/headphones)  
- OpenAI API key (for AI-powered features)  

Optional:
- Vosk model (offline transcription)  
- Faster-Whisper executable and model (local transcription)  

---

## 🔐 Privacy

Intervue AI operates locally and does not perform hidden recording or background data collection.

The application runs only when explicitly started and does not capture audio in the background.

Audio and text are only sent to external AI services when explicitly configured by the user.

👉 Privacy policy: https://iteracao.github.io/Intervue-ai/privacy.html

---

## 🏢 Publisher

ITERAÇÃO - SISTEMAS E SOLUÇÕES INFORMÁTICAS, LDA

---

## 📄 License

MIT License
