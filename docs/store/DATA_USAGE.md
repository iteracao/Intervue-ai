# Data Usage - Intervue AI

## Data processed by feature

### Real-time audio capture
- Input: system audio output
- Purpose: transcription
- Storage: in memory during processing
- Sent externally: only to OpenAI when the app sends audio for transcription
- Does not capture: microphone input

### Transcription
- Input: audio chunks
- Purpose: speech-to-text conversion
- Storage: temporary or in-memory depending on settings
- Sent externally:
  - OpenAI: yes

### Question detection
- Input: transcript text
- Purpose: identify likely questions
- Storage: in memory during session
- Sent externally: no

### AI answer generation
- Input: detected question and recent transcript context
- Purpose: generate concise suggested answer
- Sent externally:
  - OpenAI: yes, during active answer-generation requests

### Credentials
- Input: user API key
- Purpose: provider authentication
- Storage: Windows Credential Manager
- Sent externally: only to authenticate requests to OpenAI

## What the current packaged app does not use
- Microphone capture
- Offline/local transcription providers
- Hidden background recording when detection is not running
