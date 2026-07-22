# MyPortfolio

# Madhavi Katakam · Data Portfolio

[![Portfolio](https://img.shields.io/badge/Portfolio-Live-brightgreen)](https://your-portfolio-url.com)
[![GitHub](https://img.shields.io/badge/GitHub-madhavikatakam2007-181717?logo=github)](https://github.com/madhavikatakam2007)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Madhavi%20Katakam-0A66C2?logo=linkedin)](https://www.linkedin.com/in/madhavi-katakam-6001b7374)

## 📊 Overview

A modern, interactive portfolio website showcasing my journey as an **Aspiring Data Analyst** and **B.Tech CSE student**. Built with a focus on visual storytelling, this portfolio highlights my skills, projects, and professional journey through an immersive dark-themed interface with particle animations.

**🔗 Live Demo:** [View Portfolio](#) *(Add your deployed URL here)*

## ✨ Features

### 🎨 Visual Design
- **Dynamic Particle Background** - Interactive canvas particles creating an immersive cosmic feel
- **Gradient Hero Section** - Animated geometric shapes with rotating role titles
- **Responsive Layout** - Fully optimized for desktop, tablet, and mobile devices
- **Dark Theme** - Modern dark interface with purple/blue gradient accents

### 📱 Core Sections
1. **Hero Section**
   - Animated role rotation (Data Scientist → ML Engineer → AI Enthusiast)
   - Call-to-action buttons for projects and contact
   - Professional tagline with key skills

2. **About Me**
   - Comprehensive professional summary
   - Aspirations and educational background
   - Leadership and communication highlights

3. **Skills**
   - **Progress Rings** - Visual proficiency indicators for:
     - Python (92%)
     - SQL (88%)
     - Machine Learning (85%)
     - Power BI (78%)
     - Spark (70%)
     - NLP (75%)
   - **Skill Tags** - Complete tech stack including:
     - Python, SQL, Power BI, Scikit-learn
     - HTML/CSS, Git & GitHub, VS Code, PyCharm
     - Windows/Linux, SciPy, TensorFlow, Jupyter Notebook
     - Deep Neural Networks, Flask, Streamlit, MS Excel, MS Office

4. **My Journey Timeline**
   - **Apex Planet** (June 2026 – August 2026)
     - 2-month Data Analytics Internship
     - Industry-recognized training in Data Analytics & AI
   - **Graduation** (2024 – 2028)
     - B.Tech CSE @ RGUKT Srikakulam IIIT
     - CGPA: 8.3
   - **Pre-University Course** (2022 – 2024)
     - Junior & Secondary Education
     - CGPA: 8.6
   - **SSC** (2021 – 2022)
     - Score: 582/600
     - Multi-lingual proficiency (English, Telugu, Hindi)

5. **Featured Projects**
   - 🎬 **Movie Recommendation System**
     - Python, SQL, Power BI
     - Content-based & collaborative filtering
     - [View Code](https://github.com/madhavikatakam2007/Movie-Recommendation-and-Analytics-System/blob/main/movie-recommendation.sql)
   
   - 🌱 **AgroSense AI – Plant Disease Monitoring**
     - FastAPI, TensorFlow (CNN), React, IoT
     - Full-stack AI platform with real-time monitoring
     - [View Code](https://github.com/madhavikatakam2007/plantguard.ai)
   
   - 💳 **Predicting Credit Default**
     - Python, Scikit-learn, Pandas
     - 150K records with 12%+ ROC-AUC improvement
     - [View Code](https://github.com/madhavikatakam2007/credit_scoring)

6. **Contact Section**
   - Email: madhavikatam2007@gmail.com
   - Location: Annavaram, Andhra Pradesh
   - Available for Projects & Internships
   - Interactive contact form with demo submission

### 🛠 Technical Features
- **3D Hover Effects** - Cards and timeline items respond to mouse movement
- **Smooth Scrolling** - Navigation with animated transitions
- **Progress Tracking** - Back-to-top button with scroll progress indicator
- **Form Validation** - Client-side form handling with feedback
- **Particle System** - Performance-optimized canvas animations
- **SVG Graphics** - Custom skill progress rings with gradients

## 🚀 Technologies Used

### Frontend
- **HTML5** - Semantic structure
- **CSS3** - Custom styles with Flexbox/Grid
- **JavaScript** - Vanilla JS for interactivity
- **Font Awesome 6** - Icon library

### Design Features
- CSS Custom Properties for theming
- CSS Animations & Keyframes
- Responsive Design with Media Queries
- Backdrop Filters & Glass Effects
- SVG Linear Gradients

## 📦 Installation

### Local Development
1. **Clone the repository**
   ```bash
   git clone https://github.com/madhavikatakam2007/portfolio.git
   cd portfolio
   ```

2. **Open the HTML file**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```

### Deployment Options
- **GitHub Pages**
  ```bash
  # Push to main branch
  git add .
  git commit -m "Deploy portfolio"
  git push origin main
  # Enable GitHub Pages in repository settings
  ```

- **Netlify**
  - Drag and drop the folder to Netlify dashboard
  - Or connect GitHub repository for automatic deployments

- **Vercel**
  ```bash
  npm install -g vercel
  vercel
  ```

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── README.md           # Documentation
└── assets/             # (Optional) Images and resources
    └── (no external images used - all via Picsum)
```

## 🔧 Customization Guide

### Update Personal Information
```html
<!-- Hero Section -->
<h1>Your Name</h1>

<!-- About Section -->
<p class="about-full">Your professional summary</p>

<!-- Contact Details -->
<div class="item"><i class="fas fa-envelope"></i> <span>your.email@domain.com</span></div>
```

### Modify Skill Percentages
```javascript
// In the <script> section
const skills = [
    { name: 'Python', pct: 92 },  // Change this value
    { name: 'SQL', pct: 88 },     // to update ring
    // ...
];
```

### Add/Remove Projects
```html
<div class="project-card">
    <div class="project-img" style="background-image:url('YOUR_IMAGE_URL')"></div>
    <div class="project-meta">
        <h3>Project Title</h3>
        <p>Project description</p>
        <div class="tech-tags">
            <span>Tech 1</span>
            <span>Tech 2</span>
        </div>
        <div class="project-links">
            <a href="GITHUB_URL" target="_blank"><i class="fab fa-github"></i></a>
        </div>
    </div>
</div>
```

### Update Timeline Events
```html
<div class="timeline-box">
    <div class="box-content">
        <span class="year">YEAR – YEAR</span>
        <div class="title">Your Title</div>
        <div class="sub">Your description</div>
        <div class="cgpa-badge">CGPA: X.X</div>
    </div>
</div>
```

## 🌟 Performance & SEO

- **Lightweight** - Single HTML file under 50KB
- **No External Dependencies** - Only Font Awesome CDN
- **Semantic HTML** - Proper heading hierarchy
- **Lazy Loading** - Picsum images load on-demand
- **Meta Tags** - Viewport settings for mobile optimization

## 📱 Responsive Design

| Device | Breakpoint | Optimization |
|--------|------------|--------------|
| Desktop | > 1024px | Full layout with side-by-side sections |
| Tablet | 768px - 1024px | Adjusted grid layouts |
| Mobile | < 768px | Single column, adjusted typography, collapsible timeline |

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📬 Contact

- **Email**: madhavikatam2007@gmail.com
- **GitHub**: [@madhavikatakam2007](https://github.com/madhavikatakam2007)
- **LinkedIn**: [Madhavi Katakam](https://www.linkedin.com/in/madhavi-katakam-6001b7374)

---

## 🙏 Acknowledgments

- Font Awesome for beautiful icons
- Picsum Photos for placeholder images
- The open-source community for inspiration

---

**Made with 💜 and Data** | © 2026 Madhavi Katakam
