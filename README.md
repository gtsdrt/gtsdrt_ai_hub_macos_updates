# AIChatApp updates

Public signed macOS installers and automatic update feed. Source code remains private.

Download the latest DMG from [Releases](https://github.com/gtsdrt/gtsdrt_ai_hub_macos_updates/releases/latest), quit AIChatApp, and replace the app in Applications.

Apps configured with the old private update URL need this manual installation once. Future updates use this repository automatically.

The app checks the Ed25519 signatures of both the update feed and ZIP. No API keys, credentials, chat history, or signing private keys belong in this repository. Installed apps retain credentials locally in Keychain; this repository does not receive them.

Requires macOS 13 or later and Apple Silicon. Installer binaries can be analyzed; keeping the development repository private is not binary obfuscation.
