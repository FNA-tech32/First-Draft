# First Draft 🚀

[![Website Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](#)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](#)
[![Formspree](https://img.shields.io/badge/Forms-Formspree-FF5722)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **First Draft** is a modern, responsive, and feature-rich digital portfolio and creative studio showcase website. Built with semantic HTML5, modern CSS3, and vanilla JavaScript, it delivers smooth animations, theme personalization, interactive project galleries, and complete contact channels.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Live Sections](#-live-sections)
- [Tech Stack](#-tech-stack)
- [Project Directory Structure](#-project-directory-structure)
- [Quick Start / Local Setup](#-quick-start--local-setup)
- [Customization Guide](#-customization-guide)
  - [Brand Name Configuration](#1-brand-name-configuration)
  - [Contact & Alternative Details](#2-contact--alternative-details)
  - [Formspree Integration](#3-formspree-integration)
  - [Theme Colors & CSS Variables](#4-theme-colors--css-variables)
  - [Adding Projects](#5-adding-projects)
- [Contact Details](#-contact-details)
- [License](#-license)

---

## 🌟 Overview

**First Draft** is designed to provide an engaging digital presence for designers, full-stack developers, and creative agencies. It combines visual appeal with performant, dependency-free vanilla code. Visitors can explore project showcases, review academic and professional timelines, read technical articles, view a dynamic masonry gallery, test responsive layouts across all viewports, and reach out through dedicated primary and alternative communication channels.

---

## ⚡ Key Features

- **Branded Experience**: Centered around the **First Draft** brand identity with cohesive typography, color hierarchy, and custom accents.
- **Dark & Light Mode**: Built-in theme switch with persistent state stored in the browser's `localStorage`.
- **Custom Dynamic Cursor**: Interactive trailing cursor follower that dynamically scales and highlights over clickable elements.
- **Translucent / Glassmorphism Navbar**: Fixed navigation with blur backdrop, smooth scroll anchors, and an animated mobile hamburger drawer.
- **Animated Hero Section**: Ambient floating geometric shapes with dynamic keyframe animations and immediate Call-to-Action (CTA).
- **Interactive Skill Bars**: Animated on-scroll percentage meters displaying core competencies.
- **Dual Timelines**:
  - *Education Timeline*: Displays academic achievements and degrees.
  - *Work Experience Timeline*: Highlights roles, internships, and corporate contributions.
- **Leadership & Community Hub**: Cards detailing organizational leadership, public speaking, mentorship, and key soft skills.
- **Filterable Projects Grid**: Instant client-side categorization (Web Design, App Design, Branding/Random) with live demo buttons and GitHub repository links.
- **Smart Masonry Image Gallery**: Calculates image aspect ratios via JavaScript to assign CSS Grid row spans dynamically without gaps.
- **Automated Testimonials Carousel**: Rotating client feedback slider with touch/click pagination dots and auto-advance timer.
- **Dual-Channel Contact Hub**:
  - **Primary Contact Card**: Official business email, direct telephone line, and studio headquarters.
  - **Alternative Contact Card**: Backup email, WhatsApp / alternate number, availability hours, and fast turnaround guarantee.
  - **Social Connect**: Direct links to GitHub, LinkedIn, Twitter/X, and LeetCode.
  - **AJAX Contact Form**: Formspree backend, floating labels, client-side email format validation, and hidden spam honeypot trap.
- **Status Feedback Pages**: Branded `thank-you.html` and `error.html` with context-aware error messaging.
- **Back-to-Top Floating Trigger**: Smooth scroll-to-top button appearing after passing 300px scroll threshold.

---

## 🖥️ Live Sections

| Section | Description |
| :--- | :--- |
| **Header** | Logo (`FirstDraft`), navigation links, dark/light toggle, mobile hamburger. |
| **Hero** | Greeting, role, brand tagline, CTA button, social media badges, animated shapes. |
| **About** | Professional narrative, embedded Dribbble video clip, skill progress meters, resume actions. |
| **Education** | Academic background timeline (Master's, Bachelor's, Senior Secondary). |
| **Experience** | Professional experience timeline (Full-Stack Intern at StaxTech, Digital Marketer). |
| **Leadership** | Community leadership roles (XDev Club President, Wild Cats Clan, DG Sentinels). |
| **Blog** | Curated articles on UI design, web accessibility, CSS Grid vs Flexbox. |
| **Projects** | Filterable portfolio cards featuring live demo and GitHub repository buttons. |
| **Gallery** | Dynamic masonry layout displaying creative photography and design pieces. |
| **Testimonials** | Client testimonials carousel with auto-sliding timer and dot navigation. |
| **Contact** | Dual-channel contact details (Primary & Alternative) + Formspree form. |
| **Footer** | Branded logo, summary tagline, quick links, social links, and copyright notice. |

---

## 🧰 Tech Stack

- **Markup**: [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) (Semantic structure, meta tags, honeypot inputs)
- **Styling**: [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) (CSS Variables, Flexbox, CSS Grid, Keyframes, Media queries)
- **Scripting**: [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) (ES6+, DOM manipulation, Event delegation, LocalStorage)
- **Icons**: [Font Awesome 6.4.0](https://fontawesome.com/)
- **Typography**: [Google Fonts (Poppins)](https://fonts.google.com/specimen/Poppins)
- **Form Backend**: [Formspree](https://formspree.io/)

---

## 📁 Project Directory Structure

```text
First-Draft/
│
├── index.html                  # Main website landing page
├── style.css                   # Global styles, variables, dark mode & media queries
├── script.js                   # Interactive logic: cursor, theme, filters, slider, masonry
├── error.html                  # Branded error page for failed form submissions
├── thank-you.html              # Branded confirmation page for successful submissions
├── README.md                   # Complete project documentation
├── Gaurav_Mishra_Resume.pdf    # Resume PDF asset for download and preview
│
└── img/                        # Image assets
    ├── banner.jpg              # Hero section banner visual
    ├── 1.jpg                   # UI/UX design sample
    ├── 2.jpg                   # Development setup visual
    ├── 3.jpg                   # Creative workspace visual
    ├── 4.jpg                   # Nature inspiration visual
    ├── 5.jpg                   # Technology & workstation tools
    ├── 6.jpg                   # Art & experimental design
    └── 7.jpg - 15.jpg          # Additional gallery photography & showcase assets
```

---

## 🚀 Quick Start / Local Setup

Because **First Draft** is built purely with vanilla web standards, no build tools, package managers, or compilers are required.

### Method 1: Direct File Launch
Simply double-click `index.html` or open it directly in any modern web browser (Chrome, Firefox, Safari, Edge, Brave).

### Method 2: VS Code Live Server
1. Open the `First-Draft` folder in Visual Studio Code.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and select **"Open with Live Server"**.

### Method 3: Python Built-in HTTP Server
If you have Python installed:
```bash
# Navigate to the project directory
cd First-Draft

# Python 3.x
python -m http.server 3000
```
Open your browser at `http://localhost:3000`.

### Method 4: Node.js `npx serve`
```bash
cd First-Draft
npx serve .
```

---

## ⚙️ Customization Guide

### 1. Brand Name Configuration
The project is configured under the brand name **First Draft**. To adjust the branding:
- In `index.html`:
  - `<title>First Draft | Creative Design & Web Development</title>`
  - Header logo: `<a href="#" class="logo">First<span>Draft</span></a>`
  - Footer logo: `<a href="#" class="footer-logo">First<span>Draft</span></a>`
  - Copyright: `© 2025 First Draft. All rights reserved.`
- In `thank-you.html` & `error.html`:
  - Update title and return buttons (`← Back to First Draft`).

### 2. Contact & Alternative Details
Contact information is organized into **Primary** and **Alternative** detail cards inside the `#contact` section in `index.html`:

```html
<!-- Primary Contact -->
<a href="mailto:contact@firstdraft.com">contact@firstdraft.com</a>
<a href="tel:+15552345678">+1 (555) 234-5678</a>

<!-- Alternative Details -->
<a href="mailto:firstdraft.agency@gmail.com">firstdraft.agency@gmail.com</a>
<a href="https://wa.me/15559876543">+1 (555) 987-6543</a>
```

### 3. Formspree Integration
To connect the contact form to your own email:
1. Register a free form at [Formspree.io](https://formspree.io/).
2. In `index.html`, update the `action` attribute on `<form id="contactForm">`:
   ```html
   <form id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### 4. Theme Colors & CSS Variables
Modify the core color scheme in `style.css` under the `:root` pseudo-class:

```css
:root {
  --primary: #6c5ce7;    /* Main brand color (purple/indigo) */
  --secondary: #a29bfe;  /* Secondary accent */
  --dark: #2d3436;       /* Dark mode background & text color */
  --light: #f5f6fa;      /* Light mode background */
  --accent: #fd79a8;     /* Accent pink/coral for badges & highlights */
  --transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}
```

### 5. Adding Projects
To add a new project card inside `.project-grid`:

```html
<div class="project-card" data-category="web"> <!-- Categories: web, app, branding -->
  <div class="project-img">
    <img src="img/your-project.jpg" alt="Project Title" />
  </div>
  <div class="project-info">
    <h3>Project Title</h3>
    <p>Brief description of what you built and the problems it solves.</p>
    <div class="project-tags">
      <span class="project-tag">HTML</span>
      <span class="project-tag">CSS</span>
      <span class="project-tag">JavaScript</span>
    </div>
    <div class="project-links">
      <a href="https://your-demo-url.com" target="_blank" class="project-link"><i class="fas fa-eye"></i> Live Demo</a>
      <a href="https://github.com/your-username/repo" target="_blank" class="project-link"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>
```

---

## 📬 Contact Details

Feel free to connect or reach out regarding projects, design inquiries, or technical collaborations:

### 🌟 Primary Contact
- **Brand / Studio**: First Draft
- **Primary Email**: [contact@firstdraft.com](mailto:contact@firstdraft.com)
- **Direct Phone**: [+1 (555) 234-5678](tel:+15552345678)
- **Location**: San Francisco, CA & Worldwide (Remote)

### 🔄 Alternative Details
- **Alternative Email**: [firstdraft.agency@gmail.com](mailto:firstdraft.agency@gmail.com)
- **WhatsApp / Alternate Phone**: [+1 (555) 987-6543](https://wa.me/15559876543)
- **Availability / Working Hours**: Monday – Friday, 9:00 AM – 6:00 PM EST (Response within 24 hours)

### 🌐 Social & Developer Profiles
- **Author / Founder**: Gaurav Mishra
- **GitHub**: [github.com/Gauravmishra01](https://github.com/Gauravmishra01)
- **LinkedIn**: [linkedin.com/in/gauravmishra77](https://www.linkedin.com/in/gauravmishra77/)
- **Twitter / X**: [x.com/GauravMishra077](https://x.com/GauravMishra077)
- **LeetCode**: [leetcode.com/u/Gaurav_Mishra01](https://leetcode.com/u/Gaurav_Mishra01/)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — free to use for personal and commercial projects.
