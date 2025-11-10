# 🎓 UniHub – University Dashboard Frontend

UniHub is a modern, responsive university dashboard built entirely with **HTML** and **Tailwind CSS**.  
It provides a clean and visually appealing interface for students to manage their academic life — from tracking courses and events to managing library loans and personal settings.  

This project focuses purely on **frontend design** — there is **no backend or dynamic functionality** implemented.

---

## 🚀 Live Overview

UniHub simulates a unified student portal with the following sections:

- **Dashboard** – Displays today’s schedule, attendance overview, and upcoming assignments.  
- **Courses** – Lists enrolled courses with course type, instructor details, and quick access links.  
- **Library Services** – Allows users to search, book study rooms, and manage borrowed books.  
- **Calendar** – A monthly calendar view for lectures, events, and deadlines.  
- **Profile & Settings** – User profile management, dark mode toggle, and notification preferences.

---

## 🖼️ Interface Preview

### 📊 Dashboard
![Dashboard Preview](https://github.com/roshaanmehar/UniHub/blob/master/dashboard.png)

### 📚 Courses
![Courses Preview](https://github.com/roshaanmehar/UniHub/blob/master/courses.png)

### 🏛️ Library Services
![Library Services Preview](https://github.com/roshaanmehar/UniHub/blob/master/libraryservices.png)

### 🗓️ Calendar
![Calendar Preview](https://github.com/roshaanmehar/UniHub/blob/master/calendarevents.png)

### 👤 Profile
![Profile Preview](https://github.com/roshaanmehar/UniHub/blob/master/profile.png)

---

## 🧩 Project Structure

Each HTML file represents a single page of the UniHub interface.  
All assets and layouts are designed to maintain visual consistency using Tailwind’s **dark mode** and **glassmorphism** design techniques.

UniHub/
│
├── dashboard.html # Main dashboard page
├── dashboard.png
│
├── courses.html # Courses and instructors
├── courses.png
│
├── libraryServices.html # Library interface
├── libraryservices.png
│
├── calendarEvents.html # Event calendar view
├── calendarevents.png
│
├── profile.html # Profile and settings
└── profile.png


---

## 🛠️ Technologies Used

- **HTML5** – Page structure and semantic layout  
- **Tailwind CSS** – Styling and responsive design  
- **Google Fonts (Inter)** – Clean and modern typography  
- **Material Symbols** – For consistent and scalable icons  
- **Glassmorphism** – Soft blur effects for elegant visual depth  
- **Dark Mode Support** – Toggle-ready UI with Tailwind’s `dark:` classes  

---

## 💡 Design Highlights

- Fully **responsive layout** built using Tailwind’s grid and flex utilities  
- Subtle **background gradients** and blurred colour spots for depth  
- Interactive **hover effects** and visual cues  
- Modular and scalable component structure (cards, buttons, sidebars)  
- Smooth **dark/light theme** transitions  

---

## 📂 How to View

1. Clone or download this repository:
   ```bash
   git clone https://github.com/roshaanmehar/UniHub.git
2. Open any .html file in your browser:
    open dashboard.html
    or simply drag and drop it into a browser window.
No installation or build tools required — it’s a pure HTML frontend.

📜 Future Enhancements
- This static prototype can easily be extended into a full-stack application with:
- Authentication and user profiles
- Course and event data fetched dynamically via an API
- Persistent user preferences (dark mode, notifications)
- Integration with a backend such as Node.js, Flask, or Firebase