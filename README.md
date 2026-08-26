# Repository for final project
 # oaqjp-final-project-emb-ai

## Final Project - Emotion Detection Application

This project is an emotion detection application developed using the Watson NLP library.

The application analyzes a given text statement and identifies the following emotions:

- Anger
- Disgust
- Fear
- Joy
- Sadness

It also determines the dominant emotion based on the highest emotion score.

## Project Name

oaqjp-final-project-emb-ai

## Technologies Used

- Python 3
- Watson NLP
- Flask
- Requests
- PyLint
- Unit Testing

## Application Features

- Emotion detection using Watson NLP
- JSON response formatting
- Dominant emotion detection
- Python package implementation
- Unit testing
- Flask web deployment
- Error handling for blank input
- Static code analysis using PyLint

## Web Application

The Flask application runs on:

http://localhost:5000

The `/emotionDetector` endpoint accepts text for emotion analysis.

## Error Handling

If the user submits blank or invalid text, the application displays:

Invalid text! Please try again!

## Project Structure

```text
final_project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
│   └── mywebscript.js
├── server.py
├── test_emotion_detection.py
└── README.md