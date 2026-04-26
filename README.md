# Balaji Portfolio

A modern, responsive personal portfolio website showcasing my skills, projects, and experience as an aspiring web developer.

## 🌐 Live Links

- **Live Website:** [Click Here](#)
- **Documentation:** [Click Here](#)

> *Replace the links above with your actual live link and documentation link*

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Sections](#sections)
- [Customization](#customization)
- [Contact](#contact)

---

## 📌 Overview

This is a personal portfolio website built to showcase my profile as a web developer. The site features a clean, modern design with a glass morphism UI style and smooth animations. It's fully responsive and optimized for all devices.

---

## ✨ Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Glass Morphism UI** - Modern and elegant glassmorphic design elements
- **Smooth Animations** - Fade-in animations for better user experience
- **Navigation Bar** - Fixed navbar with smooth scrolling to sections
- **Multiple Sections:**
  - Home (Hero section with profile introduction)
  - About Me (Personal background and education)
  - Skills (Technical skills with progress bars)
  - Projects (Project showcase in card format)
  - Contact (Get in touch section)
- **Bootstrap Integration** - Built with Bootstrap 5 for better component styling
- **Google Fonts** - Uses Inter font family for modern typography

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Custom styling with gradients, animations, and glass morphism
- **Bootstrap 5** - Responsive grid and component library
- **JavaScript (Vanilla)** - Intersection Observer API for scroll animations
- **Google Fonts** - Inter font family

---

## 📁 Project Structure

```
ALFIDO TASK-1/
│
├── index.html          # Main HTML file with all sections
├── styles.css          # Custom CSS styling
├── script.js           # JavaScript for animations
├── README.md           # Project documentation
│
├── bejugam-balaji.jpg  # Profile image
└── resume.pdf          # Resume download link (add this file)
```

---

## 🚀 Installation

1. **Clone or Download the Project:**
   ```bash
   git clone <repository-url>
   cd ALFIDO\ TASK-1
   ```

2. **Add Required Assets:**
   - Add your profile image as `bejugam-balaji.jpg` in the root directory
   - Add your resume as `resume.pdf` in the root directory

3. **Open in Browser:**
   - Double-click `index.html` or
   - Use a local server (recommended):
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000
     ```

---

## 💻 Usage

Simply open `index.html` in your web browser. The portfolio will load with all interactive features:

- **Navigation**: Click navbar links to scroll to different sections
- **Resume**: Click "Download Resume" button to download your resume
- **Contact**: Use the contact section to get in touch

---

## 📍 Sections

### 1. **Home/Hero Section**
- Profile image
- Name and tagline
- Call-to-action buttons (Resume download and Contact)

### 2. **About Me**
- Educational background
- Personal introduction
- Skills overview

### 3. **Skills**
- Technical skills list
- Proficiency levels displayed as progress bars
- Covered skills: HTML, CSS, Bootstrap, JavaScript, C Programming

### 4. **Projects**
- Showcase of completed projects
- Project cards with descriptions
- Easily expandable

### 5. **Contact**
- Contact information section
- Call-to-action for reaching out

---

## 🎨 Customization

### Change Profile Information:
Edit `index.html` and update:
- Your name in the `<h1>` tag
- Your tagline/description
- Educational details in the About section
- Skills and proficiency percentages

### Change Colors:
Edit `styles.css` and modify:
- `background` gradient in the `body` selector
- Primary color: `#007bff` and `#00c6ff`
- Adjust transparency and blur effects in `.glass` class

### Add New Projects:
Add project cards in the Projects section within `index.html`:
```html
<div class="col-md-4">
  <div class="card">
    <h5>Project Name</h5>
    <p>Project description</p>
    <a href="#" class="btn btn-sm btn-primary">View</a>
  </div>
</div>
```

### Update Images:
Replace `bejugam-balaji.jpg` with your own profile image (same filename)

---

## 📱 Browser Compatibility

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📈 Performance

- Lightweight and fast-loading
- Optimized for Core Web Vitals
- Intersection Observer API for efficient animations
- CDN-hosted libraries (Bootstrap, Google Fonts)

---

## 📧 Contact

- **Email:** [Add your email]
- **GitHub:** [Add your GitHub profile]
- **LinkedIn:** [Add your LinkedIn profile]

---

## 📄 License

This project is open source and available under the MIT License.

---

## 🤝 Contributing

Feel free to fork this project and submit pull requests with improvements!

---

**Last Updated:** April 26, 2026

---

*Remember to update the placeholder links at the top of this README with your actual live link and documentation link!*
