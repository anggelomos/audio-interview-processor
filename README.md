# audio-interview-processor

A small script to process interviews and turn them into a document

## Prerequisites

### Installing FFmpeg

This project requires FFmpeg to convert video files to audio format. Install it using the following commands:

#### Windows

```bash
# Using chocolatey (if you have it installed)
choco install ffmpeg

# Using winget (Windows 10/11 built-in package manager)
winget install ffmpeg

# Alternative: Download manually from https://ffmpeg.org/download.html
```

#### macOS

```bash
# Using homebrew
brew install ffmpeg
```

#### Linux

```bash
# Ubuntu/Debian
sudo apt update && sudo apt install ffmpeg

# CentOS/RHEL/Fedora
sudo yum install ffmpeg
# or for newer versions:
sudo dnf install ffmpeg
```

### Verify Installation

After installation, verify FFmpeg is working by running:

```bash
ffmpeg -version
```

You should see version information if FFmpeg is properly installed.
