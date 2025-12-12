# animated-website-created-using-SheryJS
# 🌿 Sustainability & Eco-Friendly Animated Website

A modern, smooth-scroll eco-themed webpage built using **HTML, CSS, JavaScript**, **GSAP**, **Shery.js**, and **Locomotive Scroll**.
This project focuses on immersive visuals, smooth animations, and a clean design around sustainability.

---

## 🚀 Live Demo

(You can add your deployed link here)

---

## 📌 Features

### ✨ UI & Animations

* Smooth scrolling using **Locomotive Scroll**
* Advanced text & image animations with **Shery.js**
* GSAP-powered transitions, fade-ins & timelines
* Parallax-style movement and dynamic effects
* Animated image distortion effects

### 🌱 Eco-Friendly Theme

* Sections dedicated to *sustainability*, *harmony*, *equilibrium*
* Media-rich content (images + video background)
* Clear typography with custom font integration

### 🧩 Modular Structure

* Clean folder structure
* Fully responsive layout (desktop-first)
* Easy to extend for future pages or components

---

## 🖥️ Tech Stack

| Technology               | Purpose                      |
| ------------------------ | ---------------------------- |
| **HTML5**                | Structure of the website     |
| **CSS3**                 | Design, layout, custom fonts |
| **JavaScript (Vanilla)** | Animations & interactions    |
| **GSAP + ScrollTrigger** | Smooth motion effects        |
| **Shery.js**             | Text & image distortion      |
| **Locomotive Scroll**    | Smooth scrolling             |
| **RemixIcons**           | Icons                        |

---

## 📂 Project Structure

```
project-folder/
│── index.html
│── style.css
│── script.js
│
├── images/
│   ├── pinkgreenplant.jpg
│   ├── pinkplant.jpg
│   ├── sea.jpg
│   ├── cloud.jpg
│   ├── bottle.jpg
│   ├── bottle2.jpg
│   ├── bluegirl.jpg
│   ├── grass.jpg
│   └── shaljam.jpg
│
└── fonts/
    └── NimbusSanL-Reg.otf
```

---

## 🛠️ Installation & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
```

### 2. Navigate to the Folder

```bash
cd your-repo-name
```

### 3. Open the Project

* Open `index.html` directly
* Or use Live Server for best performance

---

## 📸 Screenshots

(You can add images here later using the Markdown format below)

```
![Preview](./images/preview.png)
```

---

## 🎯 Sections Explained

### **1️⃣ Home Section**

* Navigation bar
* Hero section with animated headings
* Image distortion + text animations

### **2️⃣ Motive Section**

* Sustainability message
* Custom image spans embedded inside text

### **3️⃣ Picture Grid**

* Two artistic image cards
* GSAP float-in effects

### **4️⃣ Banner & Future Section**

* Side-by-side images
* Full-width looping video background
* "Join the movement" CTA button

---

## 📜 Code Highlights

### ⭐ Smooth Navigation Animation

```js
gsap.from(".nlink", {
  stagger: 0.2,
  y: 10,
  opacity: 0,
  duration: 1,
  ease: Power2,
});
```

### ⭐ Shery.js Text Animation

```js
Shery.textAnimate("#headings h1", {
  style: 2,
  y: 10,
  delay: 0.1,
  duration: 2,
});
```

### ⭐ Smooth Scroll

```js
const scroll = new LocomotiveScroll({
  el: document.querySelector("#main"),
  smooth: true,
});
```

---


## 📜 License

This project is open-source and available under the **MIT License**.

---

## 🧑‍💻 Author

**Geetanshu**
Feel free to connect on GitHub or LinkedIn.
