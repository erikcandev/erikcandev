<div align="center">

<!-- BANNER PRINCIPAL CYBERPUNK -->
<svg width="100%" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cityGradient" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#0A0A0A;stop-opacity:1" />
      <stop offset="70%" style="stop-color:#1a1a2e;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#16213e;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="neonGlow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00F0FF;stop-opacity:0.8" />
      <stop offset="50%" style="stop-color:#FF00FF;stop-opacity:0.8" />
      <stop offset="100%" style="stop-color:#00F0FF;stop-opacity:0.8" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge> 
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="glitch">
      <feOffset in="SourceGraphic" dx="2" dy="0" result="layer1"/>
      <feFlood flood-color="#FF00FF" flood-opacity="0.7"/>
      <feComposite in2="layer1" operator="in"/>
      <feOffset in="SourceGraphic" dx="-2" dy="0" result="layer2"/>
      <feFlood flood-color="#00F0FF" flood-opacity="0.7"/>
      <feComposite in2="layer2" operator="in"/>
      <feMerge>
        <feMergeNode/>
        <feMergeNode/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Background -->
  <rect width="100%" height="100%" fill="url(#cityGradient)"/>
  
  <!-- City Skyline -->
  <polygon points="0,250 50,200 100,180 150,160 200,140 250,120 300,100 350,90 400,85 450,80 500,75 550,70 600,75 650,80 700,85 750,90 800,100 850,120 900,140 950,160 1000,180 1050,200 1100,220 1150,240 1200,250 1200,300 0,300" fill="#0f0f23" stroke="#00F0FF" stroke-width="1"/>
  
  <!-- Neon Grid Lines -->
  <line x1="0" y1="100" x2="1200" y2="100" stroke="#00F0FF" stroke-width="0.5" opacity="0.3"/>
  <line x1="0" y1="150" x2="1200" y2="150" stroke="#FF00FF" stroke-width="0.5" opacity="0.3"/>
  <line x1="0" y1="200" x2="1200" y2="200" stroke="#00F0FF" stroke-width="0.5" opacity="0.3"/>
  
  <!-- Vertical Grid -->
  <line x1="200" y1="0" x2="200" y2="300" stroke="#00F0FF" stroke-width="0.5" opacity="0.2"/>
  <line x1="400" y1="0" x2="400" y2="300" stroke="#FF00FF" stroke-width="0.5" opacity="0.2"/>
  <line x1="600" y1="0" x2="600" y2="300" stroke="#00F0FF" stroke-width="0.5" opacity="0.2"/>
  <line x1="800" y1="0" x2="800" y2="300" stroke="#FF00FF" stroke-width="0.5" opacity="0.2"/>
  <line x1="1000" y1="0" x2="1000" y2="300" stroke="#00F0FF" stroke-width="0.5" opacity="0.2"/>
  
  <!-- Main Title -->
  <text x="600" y="120" font-family="'Courier New', monospace" font-size="48" font-weight="bold" text-anchor="middle" fill="url(#neonGlow)" filter="url(#glow)">
    DOMINGOS
  </text>
  
  <!-- Subtitle -->
  <text x="600" y="160" font-family="'Courier New', monospace" font-size="16" text-anchor="middle" fill="#00F0FF" opacity="0.8">
    &gt; NETRUNNER_STATUS: ONLINE
  </text>
  
  <!-- Glitch Effect Elements -->
  <rect x="580" y="100" width="40" height="3" fill="#FF00FF" opacity="0.6">
    <animate attributeName="opacity" values="0.6;0;0.6" dur="0.1s" repeatCount="indefinite"/>
  </rect>
  <rect x="590" y="140" width="20" height="2" fill="#00F0FF" opacity="0.7">
    <animate attributeName="opacity" values="0.7;0;0.7" dur="0.15s" repeatCount="indefinite"/>
  </rect>
</svg>

---

## 🌐 SYSTEM_LOAD: [DOMINGOS] > STATUS: **ONLINE** // *Full-Stack Developer & Tech Enthusiast*

```bash
> Initializing neural interface...
> Connecting to the Grid...
> STATUS: ████████████████████████████████ 100% ONLINE
```

**Olá, fellow netrunner!** 👋 Sou um desenvolvedor apaixonado por construir **interfaces** e **sistemas robustos**. Sempre explorando novas tecnologias e otimizando minha stack para dominar o mundo digital.

```yaml
CURRENT_PROJECT: "Portfólio Cyberpunk"
LEARNING_FOCUS: "Advanced React Patterns & System Architecture"
LOCATION: "Night City // Brasil"
MISSION: "Building the future, one commit at a time"
```

---

## ⚡ ARSENAL DE TECNOLOGIAS // *TECH_STACK_v2.077*

<div align="center">

