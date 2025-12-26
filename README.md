# Daily-To---Do-list

<p align="center">
  <img src="https://i.ibb.co/0jQ9ChP/neon-banner.gif" width="100%" alt="Project Banner">
</p>

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=800&size=30&duration=3000&pause=900&color=00F0FF&center=true&vCenter=true&width=800&lines=Daily+To-Do+Planner;Smart+Daily+Task+Management+Web+App" />
</h1>

---

## Project Overview

The **Daily To-Do Planner** is a responsive, browser-based productivity web application designed to help users plan and organize their daily activities in a structured and efficient manner.  
The application supports **date-wise task management**, **priority categorization**, **hourly scheduling**, and **note-taking**, with all data stored securely in the browser using **Local Storage**.

This project is developed entirely using front-end technologies and does not require any backend, authentication, or database.

---

## Key Features

- Date-based daily planning with automatic data loading  
- Separate sections for focus tasks and priority tasks  
- Interactive to-do checklist with completion tracking  
- Hour-by-hour daily schedule planner  
- Notes section for reminders and additional information  
- Light and Dark theme toggle with saved preference  
- Automatic saving on every input change  
- Clear data option restricted to the current date  
- Fully responsive design for mobile and desktop  

---

## Tech Stack

### Front-End
![HTML5](https://img.shields.io/badge/HTML5-000?style=for-the-badge&logo=html5&logoColor=FF00FF)
![CSS3](https://img.shields.io/badge/CSS3-000?style=for-the-badge&logo=css3&logoColor=00FFFF)
![JavaScript](https://img.shields.io/badge/JavaScript-000?style=for-the-badge&logo=javascript&logoColor=39FF14)
![Bootstrap](https://img.shields.io/badge/Bootstrap-000?style=for-the-badge&logo=bootstrap&logoColor=FF00FF)

### Storage
![LocalStorage](https://img.shields.io/badge/Local%20Storage-000?style=for-the-badge&logo=googlechrome&logoColor=00FFFF)

---

## Application Workflow

- Each date is assigned a unique storage key in the format:  
  `planner-YYYY-MM-DD`
- All user inputs are saved automatically as JSON objects
- Switching the date loads the corresponding saved data
- If no data exists for a date, a fresh planner is displayed
- Theme preference is stored and restored on page reload
