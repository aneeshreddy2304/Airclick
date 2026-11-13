<p align="center"><img src="docs/assets/banner.svg" alt="Airclick — Hands, voice, and a new way to navigate." width="100%"></p>

<p align="center"><img src="docs/assets/badges/python.svg" alt="python" height="28"> <img src="docs/assets/badges/opencv.svg" alt="opencv" height="28"> <img src="docs/assets/badges/mediapipe.svg" alt="mediapipe" height="28"> <img src="docs/assets/badges/pyautogui.svg" alt="pyautogui" height="28"> <img src="docs/assets/badges/eel.svg" alt="eel" height="28"></p>

<p align="center"><strong>A desktop-interaction prototype that translates hand landmarks and voice commands into mouse, media, and assistant actions.</strong></p>

## Overview

A desktop-interaction prototype that translates hand landmarks and voice commands into mouse, media, and assistant actions.

### Why it matters

Airclick explores multimodal accessibility and interaction by connecting camera and microphone input to practical desktop controls.

## Key features

- MediaPipe hand-landmark tracking
- Gesture-to-mouse and system-control mapping
- Voice commands and spoken responses
- Eel-based chat interface

## Architecture

```mermaid
flowchart TB
  A[Camera] --> B[MediaPipe landmarks]
  B --> C[Gesture rules]
  C --> D[Desktop actions]
  E[Voice or chat] --> F[Command handling]
  F --> G[Eel UI + spoken response]
```

## Technology stack

**python** · **opencv** · **mediapipe** · **pyautogui** · **eel**

## Getting started

Use a compatible Windows Python environment with a camera and microphone. Install `requirements.txt`, then choose either the gesture controller or voice application. Test only in a safe desktop session with an emergency stop available.
