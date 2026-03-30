# Data Usage - Intervue AI

## Data processed by feature

### Real-time audio capture
- Input: system audio output
- Purpose: transcription
- Storage: in memory during processing
- Sent externally: only if the selected provider requires it

### Transcription
- Input: audio chunks
- Purpose: speech-to-text conversion
- Storage: temporary or in-memory depending on provider and settings
- Sent externally:
  - OpenAI: yes
  - Vosk: no
  - Faster-Whisper: no, if run locally

### Question detection
- Input: transcript text
- Purpose: identify likely questions
- Storage: in memory during session
- Sent externally: no

### AI answer generation
- Input: detected question and recent transcript context
- Purpose: generate concise suggested answer
- Sent externally:
  - OpenAI: yes, when enabled

### Credentials
- Input: user API key
- Purpose: provider authentication
- Storage: Windows Credential Manager
- Sent externally: only to authenticate requests to the configured provider