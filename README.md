# Final-Project---Emotion-Detector

An AI-powered web application that uses Natural Language Processing (NLP) to analyze text and detect emotions such as joy, anger, disgust, fear, and sadness.

## 🚀 Features
AI Analysis: Leverages the Watson NLP library for accurate emotion extraction.

Web Interface: Built with Flask for easy user interaction.

Error Handling: Robust processing of invalid or empty inputs.

Formatted Output: Clear, dictionary-style responses.

## 🛠️ Project Structure & Tasks
The development of this application followed a structured software engineering workflow:

Repository Setup: Cloned the project environment.

Logic Development: Integrated the Watson NLP library for emotion detection.

Data Formatting: Processed raw JSON responses into a readable format.

Packaging: Organized the application for distribution.

Testing: Executed Unit Tests to ensure logic accuracy.

Deployment: Deployed as a web application using the Flask framework.

Reliability: Incorporated comprehensive error handling for edge cases.

Quality Assurance: Conducted Static Code Analysis to maintain PEP8 standards.

## 💻 Installation & Usage

1. Clone the Repository
Bash
git clone <repository-url>
cd emotion-detector
2. Run the Application
Start the Flask server:

Bash
python3 server.py
Open your browser and navigate to http://localhost:5000.

3. Running Tests
To run the unit tests (Task 5):

Bash
python3 test_emotion_detection.py
4. Static Code Analysis
To check code quality (Task 8):

Bash
pylint server.py emotion_detection.py
