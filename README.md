# Offline Desktop Text to Speech

<p align="center">
  <strong>A lightweight Python desktop application for previewing and exporting speech on Windows and Linux.</strong>
</p>

<p align="center">
  <img alt="Python Desktop" src="https://img.shields.io/badge/Python_Desktop-3776AB?style=for-the-badge">
  <img alt="Offline TTS" src="https://img.shields.io/badge/Offline_TTS-16A34A?style=for-the-badge">
  <img alt="Maintained by Nasratul Nayem" src="https://img.shields.io/badge/Maintained_by-Nasratul_Nayem-111827?style=for-the-badge">
</p>

## Overview

The application turns written text into speech from a simple desktop interface. Users can preview speech, adjust rate, pitch, and volume, then export the result without working through a command line.

## The problem

Many text-to-speech services require subscriptions, browser uploads, or recurring API usage. That can be inconvenient for frequent narration and accessibility tasks.

## The solution

This project packages a local Python TTS workflow into an approachable cross-platform desktop application, with installer and launcher scripts for Windows, Linux, and WSL.

## What it demonstrates

- Python desktop application development
- Local audio generation and export
- Cross-platform setup automation
- Packaging a standalone Windows executable

## Core capabilities

| Capability | Practical value |
|---|---|
| Live preview | Listen before exporting the final audio |
| Voice controls | Adjust rate, pitch, and volume |
| Local workflow | Run without uploading text to a hosted dashboard |
| Export | Save generated speech as an audio file |
| Cross-platform scripts | Install and run on Windows, Linux, or WSL |
| Windows build | Create a distributable executable |

## Workflow

```mermaid
flowchart LR
A["Enter text"] --> B["Choose voice settings"]
B --> C["Preview speech"]
C --> D["Export audio"]
```

## Technology

- Python
- Desktop GUI toolkit
- Local text-to-speech engine
- PyInstaller build workflow
- Shell and Windows batch scripts

## Project status

**Working desktop utility**

Available voices and audio behavior depend on the speech engines installed by the operating system.

## Run locally

```bash
git clone https://github.com/nasratulnayem/humanizer-tts-unlimited-free.git
cd humanizer-tts-unlimited-free
python -m venv .venv
# Linux: ./install.sh && ./run.sh
# Windows: install.bat then run.bat
```

## Usage

Enter text, select the available voice settings, preview the result, and export it to an audio file.

## Engineering notes

- Configuration and credentials should be supplied through environment variables or local files excluded from Git.
- Generated output and runtime data should not be committed.
- Claims in this README describe the capabilities visible in this repository.
- Before production deployment, review authentication, rate limits, error handling, logging, and provider terms.

## Roadmap

- [ ] Add automated packaging releases
- [ ] Add screenshots for Windows and Linux
- [ ] Add voice discovery and compatibility diagnostics
- [ ] Add basic unit tests around text and export handling

## About the developer

Built by **Nasratul Nayem**, a WordPress, WooCommerce, and automation developer based in Dhaka, Bangladesh.

I build practical systems that remove repetitive work: WordPress plugins, WooCommerce integrations, browser extensions, Python automation, AI-assisted content pipelines, and internal business tools.

- Portfolio: [nayem.dev](https://nayem.dev)
- GitHub: [@nasratulnayem](https://github.com/nasratulnayem)
- LinkedIn: [Nasratul Nayem](https://www.linkedin.com/in/nasratulnayem)

## License

Review the repository license before reuse. Third-party services and APIs remain subject to their own terms.
