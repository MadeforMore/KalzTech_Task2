# KalzTech_Task2
A dynamic To-Do application built using pure JavaScript that uses DOM manipulation, events, and browser localStorage for permanent task storage.

## You can test it here :-  https://madeformore.github.io/KalzTech_Task2/
# Aryan To-Do App 📝

A dynamic To-Do application built using **pure JavaScript** that demonstrates **DOM manipulation**, **event handling**, and **permanent data storage using browser localStorage**, without using any external libraries or copied UI.

---

## Project Overview

Aryan To-Do App is a simple yet powerful task management application created as part of an internship task focused on **DOM & Events**.  
The application allows users to add and delete tasks dynamically, and it stores tasks permanently using the browser’s **localStorage**, so tasks remain available even after refreshing or closing the browser.

The main goal of this project is to understand how JavaScript interacts with HTML elements, handles user events, and manages data storage on the client side.

---

## Key Features

- Add tasks dynamically using DOM manipulation
- Delete tasks using event listeners
- Permanent storage using `localStorage`
- Tasks remain after page refresh or browser close
- Clean and custom UI (no copied design)
- No libraries or frameworks used

---

## Project Structure

todo-app/
├── index.html → Application structure
├── style.css → Styling and UI design
├── script.js → Logic, DOM, events, and storage
└── README.md → Project documentation

yaml
Copy code

---

## Technologies Used

- **HTML** – Defines the structure of the application  
- **CSS** – Provides styling and layout  
- **JavaScript** – Handles logic, DOM manipulation, events, and storage  

---

## How the Application Works

### 1. User Interface (HTML)

The HTML file contains:
- An input field to type a task
- A button to add the task
- A list element to display tasks dynamically

Buttons are connected to JavaScript using event listeners instead of inline logic.

---

### 2. Styling (CSS)

CSS is used to:
- Center the application on the screen
- Create a clean and modern card layout
- Add hover effects to buttons
- Ensure readability and a custom UI design

The UI is intentionally simple and original to meet internship guidelines.

---

### 3. Logic and DOM Manipulation (JavaScript)

JavaScript performs the following actions:

- Reads user input from the text field
- Validates input to avoid empty tasks
- Creates new list elements (`<li>`) dynamically
- Appends tasks to the task list using the DOM
- Removes tasks when the delete button is clicked

Event listeners are used to handle user actions like adding and deleting tasks.

---

### 4. Permanent Storage using localStorage

To make the application persistent, **localStorage** is used.

- Tasks are stored as an array in localStorage
- Data is saved in JSON format
- Tasks are loaded automatically when the page reloads

This ensures:
- Tasks are not lost on refresh
- No backend or database is required
- The solution remains beginner-friendly

---

## Why localStorage is Used

- Provides permanent storage in the browser
- Requires no server or database
- Allowed under “No libraries” rule
- Ideal for learning client-side storage

---

## How to Run the Project

1. Download or clone the project
2. Open the project folder
3. Open `index.html` in any web browser
4. Add, delete, and manage tasks

---

## Learning Outcomes

- Understanding DOM manipulation
- Using JavaScript event listeners
- Client-side data storage with localStorage
- Writing clean and maintainable code
- Separating UI and logic

---

## Evaluation Readiness

This project fully satisfies the task requirements:
- ✔ DOM & Events used
- ✔ Add task functionality implemented
- ✔ Permanent storage included
- ✔ No libraries used
- ✔ Custom UI
- ✔ Clean code structure

---

## Author

**Aryan Thite**  
Internship Task – DOM & Events

---
