#  Mystic Memory Game

A responsive browser-based Memory Matching Game developed using **HTML5, CSS3, and Vanilla JavaScript**. The project demonstrates core frontend development concepts including DOM manipulation, event-driven programming, state management, animations, and responsive UI design.  

##  Overview

Mystic Memory Game is an interactive card-matching application where players uncover hidden cards and match identical pairs while minimizing moves and completion time.

The project was built to strengthen practical frontend engineering skills by implementing game logic, dynamic UI updates, card state management, and performance-friendly animations without relying on external frameworks.


## Key Features

* Dynamic card generation using JavaScript
* Randomized card shuffling algorithm
* Real-time move tracking
* Live game timer
* Card flip animations using CSS transforms
* Match detection and state management
* Victory modal displaying performance statistics
* Restart and replay functionality
* Mobile-responsive interface


## Technologies Used

| Technology       | Purpose                                |
| ---------------- | -------------------------------------- |
| HTML5            | Semantic structure                     |
| CSS3             | Styling, animations, responsive design |
| JavaScript (ES6) | Game logic and DOM interactions        |


##  Architecture

```text
User Interaction
        │
        ▼
Card Click Events
        │
        ▼
State Management
(first card, second card,
moves, timer, matches)
        │
        ▼
Match Validation Logic
        │
 ┌──────┴──────┐
 │             │
Match      No Match
 │             │
 ▼             ▼
Update UI   Flip Back
 │
 ▼
Game Completion Check
 │
 ▼
Victory Modal
```


## Concepts Demonstrated

### Frontend Development

* DOM Manipulation
* Event Handling
* Dynamic Element Creation
* Responsive Design
* CSS Animations & Transitions

### JavaScript Concepts

* Closures
* Array Manipulation
* State Management
* Timers (`setInterval`)
* Event Listeners
* Conditional Rendering

### Problem Solving

* Card Matching Logic
* Shuffle Implementation
* Move Counting
* Win Condition Detection


##  Project Structure

```text
Mystic-Memory-Game/
│
├── index.html          # Application structure
├── css/
│   └── style.css       # Styling & animations
│
├── js/
│   └── script.js       # Game logic
│
└── README.md
```

## Why This Project Matters

This project demonstrates the ability to design and implement a complete interactive web application using core web technologies. It highlights proficiency in JavaScript-driven state management, responsive UI development, and user experience design—skills directly relevant to frontend and software engineering roles.
