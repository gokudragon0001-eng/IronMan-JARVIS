# Iron Man JARVIS — Fresh Android Project

This is a new project, separate from the older JarvisFree repository.

## Build the APK with GitHub
1. Create a new repository named `IronMan-JARVIS`.
2. Upload the contents of this folder to the repository root. Include the hidden `.github` folder.
3. Commit to the `main` branch.
4. Open Actions → **Build Iron Man JARVIS APK** → Run workflow.
5. Download the `IRON-MAN-JARVIS-APK` artifact after the workflow succeeds.

## Included in this starter
- Iron Man-inspired dark cyan HUD interface.
- Manual activate/deactivate speech listening.
- Android SpeechRecognizer with `en-PK` language preference.
- Text-to-speech response.
- App launching: WhatsApp, Instagram, YouTube, Facebook, Chrome, Maps and Spotify.
- Basic English and Roman Urdu app-opening keywords.

## Not included yet
This starter does not yet implement a reliable always-on wake-word detector, personal voice authentication, WhatsApp contact/message automation, arbitrary app control, remote access, or a conversational AI backend. Speech recognition depends on the speech service configured on the phone and may use the internet. This source has not yet been built or tested on the OPPO A16. The workflow produces a debug APK, not a Play Store release.
