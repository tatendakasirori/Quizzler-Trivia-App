# Quizzler Trivia App

A Python-based interactive quiz game that fetches trivia questions from an online API and presents them to users through a responsive GUI built with `tkinter`.

## Overview

Quizzler is a dynamic trivia application that uses the Open Trivia Database API to deliver real-time true/false questions. The app features a clean user interface, tracks the player's score, and provides immediate feedback on each answer. It is modularly designed with separate components for question modeling, quiz logic, and the graphical interface.

## Features

- Retrieves 10 random true/false questions from Open Trivia Database.
- Displays questions in a scroll-friendly, user-friendly GUI.
- Tracks score and shows real-time updates.
- Provides visual feedback (color-coded) based on user input.
- Disables buttons once the quiz ends.

## Technologies

- Python 3.x
- `requests` — for API communication
- `tkinter` — for GUI development
- `html` — for decoding HTML entities in questions

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/quizzler-trivia-app.git
   cd quizzler-trivia-app
2. Install dependencies:
- (These are standard libraries; requests is the only one you may need to install.)
  ```bash
    pip install requests
3. Run the application:
   ```bash
    python main.py
4. Ensure the following file structure:
   ```
    ├── main.py
    ├── question_model.py
    ├── quiz_brain.py
    ├── ui.py
    ├── data.py
    └── images/
        ├── true.png
        └── false.png
## File Descriptions
- `main.py`: Entry point; handles question fetching and initialization.
- `question_model.py`: Defines the Question class.
- `quiz_brain.py`: Handles quiz logic, scoring, and question progression.
- `ui.py`: Creates and manages the tkinter user interface.
- `data.p`y: Fetches data from the trivia API (question_data).
## Notes 
- Requires an internet connection to fetch quiz data.
- Uses only built-in and open-source libraries.
- rue/false button images should be placed in an images/ directory.
