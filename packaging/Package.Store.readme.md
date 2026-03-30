# Packaging Notes - Intervue AI

## Important
Intervue AI is a packaged desktop application.

## Packaging assumptions
- WPF .NET 8 desktop app
- MSIX packaging project
- Full trust execution required
- Local writable storage must be used for settings and logs
- Do not rely on package install folder for writable data

## Store review note
Describe clearly that the app processes system audio locally and may send audio/text to third-party AI services only when user-configured.