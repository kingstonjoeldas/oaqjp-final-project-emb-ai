# Final Project

## Emotion Detector

An AI-based web application that detects emotions in customer feedback text.
It uses the Watson NLP emotion predict service and is deployed as a web app with Flask.

### Features
- Detects five emotions: anger, disgust, fear, joy and sadness
- Returns the dominant emotion for the given text
- Handles blank input with an error message
- Packaged as `EmotionDetection`, with unit tests and a 10/10 Pylint score

### Project structure
- `EmotionDetection/emotion_detection.py` - emotion detection function
- `EmotionDetection/__init__.py` - package file
- `test_emotion_detection.py` - unit tests
- `server.py` - Flask web server
- `templates/index.html`, `static/mywebscript.js` - web interface

### How to run
```
python3 -m pip install flask requests
python3 server.py
```
Then open the app on port 5000.

### Run unit tests
```
python3 test_emotion_detection.py
```
