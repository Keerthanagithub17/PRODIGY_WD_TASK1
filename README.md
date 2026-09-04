# PRODIGY_WD_TASK1 – Interactive Navigation Menu

## 📌 Project Overview

This project is **Task 1** of my Web Development Internship at **Prodigy Infotech**.

The objective of this task is to create an **interactive navigation menu** that remains fixed on the screen and changes its appearance based on user interaction, such as hovering over menu items and scrolling the webpage.

The project is built using **HTML, CSS, and JavaScript**.

---

## 🎯 Task Objective

Create an interactive navigation menu that:

* Remains fixed at the top of the webpage
* Is visible while scrolling
* Changes style when the user scrolls
* Provides hover effects on menu items
* Uses JavaScript to add interactivity
* Provides a responsive user experience

---

## ✨ Features

### 🔹 Fixed Navigation Bar

The navigation menu remains fixed at the top of the webpage while the user scrolls.

### 🔹 Scroll Interaction

When the user scrolls down the page, JavaScript dynamically changes the navigation bar by adding:

* Background color
* Box shadow
* Different visual styling

### 🔹 Hover Effects

When the user hovers over a navigation item:

* The text color changes
* An animated underline appears
* Smooth CSS transitions are applied

### 🔹 Smooth Scrolling

Navigation links smoothly scroll to their corresponding sections.

### 🔹 Responsive Design

The navigation menu and webpage layout adapt to different screen sizes, including mobile devices.

---

## 🛠️ Technologies Used

* **HTML5** – Structure and content
* **CSS3** – Styling, animations, transitions, and responsive design
* **JavaScript** – Scroll detection and dynamic navigation behavior
* **Git & GitHub** – Version control and project hosting
* **GitHub Pages** – Live project deployment

---

## 📂 Project Structure

```text
PRODIGY_WD_TASK1/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## ⚙️ How It Works

### HTML

The navigation menu is created using semantic HTML elements such as:

```html
<nav>
    <div class="logo">MyWebsite</div>

    <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>
```

### CSS

CSS is used to make the navigation menu fixed:

```css
#navbar {
    position: fixed;
    top: 0;
    width: 100%;
}
```

Hover effects are implemented using the `:hover` pseudo-class.

### JavaScript

JavaScript listens for the user's scroll event:

```javascript
window.addEventListener("scroll", function () {
    if (window.scrollY > 50) {
        navbar.classList.add("scrolled");
    } else {
        navbar.classList.remove("scrolled");
    }
});
```

When the page is scrolled more than 50 pixels, the `scrolled` class is added to the navigation bar, changing its appearance.

---

## 📋 Task Requirements Satisfied

| Requirement                 | Status      |
| --------------------------- | ----------- |
| Interactive navigation menu | ✅ Completed |
| Fixed navigation position   | ✅ Completed |
| Visible while scrolling     | ✅ Completed |
| Hover interaction           | ✅ Completed |
| Scroll-based style change   | ✅ Completed |
| HTML structure              | ✅ Completed |
| CSS styling                 | ✅ Completed |
| JavaScript interactivity    | ✅ Completed |
| Responsive design           | ✅ Completed |
| GitHub deployment           | ✅ Completed |

---

## 🌐 Live Demo

**[View Live Demo](https://keerthanagithub17.github.io/PRODIGY_WD_TASK1/)**

---

## 💻 GitHub Repository

**Repository:**
`https://github.com/keerthanagithub17/PRODIGY_WD_TASK1`

---

## 📸 Project Highlights

The project demonstrates:

* Fixed navigation
* Interactive hover effects
* Scroll-triggered navigation styling
* Smooth transitions
* Responsive webpage sections

---

## 📚 Learning Outcomes

Through this task, I gained practical experience in:

* Creating navigation menus using HTML
* Styling navigation components using CSS
* Working with CSS transitions and hover effects
* Handling browser scroll events using JavaScript
* Dynamically modifying CSS classes using JavaScript
* Creating responsive layouts
* Deploying a frontend project using GitHub Pages
* Managing projects using Git and GitHub

---

## 👩‍💻 Internship

**Web Development Intern – Prodigy Infotech**

**Task:** Task 1 – Interactive Navigation Menu

---

## ⭐ Acknowledgement

This project was developed as part of my **Web Development Internship at Prodigy Infotech**.

---

## 📄 License

This project is created for educational and internship purposes.
