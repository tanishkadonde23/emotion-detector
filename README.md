# emotion-detector

# Emotion Detector

## Project Description

The Emotion Detector is a Python application that uses IBM Watson Natural Language Processing (NLP) to identify emotions expressed in text.

The application analyzes input text and returns scores for five emotions: anger, disgust, fear, joy, and sadness. It also identifies the dominant emotion.

## Features

- Emotion detection using the IBM Watson NLP API
- Formatted emotion scores and dominant emotion
- Python package organization
- Unit testing
- Flask web application
- Error handling for invalid or blank input
- Static code analysis using Pylint

## Technologies Used

- Python
- IBM Watson NLP EmotionPredict API
- Flask
- Requests
- Unittest
- Pylint

## Project Structure

```text
emotion-detector/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── emotion_detection.py
├── server.py
├── test_emotion_detection.py
└── README.md
```

## How to Run

Install the required dependencies:

```bash
pip install requests flask pylint
```

Run the Flask application:

```bash
python3 server.py
```

Open `http://localhost:5000` in your browser if the server starts successfully.

## Testing

Run the unit tests using:

```bash
python3 -m unittest test_emotion_detection.py
```

Run static code analysis using:

```bash
pylint server.py
```

## Author

Tanishka D.
