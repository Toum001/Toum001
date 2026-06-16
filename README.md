<div align="center">

<!-- ============================================================================= -->
<!-- HERO SECTION WITH ANIMATED SVG -->
<!-- ============================================================================= -->

<svg viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg" width="100%" height="auto" style="max-width: 100%; margin: 30px 0; display: block;">
  <defs>
    <!-- Gradients -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0F172A"/>
      <stop offset="50%" style="stop-color:#1a2a4a"/>
      <stop offset="100%" style="stop-color:#0F172A"/>
    </linearGradient>
    
    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00E5FF"/>
      <stop offset="100%" style="stop-color:#7C3AED"/>
    </linearGradient>
    
    <linearGradient id="box1Grad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#00E5FF;stop-opacity:0.2"/>
      <stop offset="100%" style="stop-color:#00E5FF;stop-opacity:0"/>
    </linearGradient>
    
    <linearGradient id="box2Grad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#7C3AED;stop-opacity:0.2"/>
      <stop offset="100%" style="stop-color:#7C3AED;stop-opacity:0"/>
    </linearGradient>
    
    <linearGradient id="box3Grad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#00E5FF;stop-opacity:0.2"/>
      <stop offset="100%" style="stop-color:#00E5FF;stop-opacity:0"/>
    </linearGradient>
    
    <filter id="glow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Fond principal -->
  <rect width="1200" height="320" fill="url(#bgGrad)"/>
  
  <!-- Lignes de grille en arrière-plan -->
  <g stroke="#00E5FF" stroke-width="0.5" opacity="0.08">
    <line x1="0" y1="80" x2="1200" y2="80"/>
    <line x1="0" y1="160" x2="1200" y2="160"/>
    <line x1="0" y1="240" x2="1200" y2="240"/>
  </g>
  
  <!-- Formes décoratives flottantes -->
  <circle cx="80" cy="60" r="45" fill="none" stroke="#00E5FF" stroke-width="1.5" opacity="0.2"/>
  <circle cx="80" cy="60" r="30" fill="none" stroke="#00E5FF" stroke-width="1" opacity="0.15"/>
  
  <circle cx="1120" cy="260" r="55" fill="none" stroke="#7C3AED" stroke-width="1.5" opacity="0.2"/>
  <circle cx="1120" cy="260" r="35" fill="none" stroke="#7C3AED" stroke-width="1" opacity="0.15"/>
  
  <!-- Rectangles décoratifs -->
  <rect x="50" y="270" width="60" height="30" fill="none" stroke="#00E5FF" stroke-width="1.5" opacity="0.15" transform="rotate(-15 80 285)"/>
  <rect x="1090" y="20" width="70" height="40" fill="none" stroke="#7C3AED" stroke-width="1.5" opacity="0.15" transform="rotate(25 1125 40)"/>
  
  <!-- Titre principal -->
  <text x="600" y="75" font-size="72" font-weight="900" text-anchor="middle" fill="url(#titleGrad)" font-family="monospace" filter="url(#glow)">TOUM001</text>
  
  <!-- Sous-titre -->
  <text x="600" y="130" font-size="26" text-anchor="middle" fill="#00E5FF" font-family="monospace" font-weight="bold" opacity="0.95">Full-Stack Developer • AI/ML Enthusiast</text>
  
  <!-- Description -->
  <text x="600" y="160" font-size="15" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif">Building innovative solutions with modern tech stack</text>
  
  <!-- Ligne décorative premium -->
  <g opacity="0.4">
    <line x1="200" y1="175" x2="1000" y2="175" stroke="#00E5FF" stroke-width="2"/>
    <line x1="200" y1="177" x2="1000" y2="177" stroke="#7C3AED" stroke-width="1" opacity="0.6"/>
  </g>
  
  <!-- Stat boxes avec gradients -->
  <g id="stat-boxes">
    <!-- Box 1 -->
    <rect x="100" y="205" width="310" height="85" rx="12" fill="url(#box1Grad)" stroke="#00E5FF" stroke-width="2.5" opacity="0.9"/>
    <rect x="105" y="210" width="300" height="75" rx="10" fill="none" stroke="#00E5FF" stroke-width="1" opacity="0.3"/>
    <text x="255" y="240" font-size="16" font-weight="bold" text-anchor="middle" fill="#00E5FF" font-family="Arial, sans-serif">10+ PROJECTS</text>
    <text x="255" y="262" font-size="12" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif" opacity="0.9">Created &amp; Deployed</text>
    <text x="255" y="278" font-size="10" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif" opacity="0.6">Production Ready</text>
    
    <!-- Box 2 -->
    <rect x="445" y="205" width="310" height="85" rx="12" fill="url(#box2Grad)" stroke="#7C3AED" stroke-width="2.5" opacity="0.9"/>
    <rect x="450" y="210" width="300" height="75" rx="10" fill="none" stroke="#7C3AED" stroke-width="1" opacity="0.3"/>
    <text x="600" y="240" font-size="16" font-weight="bold" text-anchor="middle" fill="#7C3AED" font-family="Arial, sans-serif">5+ LANGUAGES</text>
    <text x="600" y="262" font-size="12" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif" opacity="0.9">Expert Level</text>
    <text x="600" y="278" font-size="10" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif" opacity="0.6">Mastered Concepts</text>
    
    <!-- Box 3 -->
    <rect x="790" y="205" width="310" height="85" rx="12" fill="url(#box3Grad)" stroke="#00E5FF" stroke-width="2.5" opacity="0.9"/>
    <rect x="795" y="210" width="300" height="75" rx="10" fill="none" stroke="#00E5FF" stroke-width="1" opacity="0.3"/>
    <text x="945" y="240" font-size="16" font-weight="bold" text-anchor="middle" fill="#00E5FF" font-family="Arial, sans-serif">TECH DRIVEN</text>
    <text x="945" y="262" font-size="12" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif" opacity="0.9">Always Learning</text>
    <text x="945" y="278" font-size="10" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif" opacity="0.6">Innovation Focused</text>
  </g>
