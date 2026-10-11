# JARVIS Voice Assistant - Complete Tutorial Playlist Code (Parts 1 to 7)

Welcome to the official source code repository for the **JARVIS Voice Assistant Series**!
Every part in this playlist is organized into its own self-contained folder so you can follow along episode by episode, build the app at any stage, and inspect how features were implemented.

---

## 📁 Repository Structure

```
Playlist/
├── Part 1/    # Foundation: Gemini Live Bidi WebSocket, PCM Audio Streaming & Canvas Orb
├── Part 2/    # Architecture & Setup notes
├── Part 3/    # Offline Wake Word (Vosk), Background Services, Automation & Memory
├── Part 4/    # Low-Latency Audio, Natural Turn-Taking, System Integration
├── Part 5/    # Advanced Accessibility Controls, YouTube/WhatsApp Automations & UI Polish
├── Part 6/    # Screen-Sharing Vision, Real-Time Multimodal Reasoning & Bugfixes
└── Part 7/    # Agentic Workflows, Floating Overlays, Sound FX & Production Ready Engine
```

---

## 🚀 How to Run Any Part

1. **Open in Android Studio**:
   - Open Android Studio (Ladybug / Koala or newer recommended).
   - Click **Open** and select the folder of the part you want to test (e.g. `Playlist/Part 1` or `Playlist/Part 7`).
2. **Configure Local SDK**:
   - Android Studio will automatically create `local.properties` pointing to your local Android SDK.
   - If building from command-line, copy `local.properties.example` to `local.properties` and verify your SDK path.
3. **Set Gemini API Key**:
   - Launch the app on your Android device or emulator.
   - Open **Settings** within the app and paste your Google Gemini API key.
4. **Build & Run**:
   - Run `./gradlew assembleDebug` or click **Run (Shift + F10)** in Android Studio.

---

## 🧹 Cleaned & GitHub-Ready
- **Zero bloat**: Over 4 GB of local build caches, compiler artifacts (`.gradle/`, `.kotlin/`, `build/`), and dead files have been thoroughly cleaned.
- **No file > 100 MB**: 100% compliant with GitHub push limits (no LFS errors).
- **Safe & Sanitized**: Developer-specific machine paths in `local.properties` removed in favor of clean templates.

Happy coding! Build your own JARVIS! 🎙️⚡
