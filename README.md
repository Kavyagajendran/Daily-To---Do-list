# Daily-To---Do-list

Overview

The Daily To-Do Planner is a responsive, browser-based web application that helps users organize and manage their daily activities efficiently. It provides structured sections for prioritizing tasks, scheduling hourly plans, and maintaining notes. All data is stored locally in the browser using Local Storage, enabling date-wise task persistence without requiring a backend or database.

This project is built using HTML, CSS, Bootstrap, and JavaScript, making it lightweight, fast, and suitable for offline use.

Features

Date-based task planning with automatic data loading

Separate sections for:

Focus tasks

Must-get-done tasks

General to-do list with checkboxes

Optional tasks

Hourly time planner

Notes

Automatic saving of all inputs

Local Storage–based persistence (date-wise)

Light and Dark theme support

Responsive design for desktop and mobile devices

Controlled data clearing (only for the current date)

Technologies Used
Technology	Description
HTML5	Structure and layout
CSS3	Styling
Bootstrap 5	Responsive design
JavaScript	Application logic
Local Storage	Client-side data persistence
Project Structure
Daily-To-Do-Planner/
│
├── index.html      # Main application file
├── style.css       # Custom styles
├── README.md       # Documentation

How It Works

Each selected date is assigned a unique storage key in the format:
planner-YYYY-MM-DD

All user inputs are stored as JSON objects in the browser’s Local Storage

When the date changes:

Existing data is loaded automatically

If no data exists, a fresh planner is displayed

Theme preference (Light/Dark) is stored separately and applied on page load

Getting Started

Clone or download the repository

Open index.html in any modern web browser

Start planning your day

No installation, login, or internet connection is required.

Responsiveness

Built using Bootstrap grid system

Works smoothly on:

Desktop

Tablet

Mobile devices

Data Privacy

All data remains in the user’s browser

No server-side storage or external APIs

Ensures full privacy and offline accessibility

Author

Kavya Gajendran
Daily To-Do Planner
2025

Future Enhancements

Weekly and monthly calendar view

Export tasks as PDF

Task completion analytics

Cloud sync with backend integration

User authentication
