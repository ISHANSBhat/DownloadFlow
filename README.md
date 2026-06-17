# DownloadFlow

A Python-based desktop application that automates bulk file downloads from archive link collections, with built-in extraction and cleanup features.

## Features

- Extracts download links from supported pages
- Batch downloads multiple archive parts automatically
- Automatic retry system for failed downloads
- Progress tracking with download statistics
- Automatic archive extraction using WinRAR
- Optional cleanup of downloaded archive files
- Simple Tkinter-based graphical interface
- Multi-threaded operation to keep the UI responsive

## How It Works

1. Enter a supported page URL.
2. Click **Get Links** to collect available download links.
3. Review or edit the generated `input.txt` file if needed.
4. Click **Start Download**.
5. The application downloads all files into a dedicated folder.
6. After completion, optionally extract archives and remove `.rar` files.

## Requirements

- Python 3.10+
- WinRAR installed
  
https://www.chai4.me/ishxt_bhat

## Dependencies

```bash
pip install requests beautifulsoup4 tqdm

