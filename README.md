# React Quiz Application

This is a simple React.js quiz application designed to demonstrate the use of React components, hooks, and state management for junior-level React developers.

## Project Overview

The application presents a series of questions with multiple-choice answers. Users can select an answer, see the results at the end, and review their answers. The project showcases fundamental React concepts such as component structure, state management, and effects.

## Features

- **Dynamic Questionnaire**: Displays questions one at a time and stores user answers.
- **Randomized Answers**: Each question's answers are randomized.
- **Time Limits**: Each question has a time limit for responses.
- **Results Summary**: At the end of the quiz, users can see their score and review their answers.

## Technologies Used

- **React.js**: A JavaScript library for building user interfaces.
- **CSS**: For styling components.

## File Structure
- `src`:
    - `assets`: Contains png files used in the application.
    - `components`: Used to organize .jsx files.    
       - `Header.jsx`: Displays the quiz header and logo.
       - `Quiz.jsx`: Manages the quiz logic and state.
       - `Question.jsx`: Renders individual questions and handles answer selection.
       - `Answers.jsx`: Displays answers for a particular question.
       - `QuestionTimer.jsx`: Timer for each question.
       - `Summary.jsx`: Summarizes the quiz results at the end.
- `App.jsx`: Main application component that setups the quiz structure.
- `questions.js`: Contains the quiz questions and answers data.

## Setup and Installation

```bash
# Clone the repository
git clone <repository-url>

# Navigate to the project directory
cd react-quiz-demo

# Install dependencies
npm install

# Run the application
npm start
```

## Usage

Once the application is running, it will be available in your web browser at http://localhost:3000. Navigate through the application:

- **Start the Quiz**: Automatically loads the first question.
- **Answer Questions**: Select an answer for each question within the time limit.
- **Review Results**: At the end of the quiz, review your answers and see your score.
