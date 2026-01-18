# 🎬 yt-medialoader

**yt-medialoader** is a simple, locally-run tool for downloading video and audio from YouTube and other supported platforms using **yt-dlp** and **ffmpeg**.

It is designed for users who want a clean and reliable way to download media without complex setup, web services, or command-line usage.

---

## ✨ Features

- 🎥 Downloads the best available video quality  
- 🔊 Automatically merges video and audio streams  
- 📦 Outputs files in **MP4 format** for wide compatibility  
- 🖥️ Runs locally, no installation required  

---

## 🚀 How to use (1–2–3)

1. 📝 Open `links.txt` and paste your URLs (one per line)  
2. ▶️ Run `start.bat`  
3. 📁 Downloaded files will appear in the `downloads` folder  

---

## 📦 Included files

- ▶️ `start.bat` — launcher script  
- 📝 `links.txt` — list of URLs  
- 📥 `yt-dlp.exe` — media downloader  
- 🎞️ `ffmpeg.exe` / `ffprobe.exe` — media processing  
- 📁 `downloads/` — output directory  

---

## 🎬 Format & compatibility

By default, the script:

- selects the best available **MP4** video stream  
- forces **M4A (AAC)** audio for stable MP4 merging  

This avoids common issues with **OPUS audio**, which is frequently used by YouTube but is not compatible with the MP4 container.

---

## ⚠️ Notes

- 🌐 An active internet connection is required  
- 🔒 Some content may be unavailable due to region, privacy, or age restrictions  
- 🧪 This project is provided **as-is**, without any warranty  

---

## ⬇️ Download

A ready-to-use build is available in the **Releases** section.

---

## 📄 License

No license. Use at your own risk.
