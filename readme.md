# Project Jarvis - AI Desktop Assistant

A powerful AI-powered desktop assistant built with Python, featuring real-time voice interaction, system control, visual awareness, and remote mobile access.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎙️ Voice Interaction | Natural conversation with ultra-low latency |
| 🖥️ System Control | Launch apps, manage files, execute terminal commands |
| 👁️ Visual Awareness | Screen capture and webcam vision processing |
| 🧠 Persistent Memory | Remembers preferences and context across sessions |
| 📱 Remote Control | Control your PC from your phone via browser |
| 📂 File Sharing | Wirelessly transfer files from phone to PC |
| ⌨️ Hybrid Input | Switch between voice and keyboard commands |

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/mahidar22/project-jarvis.git
cd project-jarvis
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
playwright install
```

### 3. Set Up API Key

Create a `.env` file in the project root:

```env
GOOGLE_API_KEY=your_gemini_api_key_here
```

Or set it as a system environment variable:
- Press `Win + R`, type `sysdm.cpl`, Enter
- Go to **Advanced** → **Environment Variables**
- Add a new User variable: `GOOGLE_API_KEY` = `your_api_key`

Get your free API key at: [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)

### 4. Run the Application

```bash
python main.py
```

---

## 📋 Requirements

| Requirement | Version |
|------------|---------|
| Python | 3.11 or 3.12 |
| OS | Windows 10/11, macOS, or Linux |
| Microphone | Required for voice input |

---

## 🔧 Project Structure

```
project-jarvis/
├── main.py              # Main entry point
├── ui.py                # Graphical user interface
├── actions/             # Action modules (files, search, media, etc.)
├── config/              # Configuration files
├── core/                # Core Jarvis logic
├── dashboard/           # Web dashboard for remote control
├── memory/              # Persistent memory system
└── requirements.txt     # Python dependencies
```

---

## ⚠️ Troubleshooting

**ModuleNotFoundError:**
```bash
pip install <missing_module_name>
```

**Voice not working:**
- Ensure microphone is set as default input device
- Check microphone permissions in system settings

**API connection timeout:**
- Verify your internet connection
- Ensure `GOOGLE_API_KEY` is set correctly
- Check if the API key is active at [Google AI Studio](https://aistudio.google.com/app/apikey)

---

## 📄 License

This project is for **personal, non-commercial use only**.

Licensed under **Creative Commons BY-NC 4.0**.

---

## 🙏 Credits

Built with Google Gemini API and PyQt6.

Star this repo if you find it useful!
