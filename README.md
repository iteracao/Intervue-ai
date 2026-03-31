# Intervue AI

Real-time desktop AI assistant for live technical conversations.

Intervue AI is a Windows desktop application that captures system audio output, transcribes speech in real time, detects likely questions, and suggests concise AI-powered answers.

Built with .NET 8 and WPF, the current packaged app uses OpenAI for transcription and answer generation. Question detection and session orchestration run locally on the device.

---

## Features

- Real-time system audio processing
- Live transcription
- Automatic question detection
- Context-aware AI answers
- Secure credential storage with Windows Credential Manager
- Desktop-first workflow

---

## How it works

1. Captures system audio output in real time
2. Segments audio into speech chunks using silence detection
3. Transcribes speech with OpenAI
4. Detects likely questions from transcript text
5. Builds a compact contextual prompt
6. Generates a concise AI-powered answer
7. Displays results in the desktop UI

---

## Requirements

- Windows 10 / 11
- Audio output device
- Internet connection for OpenAI features
- OpenAI API key

---

## What the app does not do

- It does not capture microphone input
- It does not run hidden background recording when detection is stopped
- It does not include Vosk or Faster-Whisper in the current packaged app

---

## Privacy

Intervue AI runs locally and does not perform hidden telemetry or background capture.

Audio and text may be sent to OpenAI only during active transcription and answer-generation requests started by the user.

Privacy policy: https://iteracao.github.io/Intervue-ai/privacy.html
Support site: https://iteracao.github.io/Intervue-ai/

---

## Publisher

ITERACAO - SISTEMAS E SOLUCOES INFORMATICAS, LDA

---

## License

MIT License
