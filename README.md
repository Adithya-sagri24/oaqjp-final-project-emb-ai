# Emotion Detection Application

A web-based AI application that detects and analyzes emotions from text using the Watson NLP library and Flask.

## Project Name
**Emotion Detection Web Application**

## Overview
This project is developed as part of the IBM course **"Developing AI Applications with Python and Flask"**. The application leverages Watson NLP's embedded emotion prediction service (`emotion_aggregated-workflow_lang_en_stock`) to extract emotion metrics for anger, disgust, fear, joy, and sadness from user text, determine the dominant emotion, and display results through a web interface.

## Project Structure
```text
Developing AI Applications/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── 6b_deployment_test.png
├── 7c_error_handling_interface.png
├── README.md
├── server.py
└── test_emotion_detection.py
```

## Features
- **Emotion Analysis:** Analyzes text statements and computes scores for `anger`, `disgust`, `fear`, `joy`, and `sadness`.
- **Dominant Emotion Detection:** Identifies the strongest emotion detected in the text.
- **Python Packaging:** Modular package structure under `EmotionDetection`.
- **Unit Testing:** Comprehensive test suite in `test_emotion_detection.py` validating 5 emotional states.
- **Flask Web Deployment:** Interactive web interface running on `localhost:5000`.
- **Robust Error Handling:** Gracefully handles empty or blank inputs and status code 400 with a user-friendly prompt.
- **Static Code Analysis:** Follows PEP 8 standards with a `10.00/10` Pylint rating.

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install dependencies:**
   ```bash
   pip install flask requests pylint
   ```

3. **Run Unit Tests:**
   ```bash
   python test_emotion_detection.py
   ```

4. **Run Static Code Analysis:**
   ```bash
   pylint server.py
   ```

5. **Start Flask Server:**
   ```bash
   python server.py
   ```
   Open your browser and navigate to `http://localhost:5000/`.

## Author
Adithya Sagri
