<div align="center">

<!-- ============================================================================= -->
<!-- HERO SECTION WITH ANIMATED SVG -->
<!-- ============================================================================= -->

<svg width="100%" height="auto" viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg" style="max-width: 100%; margin-bottom: 20px;">
  <defs>
    <style>
      @keyframes pulse { 0%, 100% { opacity: 0.5; } 50% { opacity: 1; } }
      @keyframes glow { 0%, 100% { filter: drop-shadow(0 0 5px #00E5FF); } 50% { filter: drop-shadow(0 0 20px #7C3AED); } }
      @keyframes float { 0%, 100% { transform: translateY(0px); } 50% { transform: translateY(-10px); } }
      .pulse-bg { animation: pulse 3s ease-in-out infinite; }
      .glow-text { animation: glow 2s ease-in-out infinite; }
      .float-icon { animation: float 3s ease-in-out infinite; }
    </style>
    <linearGradient id="heroGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#00E5FF;stop-opacity:0.2" />
      <stop offset="50%" style="stop-color:#7C3AED;stop-opacity:0.1" />
      <stop offset="100%" style="stop-color:#00E5FF;stop-opacity:0.05" />
    </linearGradient>
    <filter id="neon" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Fond -->
  <rect width="1200" height="400" fill="#0F172A"/>
  <rect width="1200" height="400" fill="url(#heroGradient)"/>

  <!-- Grille d'arrière-plan -->
  <g stroke="#00E5FF" stroke-width="1" opacity="0.1">
    <line x1="0" y1="100" x2="1200" y2="100"/>
    <line x1="0" y1="200" x2="1200" y2="200"/>
    <line x1="0" y1="300" x2="1200" y2="300"/>
    <line x1="300" y1="0" x2="300" y2="400"/>
    <line x1="600" y1="0" x2="600" y2="400"/>
    <line x1="900" y1="0" x2="900" y2="400"/>
  </g>

  <!-- Cercles décorateurs animés -->
  <circle cx="150" cy="80" r="60" fill="none" stroke="#00E5FF" stroke-width="2" opacity="0.3" class="pulse-bg"/>
  <circle cx="1050" cy="320" r="80" fill="none" stroke="#7C3AED" stroke-width="2" opacity="0.3" class="pulse-bg"/>

  <!-- Titre principal -->
  <text x="600" y="120" font-size="80" font-weight="bold" text-anchor="middle" fill="#00E5FF" font-family="'Courier New', monospace" class="glow-text" filter="url(#neon)">
    TOUM001
  </text>

  <!-- Sous-titre -->
  <text x="600" y="180" font-size="32" text-anchor="middle" fill="#00E5FF" font-family="'Courier New', monospace" opacity="0.9">
    Full-Stack Developer • AI/ML Enthusiast
  </text>

  <!-- Description -->
  <text x="600" y="230" font-size="18" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif">
    Building innovative solutions with modern tech
  </text>

  <!-- Lignes décoratives -->
  <line x1="350" y1="260" x2="850" y2="260" stroke="#00E5FF" stroke-width="2" opacity="0.5"/>
  <line x1="350" y1="270" x2="850" y2="270" stroke="#7C3AED" stroke-width="1" opacity="0.3"/>

  <!-- Stats badges -->
  <g>
    <rect x="300" y="300" width="220" height="70" rx="10" fill="#1E293B" stroke="#00E5FF" stroke-width="2" opacity="0.9"/>
    <text x="410" y="325" font-size="16" text-anchor="middle" fill="#00E5FF" font-family="Arial, sans-serif" font-weight="bold">10+ Projects</text>
    <text x="410" y="350" font-size="13" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif">Created & Deployed</text>

    <rect x="560" y="300" width="220" height="70" rx="10" fill="#1E293B" stroke="#7C3AED" stroke-width="2" opacity="0.9"/>
    <text x="670" y="325" font-size="16" text-anchor="middle" fill="#7C3AED" font-family="Arial, sans-serif" font-weight="bold">5+ Languages</text>
    <text x="670" y="350" font-size="13" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif">Expert Level</text>

    <rect x="820" y="300" width="220" height="70" rx="10" fill="#1E293B" stroke="#00E5FF" stroke-width="2" opacity="0.9"/>
    <text x="930" y="325" font-size="16" text-anchor="middle" fill="#00E5FF" font-family="Arial, sans-serif" font-weight="bold">Tech Driven</text>
    <text x="930" y="350" font-size="13" text-anchor="middle" fill="#A0AEC0" font-family="Arial, sans-serif">Always Learning</text>
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
