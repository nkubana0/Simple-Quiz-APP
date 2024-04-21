# Simple Quiz App

This is a simple quiz application built with HTML, CSS, and JavaScript. It presents multiple-choice questions to the user and allows them to select an answer. After selecting an answer, the user can proceed to the next question.

## Features

- Multiple-choice questions with options.
- Feedback for correct and incorrect answers.
- Simple design with responsive layout.

To use the quiz app, follow these steps:

1. Clone the repository to your local machine:

git clone <repository_url>

vbnet
Copy code

2. Open the `index.html` file in your web browser.

3. Start answering the questions by selecting an option for each question.

4. Click the "Next" button to move to the next question.

5. Repeat steps 3-4 until you finish all the questions.

## Customization

You can customize the quiz by editing the `questions` array in the `script.js` file. Each question is represented as an object with a `question` key for the question text and an `answers` key for an array of possible answers. Each answer object should have a `text` key for the answer text and a `correct` key to indicate whether it is the correct answer.

```javascript
const questions = [
{
 question: "Which is the largest animal in the world",
 answers: [
   { text: "Shark", correct: false },
   { text: "Blue Whale", correct: true },
   { text: "Elephant", correct: false },
   { text: "Giraffe", correct: false },
 ],
},
// Add more questions here
];
