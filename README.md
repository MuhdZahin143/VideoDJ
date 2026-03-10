# Desktop DJ App (Zahin)

A desktop video/audio DJ application built with Python and PySide6.

## Features

- **Media Playback**: Play video and audio files (MP3, WAV, OGG, MP4, AVI, WMV)
- **Playlist Management**: Load media folders and manage playlists
- **Transport Controls**: Play, Pause, Stop, Previous, Next, Play All
- **Volume Control**: Adjustable volume slider
- **Progress Bar**: Seek through media with time display
- **Theme Toggle**: Dark mode and Light mode switching
- **32-bit Optimized**: Designed for 32-bit systems

## Requirements

- Python 3.x
- PySide6
- PyInstaller (for building executable)

## Installation

1. Install dependencies:
```bash
pip install PySide6
```

2. Run the application:
```bash
python main.py
```

## Building Executable

To build the executable:
```bash
pyinstaller VideoDJ.spec
```

## License

MIT License

