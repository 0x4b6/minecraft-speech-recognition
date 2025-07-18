# minecraft-speech-recognition

A Windows application that enables voice input for Minecraft using Faster-Whisper speech recognition. Use hotkeys to activate voice recording and automatically type messages in-game.

## Features

- **Push-To-Talk**: Hold configurable hotkeys while speaking to automatically type messages in Minecraft
- **Multiple Prefix Support**: Configure 3 different hotkey combinations with custom message prefixes
- **Auto-Send Mode**: Choose between automatic message sending or manual editing before sending
- **Minecraft Integration**: Voice recognition activates only when Minecraft is the foreground application

## Requirements

- Windows operating system (uses Windows-specific APIs for process detection)
- Python 3.8 or higher
- Microphone
- Minecraft Java Edition

## Installation

1. Clone the repository
2. Install required dependencies

    ```bash
    pip install -r requirements.txt
    ```

3. Run the application:

    ```bash
    python src/main.py
    ```

## Logs

Application logs are stored in:

```
%appdata%\.minecraft\minecraft-STT\minecraft_stt.log
```