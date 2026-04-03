# AutoEIT Transcription System

## Overview

This project aims to build an AI-based speech-to-text transcription system for non-native language learners as part of Google Summer of Code (GSoC 2026) under the HumanAI organization.

The system focuses on converting audio responses from Elicited Imitation Tasks (EIT) into accurate and usable text, even when dealing with diverse accents, pronunciation errors, and varying proficiency levels.


## Problem Statement

Current speech recognition systems perform well on native speakers but struggle with non-native speech due to:

* Accent variation
* Pronunciation errors
* Disfluencies and pauses
* Partial or incorrect sentence reproduction

This makes manual transcription necessary, which is slow, expensive, and error-prone.



## Proposed Solution

![Pipeline](Audio%20to%20text%20conversion%20pipeline.png)
Audio Input → Preprocessing → Speech-to-Text → Post-processing → Clean Text Output



## Features (Planned)

* Audio preprocessing (noise reduction, silence trimming)
* Speech-to-text transcription using AI models (Whisper / SpeechRecognition)
* Error correction for non-native speech patterns
* Clean and structured text output
* Future integration with automated scoring system



## Tech Stack

* Python
* OpenAI Whisper / SpeechRecognition
* NumPy / Pandas
* (Future) PyTorch / TensorFlow



## Project Structure (Planned)


autoeit/
│── transcription_pipeline.py
│── preprocess.py
│── sample_audio/
│── README.md
```



## Future Scope

* Model fine-tuning for multilingual learners
* Support for multiple languages
* Web interface for uploading and analyzing audio
* Integration with automated scoring system



## Current Status

Work in Progress (Initial Prototype Phase)
Currently building the base speech-to-text pipeline.



## Contribution

This project is part of GSoC 2026 preparation. Contributions, suggestions, and improvements are welcome.



## Author

Sumit Mewada
GSoC 2026 Aspirant | AI/ML Enthusiast
GitHub: https://github.com/KM-Sumit/
