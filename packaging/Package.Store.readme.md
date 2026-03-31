# Package Store Notes

## Packaging guidance
- Keep writable data in LocalAppData or Windows-managed app storage
- Do not rely on the package install folder for writable data

## Store review note
Describe clearly that the app processes system audio output locally and may send audio/text to OpenAI only during active user-started transcription or answer-generation requests.
