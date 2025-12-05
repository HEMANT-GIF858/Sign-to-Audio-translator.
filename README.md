
🔊 Sign-to-Audio Translator

A Unidirectional Sign-to-Audio Translation System

📌 Overview

The Sign-to-Audio Translator is a unidirectional system designed to convert hand signs into spoken audio output. This project aims to improve communication accessibility for individuals with speech or hearing impairments by mapping hand gestures to predefined audio phrases.

This was developed as a group project, integrating gesture recognition, text mapping, and text-to-speech conversion into one workflow.

🎯 Project Objectives

Detect and recognize predefined hand gestures

Convert recognized signs into meaningful text

Synthesize the text into clear, audible speech

Provide an easy-to-use, low-latency communication tool

🧩 System Architecture

The system works in three major stages:

1️⃣ Gesture Capture

Captures hand gestures using a live video feed or dataset images

Preprocessing applied: frame resizing, filtering, segmentation

2️⃣ Gesture Recognition

Uses a trained model / feature extraction technique

Maps gesture features to predefined labels

Classifies gestures with good accuracy

3️⃣ Audio Generation

Recognized gesture → converted into text

Text-to-Speech (TTS) engine outputs clear audio

🛠️ Tech Stack
Component	Technology Used
Gesture Recognition	OpenCV / Image Processing
Feature Extraction	Contour detection / Hand segmentation
Classification	ML / Custom gesture mapping
Audio Output	Python TTS engine (pyttsx3 / gTTS)
Programming Language	Python

(If you want, I can add exact tools from your code once you upload it.)

🚀 Features

✔ Real-time sign capture
✔ Accurate gesture classification
✔ Instant text and audio output
✔ Lightweight and easy to operate
✔ Helps people with communication disabilities

📂 Project Structure
Sign-to-Audio-Translator/
│── dataset/
│── models/
│── src/
│   │── preprocessing.py
│   │── gesture_recognition.py
│   │── text_to_audio.py
│   │── main.py
│── report/
│── README.md

🧪 How It Works

Show a predefined hand gesture in front of the camera

System detects and classifies the gesture

Mapped text is displayed

Audio is generated immediately using TTS
