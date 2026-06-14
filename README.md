# Quiz Game

## Description

A responsive web-based quiz application built with HTML, CSS, and JavaScript. The game allows users to answer multiple-choice questions, track their score in real time, view their progress, and receive performance feedback at the end of the quiz.

---

## About This Project

This project was created to further develop and enhance my front-end web development skills, particularly in:

* JavaScript DOM manipulation
* Event-driven programming
* Managing application state
* Dynamic UI rendering
* Responsive web design
* Building interactive browser applications without frameworks
* Writing clean, maintainable JavaScript code

---

## Features

✨ **User Interface:**

* Interactive start screen
* Dynamic quiz interface
* Results and feedback screen
* Responsive design for desktop and mobile devices

📚 **Core Functionality:**

* **Multiple-Choice Questions** – Answer a series of quiz questions
* **Score Tracking** – Real-time score updates during gameplay
* **Progress Indicator** – Visual progress bar showing quiz completion
* **Answer Feedback** – Correct and incorrect answers are highlighted
* **Quiz Restart** – Restart and retake the quiz at any time

🔧 **Technology Stack:**

* **Markup:** HTML5
* **Styling:** CSS3
* **Programming Language:** JavaScript (ES6)
* **Architecture:** Vanilla JavaScript (No Frameworks)

---

## Project Structure

```text
02-Quiz_Website/
├── Frontend
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── README.md
```

---

## How the Application Works

### Start Screen

* Displays a welcome message
* Allows users to begin the quiz

### Quiz Screen

* Shows one question at a time
* Displays four answer choices
* Updates score after correct answers
* Highlights correct and incorrect selections
* Tracks progress through a progress bar

### Results Screen

* Displays final score
* Calculates performance percentage
* Shows a custom feedback message based on results
* Allows users to restart the quiz

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/02-Quiz_Website.git
```

### 2. Navigate to the Project Folder

```bash
cd 02-Quiz_Website
```

### 3. Run the Application

Open `index.html` in your preferred web browser.

No installation, dependencies, or build process is required.

---

## Quiz Data Structure

Questions are stored in a JavaScript array inside `script.js`.

Example:

```javascript
{
  question: "What is the capital of France?",
  answers: [
    { text: "London", correct: false },
    { text: "Berlin", correct: false },
    { text: "Paris", correct: true },
    { text: "Madrid", correct: false }
  ]
}
```

To add more questions:

1. Open `script.js`
2. Locate the `quizQuestions` array
3. Add a new question object following the existing structure

---


