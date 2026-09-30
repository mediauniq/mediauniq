<div align="center">
  
# <img width="48" height="48" alt="image" src="https://github.com/user-attachments/assets/3ed3ea57-4d17-4e73-a29b-c2dcae386e7f" /> PRND — Media Randomizer

[![Repo](https://img.shields.io/badge/github-repo-blue?logo=github)](https://github.com/mediauniq/)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D6?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgMGgxMS4zNzd2MTEuMzcyaC0xMS4zNzd6bTEyLjYyMyAwaDExLjM3N3YxMS4zNzJoLTExLjM3N3pNMCAxMi42MjNoMTEuMzc3VjI0SDBabTEyLjYyMyAwaDExLjM3N1YyNEgxMi42MjN6Ii8+PC9zdmc+)](https://mediauniq.com/)
![Version](https://img.shields.io/badge/version-v1.9-success?logo=semver&logoColor=white)
![Interface](https://img.shields.io/badge/interface-EN%20%7C%20RU%20%7C%20ZH-orange?logo=googletranslate&logoColor=white)
![Engine](https://img.shields.io/badge/engine-FFmpeg-informational?logo=ffmpeg&logoColor=white)

[![Website](https://img.shields.io/badge/website-click_to_open-blue?logo=googlechrome)](https://mediauniq.com/)
[![License](https://img.shields.io/badge/License-Commercial-red?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTE0LDJIMTBWNEgxNFYyTTE5LDRIMTVWNkgxOVY0TTUsNEg5VjZINVY0TTE5LDhIMTVWMTBIMTlWOE01LDhIOVYxMEg1VjhNMTQsOFYxMEgxMFY4SDE0TTUsMTJIOVYxNEg1VjEyTTE5LDEySDE1VjE0SDE5VjEyTTE0LDEySDEwVjE0SDE0VjEyTTUsMTZIOVYxOEg1VjE2TTE5LDE2SDE1VjE4SDE5VjE2TTE0LDE2SDEwVjE4SDE0VjE2TTEyLDIwQzEwLjksMjAgMTAsMTkuMSAxMCwxOEgxNEMxNCwxOS4xIDEzLjEsMjAgMTIsMjBaIi8+PC9zdmc+)](https://mediauniq.com/#access)
[![Terms & Conditions](https://img.shields.io/badge/Terms%20%26%20Conditions-Informational-blue?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTE0IDJIMTBWNEgxNFYyTTUgNEg5VjZINVY0TTE5IDRIMTVWNkgxOVY0TTUgOEg5VjEwSDVWOE0xOSA4SDE1VjEwSDE5VjhNMTQgOEgxMFYxMEgxNFY4TTUgMTJIOVYxNEg1VjEyTTE5IDEySDE1VjE0SDE5VjEyTTE0IDEySDEwVjE0SDE0VjEyTTUgMTZIOVYxOEg1VjE2TTE5IDE2SDE1VjE4SDE5VjE2TTE0IDE2SDEwVjE4SDE0VjE2TTEyIDIwQzEwLjkgMjAgMTAgMTkuMSAxMCAxOEgxNEMxNCAxOS4xIDEzLjEgMjAgMTIgMjBaIi8+PC9zdmc+)](https://mediauniq.com/terms-of-use/)

</div>

**PRND Media Randomizer** keeps every file you publish unique. One desktop tool randomizes **images, video and audio** — geometry, colors, overlays, metadata, file dates and names. Ideal for mass DM / SMM campaigns where identical attachments get flagged, and for reaching a wider audience via Telegram PRIME mass messaging.

> This readme is also available in other languages:
> **[RU — Русский](https://github.com/mediauniq/mediauniq/blob/main/README_RU.md)** · **[ZH — 中文](https://github.com/mediauniq/mediauniq/blob/main/README_ZH.md)**

----
<img width="768" alt="MediaUniq" src="https://github.com/user-attachments/assets/62085a1c-2c20-44a9-87af-f5b03c9a14e5" />

----

## ✨ Highlights

| | |
|---|---|
| **3 media modules** | Images, Video and Audio in one window — each with its own randomization stack |
| **Any-to-any converter** | Drop an MP3, get randomized OGG/OPUS/M4A — the formats modern messengers use |
| **Unique everything** | Random effects, EXIF/tag rewrites, random file dates, 5 naming rules |
| **Batch-first** | Point at a folder — get N copies per file with collision-safe names |
| **Live preview** | Check a sample before running: MIN/MAX bounds, auto preview, playback with volume |
| **Private by design** | All processing runs locally (FFmpeg/Pillow) — your media is never uploaded |
| **Multilingual UI** | English, Русский, 简体中文 · 11 themes · adjustable font size and scale |

----
## 🖼️ Images

Supported input: `.jpg` `.jpeg` `.png` `.tif` `.tiff`

| Feature | Details |
|---|---|
| Random geometry | scaling, rotation (both directions), edge crop, rounded corners |
| Random color | contrast, color/saturation, brightness, sharpness, blur, hue |
| RGB pixelation | random number of passes |
| Export quality | random JPEG quality range |
| Border frame | random color and thickness |
| Text overlay | multi-line text, font, size, color / random color, position, opacity, rotation, padding |
| Watermark | image overlay: size, opacity, rotation, padding, 12 position variants incl. manual X/Y in % |
| EXIF metadata | full sanitize or randomize (camera, software, geo position, ...) |
| File date | random modification date |
| Batch mode | folder input, N copies per file |
| Live preview | render a sample with the current settings, MIN/MAX bounds |

----
## 🎬 Video
Supported input: `.mp4` `.mov` `.mkv` `.avi` `.webm` `.m4v` `.mpg` `.mpeg` `.ts` `.wmv` `.gif`

| Feature | Details |
|---|---|
| Trim | random cut from the start and the end |
| Motion | random speed, FPS jitter, mirror, rotation, zoom |
| Color | random brightness, contrast, saturation, gamma |
| Audio track | random volume range, mute |
| Text overlay | multi-line, font, size, opacity, rotation, padding, fade in/out, random show window |
| Border frame | random color and thickness |
| Background | random solid color or an image with a centered overlay |
| Metadata | random MP4 tags, random file date |
| Encoding | CRF range, presets, hardware acceleration, stream-copy mode for metadata-only runs |
| GIF support | animated GIF in — randomized GIF out |
| Preview | frame-accurate preview of the current filter chain |

----
## 🎵 Audio

Supported input: `.mp3` `.wav` `.ogg` `.opus` `.m4a` `.aac` `.flac` `.wma` `.aiff`
Output: `.mp3` `.ogg` `.opus` `.m4a` `.aac` `.wav` `.flac` `.wma`

| Feature | Details |
|---|---|
| Converter | any input format to any output format (e.g. MP3 in — randomized OGG out for messengers) |
| Speed | random playback rate |
| Pitch | random semitone shift, duration preserved |
| Volume | random loudness range |
| EQ | random bass / treble |
| Fade | random fade in and out |
| Bitrate | random bitrate for lossy formats |
| Tags | randomize title/artist/album/genre/date or strip the originals |
| File date | random modification date |
| Preview | renders the first 10 seconds with the current effects and plays it — MIN/MAX, auto preview, volume slider |

----
## 🧩 Common

| Feature | Details |
|---|---|
| Naming rules | 5 global patterns: fully random (default) / original + random / original + number + random / original + number / date-time + random. Existing files are never overwritten |
| Interface | 11 themes, EN/RU/ZH, adjustable font size and UI scale |
| Settings | per-tab state is saved automatically; Restore Last / Recommended / Defaults on every tab |
| Engine | FFmpeg is downloaded automatically on first run |
| Updates & support | free updates, online support |

----
## 🚀 Quick Start

1. Download the latest release, unpack and run.
2. Request a free demo key right in the License window.
3. Pick a tab, choose a source file or folder and a destination, tune the random ranges.
4. Press **RANDOMIZE**.

----
## 🔑 Trial & Licenses

We provide a 24-hour **FREE trial period**: 1,000 randomized files to test and confirm the system's efficiency before making a purchase. The demo-key request button is located inside the software.

After the trial the product is available under several paid subscriptions:

| License | Quota |
|---|---|
| Monthly | 20'000 randomized files |
| Annual | 50'000 randomized files |
| Permanent | Lifetime, unlimited randomized files |

----
## 📥 Download

- [Always Latest Release](https://mediauniq.com/downloads)

----
## 🎥 Video Guide

- [YouTube](https://youtu.be/)

----
## 📸 Screenshots

<img width="256" alt="MediaUniq" src="https://github.com/user-attachments/assets/377323cc-6141-4b73-ab4f-c9f0fac180ff" />
<img width="256" alt="MediaUniq" src="https://github.com/user-attachments/assets/bba82fd8-4513-429f-9d97-155e52d83996" />
<img width="256" alt="MediaUniq" src="https://github.com/user-attachments/assets/822e52dc-eda2-4e90-a607-173407ecb6af" />

----
## 💬 Contacts

| Channel | Contact |
|---|---|
| Web | https://mediauniq.com/ |
| Email | manager[@]mediauniq.com |
| Telegram | [Send message](https://mediauniq.com/telegram-contact) |
| Discord | [Send message](https://mediauniq.com/discord-contact) |
| Element | [Send message](https://mediauniq.com/element-contact) |

----
## ☕ Donations

* [Buy us a coffee :)](https://nowpayments.io/donation/mcv)
* Thank you!

----
