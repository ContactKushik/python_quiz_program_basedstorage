# Quiz App

A simple Python-based quiz application that allows users to register, log in, attempt various quizzes (Python, DSA, CSE), view high scores, and delete their accounts. The app stores user data (username, password) and quiz scores persistently, enabling users to track their progress.

## Features

- **User Registration**: Users can create an account with a username and password.
- **Login**: Users can log in using their username and password.
- **Attempt Quizzes**: Choose from three categories of quizzes:
  - **Python**: Questions related to Python programming.
  - **DSA**: Questions related to Data Structures and Algorithms.
  - **CSE**: Questions related to Computer Science Engineering.
- **Score Tracking**: Users' highest scores for each quiz are saved and displayed.
- **View High Scores**: After attempting a quiz, users can view their highest score for each quiz category.
- **Delete Account**: Users can delete their accounts, which removes both their user data and quiz scores.

## File Structure

- **users.txt**: Stores usernames and passwords.
- **scores.txt**: Stores users' highest scores for each quiz category (Python, DSA, CSE).

## Setup

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/ContactKushik/quiz-app.git
    cd quiz-app
    ```

2. Run the application:

    ```bash
    python3 quiz_app.py
    ```

### Usage

1. **Register**: Create a new account by entering a username and password.
2. **Login**: Log in with your username and password.
3. **Attempt Quiz**: Select a quiz category (Python, DSA, CSE) and answer the questions.
4. **View High Scores**: After attempting a quiz, view your highest scores in each category.
5. **Delete User**: If needed, delete your account, which removes both your user data and quiz scores.

## Code Explanation

- The app uses a simple dictionary-based system (`users` and `scores`) to manage user data and quiz scores.
- It features multiple-choice questions for three categories: Python, DSA, and CSE.
- The app calculates and tracks the user's score for each quiz, updating their highest score if they achieve a new high score.
- Users can choose to delete their account, which clears their information and scores from the system.
