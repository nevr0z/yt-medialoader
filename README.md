yt-medialoader is a simple offline script for downloading video and audio from YouTube and other supported platforms using yt-dlp and ffmpeg.

This project is designed for users who want a fast and straightforward way to download media, without complex setup, command-line usage, or extra configuration.

The script automatically:

selects the best available video quality;

correctly merges video and audio streams;

outputs files in MP4 format, compatible with most devices and players.

🔧 How to use (1–2–3)

Open links.txt and paste your links (one link per line)

Run start.bat

Downloaded files will appear in the downloads folder

📦 Included files

start.bat — launcher

links.txt — list of URLs

yt-dlp.exe — media downloader

ffmpeg.exe / ffprobe.exe — media processing

downloads/ — output directory

🎬 Format & quality

By default:

downloads the best available MP4 video

forces M4A (AAC) audio for stable MP4 merging

This avoids common issues related to OPUS audio, which is frequently used by YouTube but incompatible with the MP4 container.

⚠ Notes

The script works locally and does not rely on third-party websites

Some videos may be unavailable due to region, privacy, or age restrictions

The project is provided as-is, without any warranty

⬇ Download

A ready-to-use build is available in the Releases section.
