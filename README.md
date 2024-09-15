Custom GenAI LLM Application

Objective:
Create a simple application utilizing a pre-existing GenAI Large Language Model (LLM) to demonstrate its capabilities.

Requirements:

- Choose a pre-trained GenAI LLM model
- Develop a basic application integrating the chosen model
- Provide documentation (README file)
- Host the project on a public GitHub repository

Project Structure:

- `app.py`: Main application file (Flask server and text generation logic)
- `requirements.txt`: List of dependencies
- `README.md`: Documentation file

Getting Started:

Prerequisites:
    - Python 3.7 or higher
    - Pip (Python package installer)
Setup:
    1. Clone the repository
    2. Install dependencies (`pip install -r requirements.txt`)
    3. Run the application (`python app.py`)

Usage:

- Send a POST request to `/generate` with a JSON payload containing the prompt
- Example: `curl -X POST http://localhost:5000/generate -H "Content-Type: application/json" -d '{"prompt": "Once upon a time"}'`

Next Steps (if you make any changes):

- Review and update the README file
- Push the updated README to GitHub
- Deploy the application using a free hosting option
