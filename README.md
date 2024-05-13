# JavaFX Quiz Application Project

This JavaFX Quiz Application allows users to take a quiz with multiple-choice questions. It features a login screen where users can log in as either an admin or a regular user. Admins can view all questions, while users can take the quiz and submit their answers for scoring.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Implementation Details](#implementation-details)
4. [Contributing](#contributing)

## Installation
1. Clone the repository to your local machine: https://github.com/MokarramHossainMahir/JavaFX-Quiz-Application-Project.git

2. Navigate to the project directory: cd javafx-quiz-app

3. Compile and run the application using Maven or your preferred IDE.

## Usage
1. Upon running the application, you'll be presented with a login screen.
2. Enter your username and password.
3. If you're an admin, you'll be directed to the admin panel where you can view all questions.
4. If you're a user, you'll be directed to the user panel where you can take the quiz.
5. Answer each question by selecting one of the multiple-choice options.
6. Use the "Next" and "Previous" buttons to navigate between questions.
7. Once you've answered all questions, click the "Submit" button to view your score.

## Implementation Details
### GUI Layout
- The application consists of a login screen and two panels: admin panel and user panel.
- Each panel contains various UI elements such as labels, text fields, buttons, and radio buttons for selecting options.

### Event Handling
- Events such as button clicks are handled using JavaFX event handlers.
- Logic is implemented to move between questions, submit answers, and authenticate users.

### Data Management
- Quiz questions are loaded from an external file (`questions.txt`) using `BufferedReader`.
- User input (selected options) is stored and processed using lists.
- Authentication is implemented using a map to store username-password pairs.

## Contributing
Contributions are welcome! Please follow these guidelines:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure code quality.
4. Test your changes thoroughly.
5. Create a pull request detailing your changes.


