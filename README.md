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

## Dependencies

```bash
pip install requests beautifulsoup4 tqdm

<a href="https://chai4.me/ishxt_bhat" target="_blank" title="Support ishxt_bhat on Chai4Me" style="display:inline-flex;flex-direction:column;align-items:center;justify-content:center;background:#ffffff;padding:8px 32px;border-radius:16px;text-decoration:none;border:1px solid #e5e7eb;box-shadow:0 4px 6px -1px rgba(0,0,0,0.05), 0 2px 4px -2px rgba(0,0,0,0.05);transition:transform 0.2s;"><img src="https://chai4.me/icons/wordmark.png" alt="Chai4Me" style="height:32px;object-fit:contain;margin-bottom:4px;"/><span style="color:#6b7280;font-family:sans-serif;font-size:14px;font-weight:600;">@ishxt_bhat</span></a>

