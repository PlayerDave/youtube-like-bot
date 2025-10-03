# youtube like bot

Automate safe, repeatable YouTube “like” actions for testing, demos, and growth experiments. This toolkit provides a pluggable engine with browser automation (Playwright/Puppeteer), optional real-device flows (Appium), proxy rotation, and human-like delays—so you can prototype responsibly and measure impact quickly.

<p align="center"> 
  <a href="https://github.com/yourusername/like bot youtube">
    <img src="https://img.shields.io/badge/Try%20It%20Free-1E90FF?style=for-the-badge&logo=fire&logoColor=white" alt="Try it Free" width="30%">
  </a> 
</p>

<p align="center">
  <a href="https://discord.gg/vBu9huKBvy">
    <img src="https://img.shields.io/badge/Join-Discord-5865F2?logo=discord" alt="Join Discord">
  </a>
  <a href="https://t.me/devpilot1">
    <img src="https://img.shields.io/badge/Contact-Telegram-2CA5E0?logo=telegram" alt="Contact on Telegram">
  </a>
</p>

## Introduction
**like bot youtube** is a modular automation project for performing YouTube “like” actions at scale for QA, research, and outreach experiments. Built for developers, growth teams, and fresh grads learning automation, it supports multiple engines (Playwright/Puppeteer/Appium), multi-account profiles, proxy rotation, and a simple CLI/API.

**3 Key Benefits**
- **Time-saving:** One command to run targeted likes across URLs, playlists, or channels.  
- **Scalable:** Parallel workers with per-profile cookies, proxies, and rate limits.  
- **Safer:** Human-like timings, jitter, random scrolls, and cooldowns to reduce flags.

> **Ethical Use Only**: Respect YouTube’s Terms of Service and local laws. Use strictly for testing, QA, or with explicit permission.

## Features
- Playwright (default) + Puppeteer engines with headful/headless modes  
- Profile manager: cookies, sessions, and per-account device fingerprints  
- Proxy rotation (HTTP/SOCKS), geo-matching, and cooldown scheduling  
- Target selectors: video URLs, channel uploads, or playlist CSV  
- Humanization: random waits, scroll/view time, hover, and partial page reads  
- CLI + REST API + minimal GUI (Electron) starter  
- Dockerized worker pool with horizontal scaling

<p align="center">
  <img src="youtube-like-bot.png" alt="youtube-bot hero" width="80%" hight="70%">
</p>


<p align="center">
  <a href="https://www.loom.com/share/b7734cf1455f4c018e469ee18a821c72" target="_blank" rel="noopener noreferrer">
    <img src="youtube-bot-demo.gif" alt="youtube-bot demo" width="40%">
  </a>
</p>
<p align="center">
  <a href="https://www.loom.com/share/b7734cf1455f4c018e469ee18a821c72" target="_blank" rel="noopener noreferrer">
    Click here to see the demo video
  </a>
</p>

## Use Cases
- QA/testing: validate UI flows, collect timings, and debug selectors  
- Creator analytics experiments (private datasets, small cohorts)  
- Outreach demos for internal teams and classroom automation labs  
- Internal tools: mark training videos as “reviewed/liked” by test accounts

## Contact
<p align="center">
  <a href="https://discord.gg/vBu9huKBvy">
    <img src="https://img.shields.io/badge/Join-Discord-5865F2?logo=discord" alt="Join Discord">
  </a>
  <a href="https://t.me/devpilot1">
    <img src="https://img.shields.io/badge/Contact-Telegram-2CA5E0?logo=telegram" alt="Contact on Telegram">
  </a>
</p>

## Installation Instructions

### Pre-requisites
- **Node.js** ≥ 18 and/or **Python** ≥ 3.10  
- **Docker** (optional, for containerized runs)  
- Optional: **Playwright** browsers will be installed on first run

### Clone
```bash
git clone "https://github.com/yourusername/like bot youtube"
cd "like bot youtube"

