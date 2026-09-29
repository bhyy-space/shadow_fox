# Bhavesh Singh — Developer Portfolio

A modern, responsive developer portfolio website built to showcase my software engineering journey, technical skills, projects, competitive programming experience, and an interactive AI assistant.

> **Software Engineer & GATE Qualifier**
> B.Tech CS Student | MERN Stack | Data Structures & Algorithms

---

## 🌐 Overview

This portfolio is designed as a single-page personal website with a dark, modern UI and interactive sections.

It highlights:

* Software engineering profile
* Technical skills and technologies
* 250+ LeetCode problems
* GATE 2026 qualification
* Featured development projects
* Interactive AI Assistant
* Project idea generator
* Contact and GitHub information

The website is built primarily with **HTML, Tailwind CSS, and JavaScript**, with Google's Gemini API powering the AI assistant.

---

## ✨ Features

### 👨‍💻 Personal Portfolio

A responsive portfolio landing page featuring:

* Hero section
* About/statistics section
* Technical skills
* Featured projects
* Contact section
* Responsive navigation

### 🤖 Interactive AI Assistant

The portfolio includes an AI-powered chat interface that acts as a virtual assistant for the portfolio.

Visitors can ask questions about:

* Technical skills
* GATE 2026 achievement
* LeetCode experience
* Projects
* Development journey
* Portfolio technologies

The assistant is powered by the **Google Gemini API**.

### 💡 AI Project Brainstormer

A dedicated quick action allows visitors to generate technically challenging project ideas based on the portfolio owner's technology stack and interests.

### 🎨 Modern UI

The interface uses:

* Dark theme
* Glassmorphism cards
* Gradient backgrounds
* Smooth scrolling
* Hover animations
* Responsive layouts
* Lucide icons
* Tailwind CSS utilities

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6+)
* React.js — listed as a core technology/project skill
* Tailwind CSS

### Backend / Development

* Node.js
* Express.js
* REST API Design
* SQL
* MVC Architecture

### Programming

* C
* C++
* Python
* JavaScript
* Data Structures & Algorithms

### AI

* Google Gemini API
* Gemini 2.5 Flash Preview

### Libraries / CDNs

* [Tailwind CSS](https://tailwindcss.com/)
* [Lucide Icons](https://lucide.dev/)
* Google Fonts — Inter

---

## 📊 Profile Highlights

| Metric            | Details                 |
| ----------------- | ----------------------- |
| LeetCode          | 250+ problems           |
| GATE              | Qualified — 2026        |
| Coding Experience | 2+ years                |
| Primary Stack     | MERN                    |
| Degree            | B.Tech Computer Science |

---

## 🚀 Featured Projects

### 🎵 Spotify Clone

A full-stack music streaming platform inspired by modern music-streaming interfaces.

**Highlights:**

* Dynamic playlists
* High-fidelity user interface
* Full-stack architecture
* Express.js backend
* React frontend

**Technologies:**

`React` `Node.js` `Express.js`

---

### ✨ Interactive Animations Library

A collection of optimized web animations focused on creating smooth and responsive user interactions.

**Highlights:**

* CSS-based animations
* Smooth transitions
* Performance-focused implementation
* Optimized CSS keyframes
* Targeted 60 FPS animation performance

**Technologies:**

`HTML5` `CSS3`

---

## 🤖 AI Assistant Architecture

The AI assistant communicates directly with the Gemini API from the client-side JavaScript application.

### Request Flow

```text
User
  │
  ▼
Portfolio Chat UI
  │
  ▼
JavaScript handleChat()
  │
  ▼
callGemini()
  │
  ▼
Google Gemini API
  │
  ▼
AI-generated response
  │
  ▼
Chat UI
```

The assistant uses a predefined system prompt containing portfolio information such as education, skills, projects, achievements, and interests.

---


## 🔑 Gemini API Configuration

The AI assistant uses the Gemini API.

The current implementation expects an API key in the JavaScript configuration:

```javascript
const apiKey = "";
const GEMINI_MODEL = "gemini-2.5-flash-preview-09-2025";
```

For local testing, configure your Gemini API key appropriately.

### ⚠️ Security Note

**Do not commit a real API key to a public GitHub repository.**

For a production deployment, API requests should preferably be routed through a secure backend/serverless function so that the API key is not exposed to visitors.

---

## 📁 Project Structure

A minimal version of the project can be organized as:

```text
Shadow_fox/
│
├── portfolio.html
├── README.md


The current portfolio is largely self-contained inside the HTML file, including:

* Page structure
* Styling
* JavaScript
* AI assistant logic
* Interactive functionality

---

## 📱 Responsive Design

The portfolio is designed to adapt to different screen sizes.

It includes responsive layouts for:

* Desktop
* Tablet
* Mobile

Tailwind CSS responsive utilities are used throughout the interface.

---

## 🔮 Future Improvements

Potential improvements include:

* [ ] Move Gemini API calls to a secure backend
* [ ] Add real GitHub repository links
* [ ] Add live project demos
* [ ] Add downloadable resume
* [ ] Add detailed experience/education timeline
* [ ] Add project screenshots
* [ ] Add dark/light theme switching
* [ ] Add SEO metadata
* [ ] Add Open Graph social preview
* [ ] Add analytics
* [ ] Deploy through GitHub Pages / Vercel / Netlify
* [ ] Add a dedicated backend for the AI assistant

---

## 📬 Contact

**Bhavesh Singh**

* GitHub: [github.com/bhyy-sapce](https://github.com/bhyy-space)
* Email: [bhyy2004@gmail.com](mailto:bhyy2004@gmail.com)

I'm currently looking for **software engineering internship opportunities**.

---

## 📄 License

This project is intended as a personal portfolio website.

If you want to reuse significant portions of the design or content, please contact the author first.

---

## ⭐ Acknowledgements

Built using:

* Tailwind CSS
* Lucide Icons
* Google Fonts
* Google Gemini API

---

