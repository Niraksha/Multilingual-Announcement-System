# Multilingual-Announcement-System
An AI-powered multilingual announcement system that transcribes audio, translates it into multiple Indian languages, and generates speech using Whisper, Google Translate, and gTTS.

This project uses advanced pretrained models to transcribe audio, translate the content into multiple Indian languages, and generate speech outputs for better accessibility in public environments such as railway stations, airports, and bus terminals.

## Project Overview

Traditional announcement systems often operate in a single language, which can create difficulties for travelers who do not understand that language.

The **Multilingual Announcement System** solves this problem by automatically:

1. Transcribing audio announcements
2. Detecting the spoken language
3. Translating the message into multiple languages
4. Generating speech outputs for each language
5. Detecting urgency or calm tone in announcements

This improves communication and accessibility in public transportation environments.

## Features

- Automatic Speech Recognition using Whisper
- Multilingual Translation
- Speech Generation using Text-to-Speech
- Emotion-aware announcements (calm / urgent tone)
- Real-time audio processing
- Supports multiple Indian languages

## Supported Languages

The system generates announcements in:

- Tamil
- Hindi
- Bengali
- Kannada
- Telugu
- English

## Technologies Used

- Python
- OpenAI Whisper (Speech Recognition)
- Google Translator (googletrans)
- gTTS (Google Text-to-Speech)
- NumPy
- SoundFile

## System Workflow

1. User uploads or records an audio announcement
2. Whisper converts speech into text
3. Google Translator translates the text into different languages
4. Text preprocessing improves pronunciation clarity
5. gTTS generates audio outputs for each language

## Evaluation Metrics

The system performance was evaluated using:

- Word Error Rate (WER)
- Character Error Rate (CER)
- Sentence Accuracy
- BLEU Score for translation quality
- Audio generation success rate

The model achieved high accuracy in transcription and translation with reliable audio generation.

## Applications

- Railway station announcements
- Airport announcements
- Bus terminals
- Public information systems
- Multilingual accessibility systems
