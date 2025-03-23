# 🗺️ Mapty – Workout Tracker with Maps

**Mapty** is a modern, interactive web application that lets users **track their running and cycling workouts** on a map using geolocation. Built with **Object-Oriented JavaScript**, **Leaflet.js**, and **local storage**, this project showcases deep understanding of **classes**, **inheritance**, **modular DOM structure**, and **browser APIs**.

It’s ideal for anyone learning advanced JavaScript patterns, frontend architecture, and working with maps in a web app context.

---

## 🌟 Features

### 🧠 OOP with Real-World Architecture

- Uses **ES6 classes** with inheritance
- Encapsulation of app logic in a dedicated `App` class
- Parent `Workout` class and child `Running`/`Cycling` classes
- Each workout has dynamic descriptions, pace/speed calculations, and tracking ID

### 🗺️ Interactive Mapping

- Integration with **Leaflet.js**
- Uses **Geolocation API** to load user’s current position
- Users can **click on the map** to create new workouts
- Markers for each workout rendered on the map
- Smooth **pan and zoom** to workout location when clicked in the sidebar

### 💾 Local Storage & State Management

- Workouts are **persisted** across sessions using localStorage
- Automatically re-renders stored workouts and their map markers on reload
- Easy **reset** button to clear stored workouts

### 🖼️ Responsive UI Elements

- Auto-focus input fields after map click
- Elevation/cadence field **toggles** based on selected workout type
- Fully interactive form with validation for positive numerical inputs
- Sidebar listing all workouts with emojis, units, and dynamic info

---

## 📸 Preview

Live preview (you can deploy it using Netlify or GitHub Pages):  
[https://your-mapty-demo.netlify.app/](https://your-mapty-demo.netlify.app/)

---

## 🖼️ Screenshots

![Class structure diagram](https://github.com/user-attachments/assets/image1.png)
_OOP-based app architecture: `Workout`, `Running`, `Cycling`, and `App` classes_

![User journey](https://github.com/user-attachments/assets/image2.png)
_How the user interacts with map, form, and local storage_

![UI preview](https://github.com/user-attachments/assets/image3.png)
_Map, form, and list working together seamlessly_

---

## 🧪 Technologies Used

- **HTML5** – Semantic and accessible form structure
- **CSS3** – Custom properties, layout, transitions
- **JavaScript (ES6+)** – Object-Oriented, modular code
- **Leaflet.js** – Interactive map rendering
- **Geolocation API** – Get user’s current location
- **LocalStorage API** – Persist workouts across sessions

---

## 📁 Folder Structure

```
mapty/
├── index.html         # HTML structure and layout
├── style.css          # Custom styling and responsive UI
├── script.js          # App logic (classes, map, events, storage)
├── logo.png           # App logo
├── icon.png
└── README.md          # This file
```

---

## 🚀 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/mapty.git
   ```

2. **Navigate to the project folder:**

   ```bash
   cd mapty
   ```

3. **Open `index.html` in your browser**  
   or use a live server like VS Code Live Server.

---

## 🎯 Learning Objectives

This project helped deepen understanding of:

- Object-Oriented JavaScript
- Leaflet.js integration
- Modern ES6+ syntax and class patterns
- Modular design using class methods
- DOM event handling (submit, change, click)
- Geolocation and map rendering
- Persisting data with localStorage
- Working with third-party libraries in frontend

---

## 📌 JavaScript Concepts Covered

- `class`, `constructor`, `extends`, `super`
- Event delegation (`click`, `change`, `submit`)
- `bind(this)` to preserve context
- `localStorage.setItem` / `getItem`
- DOM manipulation (`.insertAdjacentHTML`, `classList`)
- Destructuring and template literals
- Leaflet’s `.setView()`, `.bindPopup()`, and custom marker rendering

---

## 📚 Ideal For

This project is perfect for:

- Frontend developers learning real-world architecture
- Anyone diving into OOP in JavaScript
- Students working on DOM-heavy applications
- Learners who want to build map-based tools

---

## 🙋‍♂️ About the Developer

I'm **Dmytro Zuiev**, a frontend-focused developer transitioning from entrepreneurship to software engineering. I built this project as part of my self-learning and bootcamp journey to master web technologies and become job-ready in tech.

- GitHub: [@zdvman](https://github.com/zdvman)
- LinkedIn: [zdvman](https://www.linkedin.com/in/zdvman)

---

## 🧠 Acknowledgements

This project is inspired by [Jonas Schmedtmann](https://www.udemy.com/course/the-complete-javascript-course/) as part of his _Complete JavaScript Course_ curriculum.  
The idea and structure were extended and refactored for portfolio and educational demonstration purposes only.

---

## ✅ Project Status

✔️ Fully functional  
🔄 Supports real-time map interactions  
💾 Workouts persist after reload  
📱 Not responsive yet (you can improve it!)

---

## 📝 License

This project is intended for personal learning and portfolio use only.  
**Please do not redistribute or sell as your own product.**

---

Thanks for checking out Mapty!  
If you found it useful or inspiring, give it a ⭐️ on GitHub!
