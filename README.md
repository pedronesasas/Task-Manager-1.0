# 📋 Interactive Task List – Clean UI/UX

A minimalist Single Page Application (SPA) focused on fast, distraction-free daily task management.
Built with **HTML + Tailwind CSS (CDN) + Vanilla JavaScript**, with no frameworks.

---

## 🚀 Overview

This project provides a clean and fast workflow for managing tasks with:

* Instant interaction
* A text-based quick-add system
* Smooth micro-animations
* Minimalist and modern UI
* Responsive layout
* Zero dependencies besides Tailwind CDN

Perfect for learning front-end, showcasing UI/UX, and building lightweight productivity tools.

---

## ✨ Features

### ✔ Task Management

* Single-column task board
* Each task card includes:

  * Custom checkbox
  * Short ID (e.g., #145)
  * Title + details
  * Deadline with clock icon
  * Priority badge (Urgent, High, Normal, Low)
* Automatic count of pending tasks

### ✔ Quick Add Input (Smart Parsing)

Add tasks using a simple semicolon-separated format:

```
Title ; Deadline ; Priority ; Details
```

Example:

```
Meeting ; 2 PM ; High ; Room 2
```

Default behavior if fields are omitted:

* **Deadline:** “Today”
* **Priority:** “Normal”
* **Details:** empty

### ✔ Interactive States

* Click the entire card or checkbox to complete the task
* Completed state includes:

  * Lower opacity
  * Light grayscale
  * Slight scale-down
  * Line-through text

### ✔ Delete Task

* Delete button appears on hover
* Smooth removal with full re-render

### ✔ Smooth UI/UX

* Fade-in animation for list items
* Highlight animation when a task is added
* Hover shadows and soft transitions (300ms)
* Fully responsive (mobile & desktop)

---

## 🛠 Tech Stack

* **HTML5**
* **Tailwind CSS via CDN**
* **Vanilla JavaScript (ES6+)**
* **Google Fonts – Inter**
* **No frameworks, no build tools, no dependencies**

---

## 📦 Running the Project

### 🔹 Option 1 — Open Directly (simplest)

Just click the `index.html` file.
No installation required.

### 🔹 Option 2 — VS Code + Live Server (recommended)

1. Open the folder in VS Code
2. Install "Live Server" extension
3. Right-click **index.html** → *Open with Live Server*
4. App runs at `http://127.0.0.1:5500`

### 🔹 Option 3 — Local Static Server

If you have Node.js:

```bash
npx serve
```

or

```bash
npx http-server
```

---

## 🗂 Project Structure

```
/
├── index.html  # Main and only file (SPA)
└── README.md   # Project documentation
```

---

## 🎨 Design Principles

* Clean and distraction-free
* Plenty of whitespace
* Soft shadows and subtle animations
* Inter typography
* Clear visual hierarchy
* Mobile-first responsivity

---

## 🧩 Future Improvements (Optional)

* Inline editing for tasks
* LocalStorage persistence
* Multi-board version
* Drag-and-drop sorting
* Task filters (priority, completed, date)
* Themes (Light/Dark)

---

## 📜 License

This project is open-source and free to use for learning or personal projects.

✅ A version with screenshots
✅ A GIF demo for your GitHub page
✅ A shorter or more corporate version
Just tell me!
