# yt-medialoader

**yt-medialoader** is a simple locally-run tool for downloading video and audio from YouTube and other supported platforms using **yt-dlp** and **ffmpeg**.

The project is intended for users who want a straightforward and reliable way to download media without complex configuration, web services, or command-line usage.

---

## Features

- Downloads the best available video quality
- Automatically merges video and audio streams
- Outputs files in **MP4 format** for wide compatibility
- No installation or additional setup required

---

## How to use (1–2–3)

1. Open `links.txt` and paste your URLs (one per line)  
2. Run `start.bat`  
3. Downloaded files will appear in the `downloads` folder

---

## Included files

- `start.bat` — launcher script  
- `links.txt` — list of URLs  
- `yt-dlp.exe` — media downloader  
- `ffmpeg.exe` / `ffprobe.exe` — media processing  
- `downloads/` — output directory  

---

## Format and compatibility

By default, the script:
- selects the best available **MP4** video stream
- forces **M4A (AAC)** audio for stable MP4 merging

This avoids common issues with **OPUS audio**, which is frequently used by YouTube but is not compatible with the MP4 container.

---

## Notes

- The tool runs locally and requires an active internet connection
- Some content may be unavailable due to regional, privacy, or age restrictions
- This project is provided **as-is**, without any warranty

---

## Download

A ready-to-use build is available in the **Releases** section.

---

## License

No license. Use at your own risk.
