# MagicSub ✨  
**One-click automatic subtitle generator powered by OpenAI Whisper**

MagicSub is a lightweight Windows application that automatically generates subtitles from video or audio files with a single click.  
It is built on top of OpenAI Whisper and packaged with ffmpeg, so no additional installation is required.

---

## 🚀 Key Features

- ✅ One-click automatic subtitle generation
- ✅ Supports **SRT / VTT / TXT / FCPXML** formats
- ✅ GUI-based (no command line required)
- ✅ Built-in **ffmpeg** (no external dependency)
- ✅ Powered by **OpenAI Whisper**
- ✅ Korean / English / Multilingual support
- ✅ FCPXML export for **DaVinci Resolve**
- ✅ Font color & FPS control for FCPXML

---

## 🖥️ System Requirements

- Windows 10 / 11 (64-bit)
- NVIDIA GPU recommended (for faster processing)
- CPU-only mode is supported (slower)

---

## ⚡ GPU / CPU Execution Mode

MagicSub automatically uses **GPU (CUDA)** if it is available on your system.

- If **CUDA is NOT installed**, MagicSub will **automatically fall back to CPU mode**.
- CPU mode works correctly, but **processing speed will be significantly slower**.
- For the **best performance**, an NVIDIA GPU with CUDA installed is strongly recommended.

Summary:
- NVIDIA GPU + CUDA installed → **Fast GPU mode**
- No CUDA / No GPU → **Slower CPU mode (automatic fallback)**

To enable GPU acceleration, please install:
- NVIDIA Graphics Driver
- CUDA Toolkit

---

## 📦 Download

Go to the **Releases** page and download the latest installer:

👉 https://github.com/ssw03270/MagicSub/releases

Download:
- `MagicSub_Setup.exe`

After installation, you can run MagicSub from the desktop or start menu.

---

## 🛠️ Supported Formats

### Input
- `.mp4`, `.mkv`, `.mov`, `.avi`
- `.wav`, `.mp3`, `.m4a`, `.aac`

### Output
- `.srt` – Standard subtitle
- `.vtt` – WebVTT subtitle
- `.txt` – Plain transcript
- `.fcpxml` – DaVinci Resolve subtitle titles

---

## 🎬 DaVinci Resolve (FCPXML) Workflow

1. Export subtitles as **FCPXML**
2. Open DaVinci Resolve
3. Go to **File → Import Timeline → Import AAF, EDL, XML**
4. Select the exported `.fcpxml` file
5. Subtitles will appear as **Title clips on the timeline**

---

## 🧩 Built With

- **Python**
- **PySide6 (Qt)**
- **OpenAI Whisper**
- **ffmpeg**
- **PyInstaller**
- **Inno Setup**

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙋‍♂️ Author

SeungWon Seo  
Korea University  
Graphics AI / LLM Planning / Virtual Agent Researcher

---

## ⭐ If you like this project

Please consider giving it a **star ⭐** on GitHub.  
It helps a lot!
