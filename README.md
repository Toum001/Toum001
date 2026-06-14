<div align="center">

<svg width="400" height="300" viewBox="0 0 400 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes rotate { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }
      @keyframes float { 0%, 100% { transform: translateY(0px); } 50% { transform: translateY(-20px); } }
      @keyframes glow { 0%, 100% { opacity: 0.3; } 50% { opacity: 1; } }
      @keyframes pulse { 0%, 100% { r: 4px; } 50% { r: 7px; } }
      @keyframes shimmer { 0% { stroke-dashoffset: 1000; } 100% { stroke-dashoffset: 0; } }
      
      .rotating { animation: rotate 20s linear infinite; transform-origin: 200px 150px; }
      .floating { animation: float 3s ease-in-out infinite; }
      .glowing { animation: glow 2s ease-in-out infinite; }
      .pulsing { animation: pulse 2s ease-in-out infinite; }
      .shimmering { animation: shimmer 3s linear infinite; stroke-dasharray: 1000; }
    </style>
    
    <!-- Gradients -->
    <radialGradient id="bgGradient" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:0.1" />
      <stop offset="100%" style="stop-color:#764ba2;stop-opacity:0.05" />
    </radialGradient>
    
    <linearGradient id="mainGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#667eea" />
      <stop offset="50%" style="stop-color:#764ba2" />
      <stop offset="100%" style="stop-color:#f093fb" />
    </linearGradient>
    
    <linearGradient id="accentGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#f093fb" />
      <stop offset="100%" style="stop-color:#667eea" />
    </linearGradient>
  </defs>
  
  <!-- Fond -->
  <rect width="400" height="300" fill="#0a0e27"/>
  <circle cx="200" cy="150" r="200" fill="url(#bgGradient)"/>
  
  <!-- Cercles d'arrière-plan -->
  <circle class="rotating" cx="200" cy="150" r="150" fill="none" stroke="url(#mainGradient)" stroke-width="1" opacity="0.3"/>
  <circle class="rotating" cx="200" cy="150" r="120" fill="none" stroke="url(#accentGradient)" stroke-width="1" opacity="0.2" style="animation-direction: reverse;"/>
  
  <!-- Points orbitaux qui tournent -->
  <g class="rotating">
    <circle cx="200" cy="30" r="6" fill="#667eea" class="pulsing" opacity="0.8"/>
    <circle cx="320" cy="150" r="6" fill="#764ba2" class="pulsing" opacity="0.8" style="animation-delay: 0.5s;"/>
    <circle cx="200" cy="270" r="6" fill="#f093fb" class="pulsing" opacity="0.8" style="animation-delay: 1s;"/>
    <circle cx="80" cy="150" r="6" fill="#667eea" class="pulsing" opacity="0.8" style="animation-delay: 1.5s;"/>
  </g>
  
  <!-- Lignes de connexion animées -->
  <g opacity="0.4" stroke="url(#mainGradient)" stroke-width="1.5" class="shimmering">
    <line x1="200" y1="150" x2="200" y2="30"/>
    <line x1="200" y1="150" x2="320" y2="150"/>
    <line x1="200" y1="150" x2="200" y2="270"/>
    <line x1="200" y1="150" x2="80" y2="150"/>
  </g>
  
  <!-- Formes flottantes -->
  <g class="floating" opacity="0.6">
    <polygon points="200,80 220,110 180,110" fill="url(#mainGradient)" opacity="0.7"/>
  </g>
  
  <g class="floating" style="animation-delay: 0.5s;" opacity="0.6">
    <polygon points="280,140 310,160 280,180 250,160" fill="url(#accentGradient)" opacity="0.7"/>
  </g>
  
  <g class="floating" style="animation-delay: 1s;" opacity="0.6">
    <polygon points="200,220 220,250 180,250" fill="url(#mainGradient)" opacity="0.7" transform="rotate(180 200 235)"/>
  </g>
  
  <!-- Halo central -->
  <circle cx="200" cy="150" r="40" fill="none" stroke="url(#mainGradient)" stroke-width="2" opacity="0.5" class="glowing"/>
  <circle cx="200" cy="150" r="35" fill="none" stroke="url(#accentGradient)" stroke-width="1" opacity="0.3"/>
  
  <!-- Texte principal -->
  <text x="200" y="165" font-size="48" font-weight="bold" text-anchor="middle" fill="url(#mainGradient)" font-family="Arial, sans-serif" letter-spacing="2">TOUM001</text>
  
  <!-- Texte secondaire -->
  <text x="200" y="195" font-size="14" text-anchor="middle" fill="#667eea" opacity="0.8" font-family="Arial, sans-serif">Developer • Innovation</text>
  
  <!-- Points de lumière supplémentaires -->
  <circle cx="120" cy="80" r="3" fill="#f093fb" class="glowing" opacity="0.6"/>
  <circle cx="280" cy="80" r="3" fill="#667eea" class="glowing" opacity="0.6" style="animation-delay: 0.5s;"/>
  <circle cx="280" cy="220" r="3" fill="#764ba2" class="glowing" opacity="0.6" style="animation-delay: 1s;"/>
  <circle cx="120" cy="220" r="3" fill="#f093fb" class="glowing" opacity="0.6" style="animation-delay: 1.5s;"/>
</svg>

# 👋 Bienvenue sur mon profil !

### Je suis **Toum001** 🚀

---

</div>

<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/Toum001?style=social)](https://github.com/Toum001)
[![GitHub stars](https://img.shields.io/github/stars/Toum001?style=social)](https://github.com/Toum001)

</div>

---

## 🔥 À propos de moi

Je suis un développeur passionné par la création de projets innovants et l'exploration de nouvelles technologies. J'aime coder, apprendre et partager mes connaissances avec la communauté.

---

## 💻 Mes compétences

<div align="center">

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Odoo](https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white)

</div>

---

## 📊 Statistiques GitHub

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Toum001&show_icons=true&theme=tokyonight&hide_border=true)

![Langages](https://github-readme-stats.vercel.app/api/top-langs/?username=Toum001&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🎯 Projets en vedette

| 🚀 Projet | 📝 Description |
|-----------|---------------|
| [Minishell](https://github.com/Toum001/Minishell) | Un shell Unix minimaliste implémentant les fonctionnalités essentielles d'un interpréteur de commandes |

---

## 📫 Comment me contacter

<div align="center">

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zotoum007@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Toum001)

</div>

---

<div align="center">

### ✨ Merci de visiter mon profil ! ✨

**N'hésite pas à explorer mes projets et me suivre pour rester à jour** 🌟

---

*Dernière mise à jour: 2026-06-14*

</div>
