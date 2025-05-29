# Jeevan Gowda - Personal Portfolio Website

## 🌟 Overview
This is a modern, single-page personal portfolio website for **Jeevan Gowda**, designed to showcase educational background, skills, projects, and experience.

Inspired by the clean and dynamic aesthetics of **Villo Framer templates**, this website features:
- Dual light/dark theme functionality
- Engaging animations
- Fully responsive layout

---

## ✨ Features

- **Responsive Design:** Optimized for desktop, tablet, and mobile devices.
- **Dual Theme:**
  - Light Mode: White background with blue accents.
  - Dark Mode: Dark background with yellow accents.
  - Theme toggle saved in `localStorage`.
- **Modern UI Inspired by Villo:**
  - Clean layout, bold typography
  - Signature SVG logo
  - Smooth and engaging animations
- **Dynamic Hero Section:**
  - Animated “JEEVAN GOWDA” letter-by-letter reveal
  - Circular image overlay
  - Scroll-down indicator
- **Sections:**
  - About Me
  - Education
  - Skills
  - Projects (e.g., [mathcreations.in](https://mathcreations.in), Employee Management System)
  - Experience (e.g., Infosys Internship)
  - Certificates (Udemy, LinkedIn Learning)
  - Contact
- **Interactive Elements:**
  - Scroll-triggered animations
  - Hover effects
  - Scrolling text marquee in the footer
- **Mobile Navigation:** Hamburger menu on small screens

---

## 🛠️ Technologies Used

- **HTML5** – Structure
- **Tailwind CSS** – Utility-first styling (via CDN)
- **Vanilla JavaScript** – Interactions:
  - Theme toggle
  - Scroll-based animations (`IntersectionObserver`)
  - Hero text animation
  - Mobile menu toggle
- **Google Fonts:** "DM Sans", "Big Shoulders Display", and "Inter"
- **SVGs** – Signature and icons

---

## 🚀 How to Use

1. **Download/Clone** the repository.
2. **Open** `portfolio_jeevan_gowda.html` in any modern web browser.
3. **No build tools required** – everything runs directly in the browser (Tailwind via CDN, inline JS/CSS).

---

## 🎨 Customization Guide

### ✅ Hero Image:
Replace the `<img>` `src` in `.hero-image-overlay` with your profile photo.

### ✅ Signature Logo:
Edit the `<svg class="logo-signature-svg">` with your custom SVG. Use `fill="currentColor"` or `stroke="currentColor"` for theme adaptation.

### ✅ Contact Email:
Update the email link in the Contact section:
```html
<a href="mailto:your-email@example.com">Say Hello</a>
````

### ✅ Sections to Edit:

* **About Me:** Update `.about-text`
* **Education:** Update `.content-entry` elements
* **Skills:** Replace names, icons, and descriptions in `.skill-item-villo`
* **Projects:** Change titles, links, and descriptions in `#projects`
* **Experience:** Add real-world or internship experience
* **Certificates:** List platforms like Udemy, LinkedIn, etc.
* **Social Links:** Replace GitHub/LinkedIn URLs in `<footer>`

### ✅ Footer Marquee:

Edit text inside `.marquee-content` spans.

### ✅ Advanced: Change Theme Colors

Edit the CSS variables near the top of the `<style>` block:

```css
--theme-accent: rgb(...);
```

---

## 🙏 Credits & Inspiration

* Inspired by **Apple's design language**
* Typography and design influenced by **Narthan**
* Powered by **Tailwind CSS**
* Placeholder icons (replace with Heroicons, Phosphor Icons, etc.)

---

> 💡 Tip: Fork this repo and start customizing your own personal brand portfolio today!

```

---

Let me know if you’d like a badge, GitHub Pages deployment instructions, or license section added too!
```
