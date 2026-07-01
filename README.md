# Automated Sign Language Rendering System

A full-stack web application that converts text and speech into Indian Sign Language (ISL) animations using landmark-based gesture rendering. The system bridges the communication gap between hearing and hearing-impaired individuals through real-time, interactive sign language visualization.

---

## Project Resources

🌐 **Live Demo**  
https://setup-1-1pil.onrender.com/

📄 **Research Paper (IEEE I2ITCON 2026)**  
https://drive.google.com/drive/folders/1QmCjGE9YY6VwNsBYDIBuFbLnQagSgeh9?usp=sharing

📘 **Project Report**  
https://drive.google.com/drive/folders/1QmCjGE9YY6VwNsBYDIBuFbLnQagSgeh9?usp=sharing

---

## Research Contribution

The research work based on this project, titled **"Automated Sign Language Rendering System,"** has been **accepted with Minor Revision** for **Oral Presentation** and **Full Paper Publication** at the:

**2nd IEEE International Conference on Information, Implementation, and Innovation in Technology (IEEE I2ITCON 2026)**

Hope Foundation's International Institute of Information Technology (I2IT), Pune, India.

The accepted and presented paper will be submitted to **IEEE Xplore** and is intended for indexing in **Scopus** and **EI Compendex**, subject to the conference publication process.

---

## Features

- Text-to-Sign Language Translation
- Speech-to-Sign Language Translation
- Indian Sign Language (ISL) Grammar Transformation
- Word Tokenization and Mapping
- Landmark-Based Gesture Rendering
- Real-Time 2D Avatar Animation
- Responsive User Interface
- Playback Controls
- Word Suggestions for Unsupported Inputs
- Lightweight JSON-Based Dataset

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

### Dataset

- JSON Landmark Dataset

### Core Technologies

- Natural Language Processing (NLP)
- Speech Recognition
- Computer Vision
- Landmark-Based Animation

---

## Project Architecture

The application follows a modular full-stack architecture consisting of:

- Frontend Layer
- Backend Processing Layer
- Landmark Dataset Layer

The workflow includes:

- Input Acquisition
- Speech-to-Text Conversion
- Sentence Preprocessing
- ISL Grammar Transformation
- Word Mapping
- Landmark Retrieval
- Animation Rendering
- Sign Language Output

---

## Project Structure

```text
Automated-Sign-Language-Rendering-System/
│
├── backend/
├── frontend/
├── explore_data.py
├── migrate_data.py
├── Setup1.py
├── README.md
├── screenshots/
└── .gitignore
```

---

## How It Works

1. The user enters text or provides speech input.
2. Speech input is converted into text using the Web Speech API.
3. The sentence is preprocessed by removing unnecessary words.
4. The processed sentence is transformed into Indian Sign Language grammar.
5. The sentence is tokenized into individual words.
6. Each word is mapped to its corresponding sign representation.
7. Landmark coordinates are retrieved from the JSON dataset.
8. The animation engine renders smooth sign language gestures using a 2D avatar.
9. The generated animation is displayed through the web interface.

---

## Key Highlights

- Supports both text and speech input.
- Grammar-aware translation for Indian Sign Language.
- Landmark-based gesture animation.
- Lightweight and scalable architecture.
- Near real-time response.
- Modular full-stack implementation.
- Easy to extend with additional ISL vocabulary.

---

## Performance

| Metric | Performance |
|---------|------------|
| Text Translation Accuracy | 90–95% |
| Speech Translation Accuracy | 85–90% |
| Animation Rendering | Near Real-Time |
| Dataset | JSON Landmark-Based |
| Gesture Representation | 66 Landmark Points per Frame |

---

## Future Enhancements

- 3D Avatar Rendering
- Facial Expression Integration
- Live Sign Language Recognition
- Expanded ISL Vocabulary
- Multi-language Sign Language Support
- Mobile Application
- Cloud Deployment

---

## Research Publication

**Paper Title**

Automated Sign Language Rendering System

**Conference**

2nd IEEE International Conference on Information, Implementation, and Innovation in Technology (IEEE I2ITCON 2026)

**Research Paper & Project Report**

https://drive.google.com/drive/folders/1QmCjGE9YY6VwNsBYDIBuFbLnQagSgeh9?usp=sharing

---

## Authors

**Janhavi Kolamkar**

Department of Electronics and Telecommunication Engineering

Pune Institute of Computer Technology (PICT), Pune

---
