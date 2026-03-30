# Intervue AI

Intervue AI is a Windows desktop assistant that processes live conversations, detects questions, and suggests concise AI-powered answers in real time.

Built with .NET 8 and WPF, it captures system audio, performs real-time transcription, applies heuristic question detection, and generates context-aware responses using AI.

## 🚀 Features

- Real-time system audio processing
- Live transcription (OpenAI, Vosk, Faster-Whisper)
- Automatic question detection (EN/PT)
- Context-aware AI answers
- Local-first desktop architecture
- Secure credential storage (Windows Credential Manager)

## 🧱 Architecture

- **Desktop (WPF)** – UI and interaction  
- **Core** – orchestration, detection, domain logic  
- **Infrastructure** – audio capture, providers, integrations  

## ⚙️ Requirements

- Windows 10 / 11  
- Audio output device  
- OpenAI API key (for cloud features)  
- Optional local models for offline transcription  

## 🔐 Privacy

Intervue AI operates locally and does not perform hidden recording or background data collection.

The application runs only when explicitly started and does not capture audio in the background.

👉 Privacy policy: https://iteracao.github.io/Intervue-ai/privacy/

## 🏢 Publisher

ITERAÇÃO - SISTEMAS E SOLUÇÕES INFORMÁTICAS, LDA

## 📄 License

MIT License
