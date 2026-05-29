# SpeakAble

An AI-powered accessibility communication platform that helps non-verbal individuals communicate through gesture recognition, sign language interpretation, facial emotion analysis, and real-time voice generation.

![Next.js](https://img.shields.io/badge/Next.js-14-black)
![TypeScript](https://img.shields.io/badge/TypeScript-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-green)
![MediaPipe](https://img.shields.io/badge/MediaPipe-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-red)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E)

---

## Overview

SpeakAble is designed to bridge communication barriers for individuals with speech and communication impairments. Using real-time computer vision and AI, the platform interprets hand gestures, sign language, and facial expressions through a webcam and converts them into understandable text and speech.

The goal is to provide a simple, accessible, and emotionally supportive communication experience for non-verbal users.

---

## Features

### ✋ Gesture Recognition
Detects predefined communication gestures and converts them into meaningful phrases.

Examples:
- 👍 Yes
- 👎 No
- ✋ Help
- ✊ Stop
- ☝️ Need Water

---

### 🤟 Sign Language Interpretation
Recognizes ASL alphabet gestures and translates them into text.

Features:
- Real-time sign detection
- Word builder
- Speech generation from detected signs

---

### 😊 Facial Emotion Detection
Analyzes facial expressions to identify emotions such as:

- Happy
- Sad
- Neutral
- Surprised
- Concerned

Emotion detection provides additional context during communication.

---

### 🔊 Voice Output
Converts detected gestures and sign language into natural speech using browser-based text-to-speech.

---

### 🚨 Emergency Communication
Provides one-tap emergency phrases:

- I Need Help
- I Need Water
- Call My Caregiver
- I Am In Pain

Designed for quick communication in critical situations.

---

### 📊 Live Activity Feed
Tracks:
- Gesture detections
- Sign language outputs
- Emotion changes
- Communication history

---

## Modes

### Communication Mode

Designed for rapid communication using custom gestures.

Includes:
- Gesture Detection
- Emotion Detection
- Voice Output
- Emergency Phrases

---

### Sign Language Mode

Designed for sign language translation.

Includes:
- ASL Recognition
- Word Builder
- Emotion Detection
- Voice Output

Communication gestures are disabled in this mode to avoid detection conflicts.

---

## Tech Stack

### Frontend

- Next.js
- React.js
- TypeScript
- Tailwind CSS
- Framer Motion
- shadcn/ui

### Backend

- FastAPI
- Python

### Computer Vision & AI

- MediaPipe
- OpenCV
- TensorFlow

### Database & Storage

- Supabase

### Real-Time Communication

- WebRTC
- Browser SpeechSynthesis API

---

## Architecture

```text
Frontend (Next.js)
        │
        ▼
FastAPI Backend
        │
        ▼
AI Processing Layer
(MediaPipe + OpenCV + TensorFlow)
        │
        ▼
Speech Output + UI Updates
        │
        ▼
Supabase Database
```

---

## Project Structure

```text
frontend/
├── app/
├── components/
├── hooks/
├── services/
├── lib/
└── styles/

backend/
├── api/
├── ai/
├── models/
├── services/
└── utils/
```

---

## Workflow

```text
Webcam Feed
      ↓
Frame Processing
      ↓
Gesture / Sign Detection
      ↓
Emotion Analysis
      ↓
Text Generation
      ↓
Voice Output
      ↓
Communication History
```

---

## Future Improvements

- Custom gesture training
- Personalized phrase mapping
- Sign language sentence generation
- Multilingual support
- Caregiver notifications
- Voice cloning
- Mobile application
- Advanced emotion analytics

---

## Accessibility Focus

SpeakAble is built with accessibility-first principles:

- Large readable typography
- High contrast UI
- Keyboard accessibility
- Responsive layouts
- Emotionally supportive design
- Inclusive communication workflows

---

## Mission

> Communicate Beyond Words.

SpeakAble aims to empower non-verbal individuals by providing accessible, AI-assisted communication tools that make everyday interactions easier, faster, and more independent.

---

## License

MIT License
