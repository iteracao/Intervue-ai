# Reviewer Notes - Intervue AI

Intervue AI is a desktop productivity tool.

- It processes system audio output locally
- It does not capture microphone input
- Detection starts only when explicitly triggered by the user
- Users can stop processing at any time
- No hidden background recording or background capture occurs
- OpenAI is used only during active transcription or answer-generation requests
- API keys are stored locally using Windows Credential Manager
- The current packaged app is OpenAI-only and does not include Vosk or Faster-Whisper
