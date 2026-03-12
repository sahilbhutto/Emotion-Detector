# Emotion Detection Web Application

## Project Overview
This project is an AI-based web application that detects emotions in a given text. It was built as the final project for the IBM Python Project for AI & Application Development course on Coursera. The application takes a text input from the user, processes it using the Watson NLP API, and returns the confidence scores for various emotions along with the dominant emotion.

## Features
* Extracts and displays confidence scores for: **Anger, Disgust, Fear, Joy, and Sadness**.
* Identifies the **dominant emotion** from the provided text.
* Handles errors gracefully (e.g., handles blank text inputs by returning an "Invalid text! Please try again!" message).
* Web interface deployed using a **Flask** server.
* Includes a custom Python package (`EmotionDetection`) and unit testing.

## Technologies Used
* **Python 3**
* **Flask** (Web Framework)
* **Requests** (API calls)
* **Watson NLP API** (Emotion Prediction)
* **HTML/CSS/JavaScript** (Frontend)

## Project Structure
* `EmotionDetection/`: Contains the application logic (`emotion_detection.py`) and package initialization (`__init__.py`).
* `server.py`: The Flask server that routes traffic and renders the web interface.
* `test_emotion_detection.py`: Unit tests for the application.
* `templates/index.html`: The frontend user interface.
* `static/`: Contains the styling and client-side scripts.

## How to Run the Application
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)[YourUsername]/[YourRepositoryName].git
   cd [YourRepositoryName]