</svg>

<!-- Real GitHub Badges -->
<a href="https://github.com/Toum001">
  <img alt="GitHub followers" src="https://img.shields.io/github/followers/Toum001?style=flat-square&labelColor=1E293B&color=00E5FF&logo=github"/>
</a>

<a href="https://github.com/Toum001?tab=stars">
  <img alt="GitHub User's stars" src="https://img.shields.io/github/stars/Toum001?style=flat-square&labelColor=1E293B&color=7C3AED&logo=github"/>
</a>

---

</div>

<div align="center">

## 🎯 ABOUT ME

</div>

<div align="left">

```
$ whoami
├─ Full-Stack Developer passionate about clean code
├─ AI/ML enthusiast exploring advanced algorithms
├─ Open-source contributor & tech community builder
├─ Problem solver with a focus on scalability
└─ Always exploring new technologies
```

As a versatile developer, I specialize in building efficient, scalable applications across **frontend** and **backend** ecosystems. My journey spans from low-level systems programming with **C/C++** to high-level application development with **JavaScript**, **React**, and **Node.js**. I'm driven by the challenge of solving complex problems and creating solutions that make a real impact.

**Currently focused on**: Full-stack development, cloud architecture, and emerging AI/ML technologies.

</div>

---

<div align="center">

## 🛠️ TECH STACK

</div>

### 🎨 **Frontend Development**
<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=1E293B)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black&labelColor=1E293B)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white&labelColor=1E293B)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=1E293B)

</div>

### ⚙️ **Backend Development**
<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white&labelColor=1E293B)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white&labelColor=1E293B)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white&labelColor=1E293B)
![Odoo](https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logoColor=white&labelColor=1E293B)

</div>

### 🗄️ **Databases & Architecture**
<div align="center">

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=1E293B)
![MongoDB](https://img.shields.io/badge/MongoDB-13AA52?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=1E293B)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white&labelColor=1E293B)

</div>

### 🛠️ **Tools & DevOps**
<div align="center">

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=1E293B)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=1E293B)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=1E293B)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black&labelColor=1E293B)

</div>

---

<div align="center">

## 📊 GITHUB DASHBOARD

</div>

<div align="center">

<!-- GitHub Stats -->
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Toum001&show_icons=true&theme=nightowl&hide_border=true&bg_color=0F172A&title_color=00E5FF&icon_color=7C3AED&text_color=A0AEC0&hide=contribs)

<!-- Top Languages -->
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Toum001&layout=compact&theme=nightowl&hide_border=true&bg_color=0F172A&title_color=00E5FF&text_color=A0AEC0)

<!-- GitHub Streak -->
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=Toum001&theme=nightowl&hide_border=true&background=0F172A&stroke=00E5FF&ring=7C3AED&fire=00E5FF&currStreakNum=00E5FF&sideNums=A0AEC0&currStreakLabel=7C3AED&sideLabels=A0AEC0&dates=A0AEC0)

</div>

---

<div align="center">

## 🚀 FEATURED PROJECTS

</div>

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=Toum001&repo=Minishell&theme=nightowl&hide_border=true&bg_color=1E293B&title_color=00E5FF&text_color=A0AEC0&icon_color=7C3AED" alt="Minishell"/>
      <br/>
      <strong>A lightweight Unix shell implementation</strong>
      <br/>
      <sub>C • Systems Programming • CLI</sub>
    </td>
  </tr>
</table>

---

<div align="center">

## 🎯 CURRENTLY WORKING ON

</div>

<div align="center">

```
┌─────────────────────────────────────────────────┐
│  🔬 Advanced Full-Stack Projects                │
│  🤖 Machine Learning & AI Implementations       │
│  🌐 Cloud Architecture & Microservices          │
│  📚 Open-source Contributions                   │
└─────────────────────────────────────────────────┘
```

</div>

---

<div align="center">

## 🏆 ACHIEVEMENTS

</div>

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=Toum001&theme=nightowl&no-frame=true&row=1&column=7&title=Followers,Stars,Commits,Issues,PullRequests,Repositories)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

<div align="center">

## 📈 CONTRIBUTION ACTIVITY

</div>

<div align="center">

[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=Toum001&theme=nightowl&hide_border=true&bg_color=0F172A&color=00E5FF&line=7C3AED&point=7C3AED)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

<!-- 
=============================================================================
SNAKE ANIMATION - UNCOMMENT TO ACTIVATE
=============================================================================

<div align="center">

## 🐍 COMMIT SNAKE

![Snake animation](https://github.com/Toum001/Toum001/blob/output/github-contribution-grid-snake.svg)

</div>

To enable this animation:
1. Go to https://github.com/Toum001/Toum001/actions
2. Enable GitHub Actions
3. The snake animation will auto-generate from your contribution graph

=============================================================================
-->

---

<div align="center">

## 📬 GET IN TOUCH

</div>

<div align="center">

<a href="mailto:rakotomalalazotoavina@gmail.com">
  <img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1E293B"/>
</a>

<a href="https://github.com/Toum001">
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=1E293B"/>
</a>

<a href="https://linkedin.com/in/toum001">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1E293B"/>
</a>

</div>

---

<div align="center">

## 💡 PHILOSOPHY

> "Code is not just instructions for machines. It's communication with the future—a message to developers who will read, maintain, and build upon your work."

**Let's create something amazing together!** 🚀

<br/>

<sub>Last updated: 2026-06-14</sub> | <sub>Crafted with ❤️ by Toum001</sub>

</div>
