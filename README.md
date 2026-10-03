# CreatorAI Video Processing Engine 🎬

This is the core headless video rendering API for CreatorAI. It handles multi-clip timeline concatenation, audio ducking, dynamic subtitles, and format rotation using raw FFmpeg.

## ⚙️ Prerequisites
You must have **FFmpeg** installed on your system and added to your PATH. 
- Windows: `winget install ffmpeg`
- Mac: `brew install ffmpeg`

## 🚀 Setup & Installation
1. Clone this repository to your local machine.
2. Create a virtual environment:
   ```bash
   python -m venv .venv