### 🎯 **FRONTEND INTERFACES**
<table>
<tr>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="48" height="48" alt="React" style="filter: drop-shadow(0 0 10px #00F0FF);"/>
<br><span style="color: #00F0FF;"><strong>React</strong></span>
</td>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="48" height="48" alt="JavaScript" style="filter: drop-shadow(0 0 10px #FFD700);"/>
<br><span style="color: #FFD700;"><strong>JavaScript</strong></span>
</td>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="48" height="48" alt="TypeScript" style="filter: drop-shadow(0 0 10px #3178C6);"/>
<br><span style="color: #3178C6;"><strong>TypeScript</strong></span>
</td>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="48" height="48" alt="HTML5" style="filter: drop-shadow(0 0 10px #E34F26);"/>
<br><span style="color: #E34F26;"><strong>HTML5</strong></span>
</td>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="48" height="48" alt="CSS3" style="filter: drop-shadow(0 0 10px #1572B6);"/>
<br><span style="color: #1572B6;"><strong>CSS3</strong></span>
</td>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" width="48" height="48" alt="TailwindCSS" style="filter: drop-shadow(0 0 10px #06B6D4);"/>
<br><span style="color: #06B6D4;"><strong>Tailwind</strong></span>
</td>
</tr>
</table>

### 🔥 **BACKEND SYSTEMS**
<table>
<tr>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="48" height="48" alt="Python" style="filter: drop-shadow(0 0 10px #3776AB);"/>
<br><span style="color: #3776AB;"><strong>Python</strong></span>
</td>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="48" height="48" alt="Node.js" style="filter: drop-shadow(0 0 10px #339933);"/>
<br><span style="color: #339933;"><strong>Node.js</strong></span>
</td>
</tr>
</table>

### 📱 **MOBILE NEURAL LINKS**
<table>
<tr>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" width="48" height="48" alt="Kotlin" style="filter: drop-shadow(0 0 10px #7F52FF);"/>
<br><span style="color: #7F52FF;"><strong>Kotlin</strong></span>
</td>
</tr>
</table>

### 🛠️ **SYSTEM TOOLS & PROTOCOLS**
<table>
<tr>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="48" height="48" alt="C++" style="filter: drop-shadow(0 0 10px #00599C);"/>
<br><span style="color: #00599C;"><strong>C++</strong></span>
</td>
<td align="center" width="96">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/npm/npm-original-wordmark.svg" width="48" height="48" alt="npm" style="filter: drop-shadow(0 0 10px #CB3837);"/>
<br><span style="color: #CB3837;"><strong>npm</strong></span>
</td>
<td align="center" width="96">
<svg width="48" height="48" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" style="filter: drop-shadow(0 0 10px #F69220);">
<path d="M12 2.5L2 7L12 11.5L22 7L12 2.5Z" fill="#F69220"/>
<path d="M2 17L12 21.5L22 17" stroke="#F69220" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M2 12L12 16.5L22 12" stroke="#F69220" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
<br><span style="color: #F69220;"><strong>pnpm</strong></span>
</td>
</tr>
</table>

</div>

---

## 📊 STREAMS DE DADOS // *NEURAL_ANALYTICS*

<div align="center">

### 🔥 **SYSTEM PERFORMANCE METRICS**

<img src="https://github-readme-stats.vercel.app/api?username=Domingos&show_icons=true&theme=transparent&title_color=FF00FF&icon_color=00F0FF&text_color=E0E0E0&bg_color=0A0A0A&border_color=00F0FF&hide_border=false&cache_seconds=14400" alt="GitHub Stats" />

### 🎯 **CODE DISTRIBUTION ANALYSIS**

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Domingos&layout=compact&theme=transparent&title_color=FF00FF&text_color=E0E0E0&bg_color=0A0A0A&border_color=00F0FF&hide_border=false&cache_seconds=14400" alt="Top Languages" />

</div>

---

## 🐍 NEURAL ACTIVITY GRID // *CONTRIBUTION_MATRIX*

<div align="center">

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />

</div>

---

## 🔗 INTERFACES DE CONEXÃO // *NETWORK_PROTOCOLS*

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&color=0A0A0A&labelColor=00F0FF)](https://linkedin.com/in/seu-perfil)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&color=0A0A0A&labelColor=FF00FF)](mailto:seu.email@exemplo.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white&color=0A0A0A&labelColor=00F0FF)](https://seu-portfolio.com)

</div>

---

<div align="center">

```ascii
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║  > NEURAL_LINK_ESTABLISHED                                       ║
║  > WELCOME_TO_THE_GRID                                           ║
║  > STATUS: READY_FOR_COLLABORATION                               ║
║                                                                  ║
║  "The future is not some place we are going,                    ║
║   but one we are creating. The paths are not to be found,       ║
║   but made. And the activity of making them changes             ║
║   both the maker and the destination." - John Schaar            ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

<img src="https://komarev.com/ghpvc/?username=Domingos&color=00F0FF&style=for-the-badge&label=NEURAL+CONNECTIONS" alt="Profile Views" />

</div>

---

<div align="center">
<sub>🚀 Built with <strong>Cyberpunk 2077</strong> aesthetics | Powered by <strong>Night City Tech</strong> ⚡</sub>
</div>
