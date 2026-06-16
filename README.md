<div align="center">

<!-- ============================================================================= -->
<!-- PREMIUM HERO SECTION WITH ANIMATIONS -->
<!-- ============================================================================= -->

<svg viewBox="0 0 1400 450" xmlns="http://www.w3.org/2000/svg" width="100%" height="auto" style="max-width: 100%; margin: 40px 0;">
  <defs>
    <!-- Background Gradients -->
    <radialGradient id="bgRadial" cx="50%" cy="50%" r="70%">
      <stop offset="0%" style="stop-color:#1E3A5F;stop-opacity:0.3"/>
      <stop offset="100%" style="stop-color:#0F172A;stop-opacity:0"/>
    </radialGradient>
    
    <linearGradient id="bgLinear" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0F172A"/>
      <stop offset="50%" style="stop-color:#0F1e3e"/>
      <stop offset="100%" style="stop-color:#0F172A"/>
    </linearGradient>
    
    <!-- Title Gradient -->
    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00E5FF"/>
      <stop offset="50%" style="stop-color:#7C3AED"/>
      <stop offset="100%" style="stop-color:#00E5FF"/>
    </linearGradient>
    
    <!-- Box Gradients -->
    <linearGradient id="boxGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00E5FF;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#0F172A;stop-opacity:0.5"/>
    </linearGradient>
    
    <linearGradient id="boxGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#7C3AED;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#0F172A;stop-opacity:0.5"/>
    </linearGradient>
    
    <linearGradient id="boxGrad3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00E5FF;stop-opacity:0.15"/>
      <stop offset="100%" style="stop-color:#0F172A;stop-opacity:0.5"/>
    </linearGradient>
    
    <!-- Animations -->
    <style>
      @keyframes float { 0%, 100% { transform: translateY(0px); } 50% { transform: translateY(-15px); } }
      @keyframes pulse { 0%, 100% { opacity: 0.6; } 50% { opacity: 1; } }
      @keyframes rotate { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }
      
      .floating { animation: float 4s ease-in-out infinite; transform-origin: center; }
      .pulsing { animation: pulse 3s ease-in-out infinite; }
      .rotating { animation: rotate 20s linear infinite; transform-origin: center; }
    </style>
    
    <!-- Glow Filter -->
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    
    <filter id="softGlow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Background -->
  <rect width="1400" height="450" fill="url(#bgLinear)"/>
  <rect width="1400" height="450" fill="url(#bgRadial)"/>
  
  <!-- Animated Background Elements -->
  <g class="floating" style="animation-delay: 0s;">
    <circle cx="150" cy="100" r="70" fill="none" stroke="#00E5FF" stroke-width="1" opacity="0.15"/>
    <circle cx="150" cy="100" r="50" fill="none" stroke="#00E5FF" stroke-width="0.5" opacity="0.1"/>
  </g>
  
  <g class="floating" style="animation-delay: 1s;">
    <circle cx="1250" cy="350" r="90" fill="none" stroke="#7C3AED" stroke-width="1" opacity="0.15"/>
    <circle cx="1250" cy="350" r="60" fill="none" stroke="#7C3AED" stroke-width="0.5" opacity="0.1"/>
  </g>
  
  <!-- Grid Background -->
  <g stroke="#00E5FF" stroke-width="0.5" opacity="0.05">
    <line x1="0" y1="112" x2="1400" y2="112"/>
    <line x1="0" y1="224" x2="1400" y2="224"/>
    <line x1="0" y1="336" x2="1400" y2="336"/>
    <line x1="350" y1="0" x2="350" y2="450"/>
    <line x1="700" y1="0" x2="700" y2="450"/>
    <line x1="1050" y1="0" x2="1050" y2="450"/>
  </g>
  
  <!-- Decorative Accent Lines -->
  <line x1="200" y1="80" x2="450" y2="80" stroke="#00E5FF" stroke-width="2" opacity="0.3"/>
  <line x1="950" y1="80" x2="1200" y2="80" stroke="#7C3AED" stroke-width="2" opacity="0.3"/>
  
  <!-- Main Title -->
  <text x="700" y="110" font-size="96" font-weight="900" text-anchor="middle" fill="url(#titleGrad)" font-family="monospace" filter="url(#glow)" letter-spacing="2">TOUM001</text>
  
  <!-- Subtitle -->
  <text x="700" y="185" font-size="32" text-anchor="middle" fill="#00E5FF" font-family="monospace" font-weight="700" opacity="0.95">Full-Stack Developer</text>
  <text x="700" y="225" font-size="32" text-anchor="middle" fill="#7C3AED" font-family="monospace" font-weight="700" opacity="0.95">AI/ML Enthusiast</text>
  
  <!-- Description -->
  <text x="700" y="265" font-size="16" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif">Building innovative solutions with modern technologies</text>
  
  <!-- Separator Line Premium -->
  <g opacity="0.5">
    <line x1="300" y1="285" x2="1100" y2="285" stroke="url(#titleGrad)" stroke-width="2.5"/>
    <circle cx="700" cy="285" r="4" fill="#00E5FF" opacity="0.8"/>
  </g>
  
  <!-- Stat Cards with Enhanced Styling -->
  <g id="stat-cards">
    <!-- Card 1 -->
    <g class="pulsing" style="animation-delay: 0s;">
      <rect x="80" y="320" width="340" height="110" rx="16" fill="url(#boxGrad1)" stroke="#00E5FF" stroke-width="2.5"/>
      <rect x="90" y="330" width="320" height="90" rx="14" fill="none" stroke="#00E5FF" stroke-width="0.5" opacity="0.2"/>
      
      <!-- Icon Circle -->
      <circle cx="130" cy="360" r="20" fill="none" stroke="#00E5FF" stroke-width="2" opacity="0.6"/>
      <text x="130" y="368" font-size="20" text-anchor="middle" fill="#00E5FF">📦</text>
      
      <!-- Text -->
      <text x="250" y="355" font-size="18" font-weight="bold" fill="#00E5FF">10+</text>
      <text x="250" y="375" font-size="13" fill="#A0AEC0">Projects Created</text>
      <text x="250" y="395" font-size="11" fill="#A0AEC0" opacity="0.7">Production Ready</text>
    </g>
    
    <!-- Card 2 -->
    <g class="pulsing" style="animation-delay: 0.6s;">
      <rect x="530" y="320" width="340" height="110" rx="16" fill="url(#boxGrad2)" stroke="#7C3AED" stroke-width="2.5"/>
      <rect x="540" y="330" width="320" height="90" rx="14" fill="none" stroke="#7C3AED" stroke-width="0.5" opacity="0.2"/>
      
      <!-- Icon Circle -->
      <circle cx="580" cy="360" r="20" fill="none" stroke="#7C3AED" stroke-width="2" opacity="0.6"/>
      <text x="580" y="368" font-size="20" text-anchor="middle" fill="#7C3AED">💻</text>
      
      <!-- Text -->
      <text x="700" y="355" font-size="18" font-weight="bold" fill="#7C3AED">5+</text>
      <text x="700" y="375" font-size="13" fill="#A0AEC0">Languages Mastered</text>
      <text x="700" y="395" font-size="11" fill="#A0AEC0" opacity="0.7">Expert Level</text>
    </g>
    
    <!-- Card 3 -->
    <g class="pulsing" style="animation-delay: 1.2s;">
      <rect x="980" y="320" width="340" height="110" rx="16" fill="url(#boxGrad3)" stroke="#00E5FF" stroke-width="2.5"/>
      <rect x="990" y="330" width="320" height="90" rx="14" fill="none" stroke="#00E5FF" stroke-width="0.5" opacity="0.2"/>
      
      <!-- Icon Circle -->
      <circle cx="1030" cy="360" r="20" fill="none" stroke="#00E5FF" stroke-width="2" opacity="0.6"/>
      <text x="1030" y="368" font-size="20" text-anchor="middle" fill="#00E5FF">🚀</text>
      
      <!-- Text -->
      <text x="1150" y="355" font-size="18" font-weight="bold" fill="#00E5FF">Always</text>
      <text x="1150" y="375" font-size="13" fill="#A0AEC0">Innovating & Learning</text>
      <text x="1150" y="395" font-size="11" fill="#A0AEC0" opacity="0.7">Tech Driven</text>
    </g>
  </g>
</svg>

<br/>

<!-- GitHub Badges -->
<div style="display: flex; gap: 12px; justify-content: center; flex-wrap: wrap;">
  <a href="https://github.com/Toum001">
    <img alt="GitHub followers" src="https://img.shields.io/github/followers/Toum001?style=flat-square&labelColor=1E293B&color=00E5FF&logo=github&logoColor=00E5FF"/>
  </a>
  <a href="https://github.com/Toum001?tab=stars">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/Toum001?style=flat-square&labelColor=1E293B&color=7C3AED&logo=github&logoColor=7C3AED"/>
  </a>
  <a href="https://github.com/Toum001">
    <img alt="Profile Views" src="https://komarev.com/ghpvc/?username=Toum001&style=flat-square&labelColor=1E293B&color=00E5FF"/>
  </a>
</div>

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
