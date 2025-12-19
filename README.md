# 🎙️ Persian Speech-to-Text with OpenAI Whisper

A lightweight Python implementation for transcribing Persian (Farsi) audio files into text using OpenAI's Whisper model. This script is optimized for both speed and accuracy.

## 🚀 Features
- **Language Support:** Specifically configured for Persian (`fa`).
- **Flexible Models:** Easy to switch between `tiny`, `base`, `small`, `medium`, and `large`.
- **Hardware Acceleration:** Automatically uses NVIDIA GPU (CUDA) if available.

## 🛠️ Prerequisites

### 1. System Dependency (FFmpeg)
Whisper requires `ffmpeg` to process audio files.
- **Windows:** `choco install ffmpeg`
- **macOS:** `brew install ffmpeg`
- **Linux:** `sudo apt update && sudo apt install ffmpeg`

### 2. Python Libraries
Install the official Whisper library and its dependencies:
```bash
pip install openai-whisper

📝 How to Use
Clone or Download this repository.

Place your audio file (e.g., AudioFile.mp4.m4a) in the project folder.

Run the script:

⚙️ Configuration
You can modify the model size in the script:

model = whisper.load_model("small"): Good balance for most users.

model = whisper.load_model("medium"): High accuracy for complex Persian dialects.

---

### 📂 Pro-Tip: Adding a `requirements.txt`
In GitHub, it is standard practice to include a `requirements.txt` file. This allows users to install everything in one command. 

**Create a file named `requirements.txt` and paste this inside:**
```text
openai-whisper
setuptools-rust

🚀 How to Upload to GitHub (Quick Steps)
Login to GitHub and click New Repository.

Name it (e.g., persian-whisper-stt).

Select Public and click Create repository.

Click "uploading an existing file".

Drag and drop your Python script, README.md, and requirements.txt.

Click Commit changes.

# 🎙️ Persian Speech-to-Text with Whisper
این پروژه یک اسکریپت ساده پایتون برای تبدیل فایل‌های صوتی فارسی به متن (Transcribe) با استفاده از مدل قدرتمند **Whisper** اپن‌ای‌آی است.

## 🚀 ویژگی‌ها
- پشتیبانی کامل از زبان فارسی.
- استفاده از مدل `small` برای تعادل بین سرعت و دقت.
- قابلیت اجرا روی CPU و GPU.

## 🛠️ پیش‌نیازها
قبل از اجرا، باید ابزار **FFmpeg** را روی سیستم خود نصب داشته باشید:
- **Windows:** `choco install ffmpeg`
- **Linux:** `sudo apt install ffmpeg`
- **Mac:** `brew install ffmpeg`

## 📦 نصب کتابخانه‌ها
برای نصب کتابخانه Whisper دستور زیر را در ترمینال بزنید:
```bash
pip install openai-whisper
