# Automated Sign Language Rendering System

A full-stack web application that converts text and speech into Indian Sign Language (ISL) animations using landmark-based gesture rendering. The system aims to bridge the communication gap between hearing and hearing-impaired individuals by providing real-time, interactive sign language visualization.

---

## Features

- Text-to-Sign Language Translation
- Speech-to-Sign Language Translation
- Indian Sign Language (ISL) Grammar Transformation
- Word Tokenization and Mapping
- Landmark-Based Gesture Rendering
- Real-Time 2D Avatar Animation
- Playback Controls
- Word Suggestions for Unsupported Inputs
- Lightweight JSON-Based Dataset
- Responsive User Interface

---

## System Workflow

```text
Text / Speech Input
        │
Speech-to-Text (if required)
        │
Sentence Preprocessing
        │
ISL Grammar Transformation
        │
Word Tokenization
        │
Word-to-Sign Mapping
        │
Landmark Data Retrieval
        │
Animation Rendering
        │
Sign Language Animation Output
```

---

## Tech Stack

### Frontend
- React
- Vite
- HTML5
- CSS3
- JavaScript
- Web Speech API

### Backend
- Java
- Spring Boot
- REST API

### Data
- JSON Landmark Dataset

### Concepts Used
- Natural Language Processing (NLP)
- Speech Recognition
- Computer Vision
- Landmark-Based Animation

---

## Project Structure

```
Automated-Sign-Language-Rendering-System/
│
├── backend/
├── frontend/
├── explore_data.py
├── migrate_data.py
├── Setup1.py
├── README.md
└── .gitignore
```

---

## How It Works

1. User enters text or provides speech input.
2. Speech input is converted into text using the Web Speech API.
3. The sentence is preprocessed and transformed into ISL grammar.
4. The processed sentence is tokenized into individual words.
5. Each word is mapped to its corresponding sign representation.
6. Landmark data is retrieved from the JSON dataset.
7. The animation engine renders smooth 2D sign language gestures.
8. The generated sign language animation is displayed to the user.

---

## Key Highlights

- Supports both text and voice input.
- Grammar-aware translation for Indian Sign Language.
- Lightweight landmark-based rendering.
- Modular full-stack architecture.
- Near real-time animation generation.
- Easy to extend with additional sign vocabulary.

---

## Performance

| Metric | Value |
|---------|-------|
| Text Input Accuracy | 90–95% |
| Speech Input Accuracy | 85–90% |
| Animation | Near Real-Time |
| Dataset | JSON Landmark-Based |

---

## Future Enhancements

- 3D Avatar Rendering
- Facial Expression Integration
- Live Sign Language Recognition
- Expanded ISL Vocabulary
- Multi-Language Support
- Cloud Deployment

---

## Authors

Janhavi Kolamkar
  
Department of Electronics and Telecommunication Engineering

Pune Institute of Computer Technology (PICT), Pune

---


