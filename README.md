# Emotion Detection Application

This project is an **Emotion Detection** application developed as the final project for the IBM AI Developer certification. It analyzes text input and determines the dominant emotion along with individual scores for various emotions using the Watson NLP library.

## Features
- **Emotion Analysis:** Extracts scores for `anger`, `disgust`, `fear`, `joy`, and `sadness` from any given text.
- **Dominant Emotion:** Automatically identifies and highlights the strongest emotion in the text.
- **Web Interface:** Includes a Flask-based web server and a front-end interface for easy interaction.
- **Error Handling:** Gracefully handles empty inputs or invalid text to ensure a smooth user experience.
- **Unit Testing:** Comprehensive test coverage using Python's `unittest` module.
- **Clean Code:** Fully compliant with `pylint` (score of 10.00/10) with proper documentation.

## Technologies Used
- Python 3
- Flask
- Requests (for interacting with the Watson NLP API)
- HTML/JavaScript (for the front-end)

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GuleriaPiyush/oaqjp-final-project-emb-ai.git
   cd oaqjp-final-project-emb-ai
   ```

2. **Install requirements:**
   ```bash
   pip install requests flask pylint
   ```

3. **Run the application:**
   ```bash
   python3 server.py
   ```

4. **Access the Web Interface:**
   Open your browser and navigate to `http://localhost:5000` to interact with the Emotion Detector.
