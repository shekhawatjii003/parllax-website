# Adventure Parallax Website

A visually engaging landing page demonstrating **Pure CSS Parallax Scrolling** effects. This project showcases two different methods of creating depth and motion in web design without using JavaScript.

## 🌟 Overview

This project is a practice in advanced CSS styling. It features a "Hero" section that uses CSS 3D transforms (`perspective` and `translateZ`) to create a multi-layered depth effect, and content sections that utilize `background-attachment: fixed` for a smooth scrolling reveal effect.

## ✨ Features

* **3D Parallax Header:** A composite header using a background layer, a foreground layer, and text moving at different speeds to create a 3D depth illusion.
* **Fixed Background Scrolling:** Content sections (Biking, Paragliding, Surfing) featuring static background images that stay in place while text scrolls over them.
* **Responsive Design:** Uses flexible units and viewport settings to adapt to different screen sizes.
* **Clean UI:** Minimalist dark theme typography.
* **Zero JavaScript:** All visual effects are achieved using only HTML5 and CSS3.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure.
* **CSS3:**
    * `transform-style: preserve-3d`
    * `perspective`
    * `translateZ` (for depth scaling)
    * `background-attachment: fixed`
    * Flexbox (for layout alignment)

## 📂 Project Structure

```text
/
├── parallax.html        # Main HTML structure
├── parallax.css         # Stylesheet containing the parallax logic
├── background.png       # Rear layer for the hero section
├── foreground.png       # Front layer (e.g., trees/rocks) for the hero section
├── sport-1.jpg          # Image for Biking section
├── sport-2.jpg          # Image for Paragliding section
└── sport-3.jpg          # Image for Surfing section
