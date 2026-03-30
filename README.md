<!-- ╔══════════════════════════════════════════════════════════════╗
     ║   VISHAN RABARI — ULTRA COLORFUL WORLD-CLASS README          ║
     ╚══════════════════════════════════════════════════════════════╝ -->

<!-- ░░░░░░░░░░░░░░░ HERO BANNER ░░░░░░░░░░░░░░░ -->
<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 300" width="100%">
  <defs>
    <linearGradient id="heroBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#0d0221"/>
      <stop offset="30%"  stop-color="#130a2e"/>
      <stop offset="65%"  stop-color="#0a1628"/>
      <stop offset="100%" stop-color="#04101f"/>
    </linearGradient>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#ff6b6b"/>
      <stop offset="20%"  stop-color="#ffd93d"/>
      <stop offset="40%"  stop-color="#c8ff00"/>
      <stop offset="60%"  stop-color="#00e5ff"/>
      <stop offset="80%"  stop-color="#4d96ff"/>
      <stop offset="100%" stop-color="#c77dff"/>
    </linearGradient>
    <linearGradient id="subGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#00e5ff"/>
      <stop offset="50%"  stop-color="#f472b6"/>
      <stop offset="100%" stop-color="#ffd93d"/>
    </linearGradient>
    <linearGradient id="rainbowBar" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#ff6b6b"/>
      <stop offset="16%"  stop-color="#ffd93d"/>
      <stop offset="33%"  stop-color="#c8ff00"/>
      <stop offset="50%"  stop-color="#00e5ff"/>
      <stop offset="66%"  stop-color="#4d96ff"/>
      <stop offset="83%"  stop-color="#c77dff"/>
      <stop offset="100%" stop-color="#f472b6"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- BG -->
  <rect width="900" height="300" fill="url(#heroBg)"/>

  <!-- Big colorful glowing orbs -->
  <circle cx="100"  cy="80"  r="90"  fill="#c77dff" opacity="0.12"/>
  <circle cx="800"  cy="200" r="110" fill="#00e5ff"  opacity="0.09"/>
  <circle cx="450"  cy="280" r="70"  fill="#ffd93d"  opacity="0.08"/>
  <circle cx="200"  cy="240" r="55"  fill="#ff6b6b"  opacity="0.08"/>
  <circle cx="720"  cy="50"  r="65"  fill="#c8ff00"  opacity="0.08"/>
  <circle cx="350"  cy="40"  r="40"  fill="#f472b6"  opacity="0.07"/>
  <circle cx="600"  cy="260" r="50"  fill="#4d96ff"  opacity="0.08"/>

  <!-- Star particles -->
  <circle cx="50"  cy="25"  r="3"   fill="#ff6b6b"  opacity="1" filter="url(#glow2)"/>
  <circle cx="130" cy="12"  r="2.5" fill="#ffd93d"  opacity="0.9" filter="url(#glow2)"/>
  <circle cx="260" cy="35"  r="2"   fill="#c8ff00"  opacity="0.8"/>
  <circle cx="380" cy="18"  r="3"   fill="#00e5ff"  opacity="1" filter="url(#glow2)"/>
  <circle cx="510" cy="28"  r="2"   fill="#4d96ff"  opacity="0.8"/>
  <circle cx="640" cy="14"  r="2.5" fill="#c77dff"  opacity="0.9" filter="url(#glow2)"/>
  <circle cx="760" cy="32"  r="3"   fill="#f472b6"  opacity="1" filter="url(#glow2)"/>
  <circle cx="860" cy="10"  r="2"   fill="#ffd93d"  opacity="0.8"/>
  <circle cx="25"  cy="210" r="2.5" fill="#c8ff00"  opacity="0.7"/>
  <circle cx="875" cy="240" r="2.5" fill="#ff6b6b"  opacity="0.7"/>
  <circle cx="95"  cy="265" r="2"   fill="#c77dff"  opacity="0.6"/>
  <circle cx="830" cy="110" r="2"   fill="#00e5ff"  opacity="0.6"/>
  <circle cx="450" cy="15"  r="2"   fill="#f472b6"  opacity="0.7"/>
  <circle cx="310" cy="270" r="2.5" fill="#ffd93d"  opacity="0.6"/>
  <circle cx="680" cy="270" r="2"   fill="#c8ff00"  opacity="0.6"/>

  <!-- Top rainbow accent bar (thick) -->
  <rect x="0" y="0" width="900" height="5" fill="url(#rainbowBar)"/>

  <!-- VR badge (glowing) -->
  <rect x="390" y="28" width="120" height="40" rx="20" fill="none" stroke="url(#subGrad)" stroke-width="2" opacity="0.9"/>
  <rect x="390" y="28" width="120" height="40" rx="20" fill="url(#subGrad)" opacity="0.08"/>
  <text x="450" y="53" font-family="monospace" font-size="14" font-weight="800"
        fill="url(#subGrad)" text-anchor="middle" letter-spacing="3" filter="url(#glow2)">⚡ VR.dev</text>

  <!-- MAIN NAME (massive, glowing) -->
  <text x="450" y="138" font-family="monospace" font-size="74" font-weight="900"
        fill="url(#nameGrad)" text-anchor="middle" letter-spacing="9" filter="url(#glow)">VISHAN RABARI</text>

  <!-- Subtitle -->
  <text x="450" y="174" font-family="monospace" font-size="17" font-weight="700"
        fill="url(#subGrad)" text-anchor="middle" letter-spacing="5" filter="url(#glow2)">✦  FRONTEND DEVELOPER  &amp;  CREATOR  ✦</text>

  <!-- Colored tag pills row -->
  <rect x="115" y="192" width="95"  height="24" rx="12" fill="#ff6b6b"  opacity="0.22"/>
  <rect x="220" y="192" width="80"  height="24" rx="12" fill="#ffd93d"  opacity="0.22"/>
  <rect x="310" y="192" width="95"  height="24" rx="12" fill="#c8ff00"  opacity="0.22"/>
  <rect x="415" y="192" width="70"  height="24" rx="12" fill="#00e5ff"  opacity="0.22"/>
  <rect x="495" y="192" width="90"  height="24" rx="12" fill="#c77dff"  opacity="0.22"/>
  <rect x="595" y="192" width="85"  height="24" rx="12" fill="#f472b6"  opacity="0.22"/>
  <rect x="690" y="192" width="95"  height="24" rx="12" fill="#4d96ff"  opacity="0.22"/>
  <text x="162" y="209" font-family="monospace" font-size="10.5" fill="#ff6b6b"  text-anchor="middle" font-weight="700">HTML5 🔥</text>
  <text x="260" y="209" font-family="monospace" font-size="10.5" fill="#ffd93d"  text-anchor="middle" font-weight="700">CSS3 ✨</text>
  <text x="357" y="209" font-family="monospace" font-size="10.5" fill="#c8ff00"  text-anchor="middle" font-weight="700">JavaScript ⚡</text>
  <text x="450" y="209" font-family="monospace" font-size="10.5" fill="#00e5ff"  text-anchor="middle" font-weight="700">Figma</text>
  <text x="540" y="209" font-family="monospace" font-size="10.5" fill="#c77dff"  text-anchor="middle" font-weight="700">REST APIs</text>
  <text x="637" y="209" font-family="monospace" font-size="10.5" fill="#f472b6"  text-anchor="middle" font-weight="700">React 🌱</text>
  <text x="737" y="209" font-family="monospace" font-size="10.5" fill="#4d96ff"  text-anchor="middle" font-weight="700">Freelance ✅</text>

  <!-- Status row -->
  <circle cx="292" cy="245" r="5" fill="#c8ff00" opacity="0.9" filter="url(#glow2)"/>
  <text x="304" y="250" font-family="monospace" font-size="11" fill="#c8ff00" font-weight="700">OPEN TO FREELANCE</text>
  <text x="480" y="250" font-family="monospace" font-size="11" fill="#94a3b8">·</text>
  <text x="493" y="250" font-family="monospace" font-size="11" fill="#ffd93d" font-weight="600">📍 Gandhidham, Gujarat 🇮🇳</text>

  <!-- Bottom wave -->
  <path d="M0,268 Q150,250 300,264 Q450,278 600,260 Q750,244 900,268 L900,300 L0,300 Z" fill="#0d0221" opacity="0.8"/>

  <!-- Bottom rainbow bar -->
  <rect x="0" y="295" width="900" height="5" fill="url(#rainbowBar)"/>
</svg>
</div>

<br/>

<!-- TYPING SVG -->
<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=22&pause=700&color=C8FF00&center=true&vCenter=true&multiline=false&width=850&lines=🚀+Available+for+Freelance+·+Gandhidham%2C+Gujarat+🇮🇳;🎨+Crafting+pixel-perfect%2C+interactive+web+experiences;💻+HTML+·+CSS+·+JavaScript+·+Figma+·+REST+APIs;⚡+Fast+Delivery+%7C+28%2B+Repos+%7C+100%25+Satisfied+Clients;🌱+Currently+levelling+up+with+React.js;✨+Design+First.+Build+Second.+Ship+Always." alt="Typing SVG"/>
</div>

<br/>

<!-- SOCIAL BADGES -->
<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐_PORTFOLIO-vishanrabari.vercel.app-ff6b6b?style=for-the-badge&labelColor=1a0a0a)](https://vishanrabari.vercel.app)
[![LinkedIn](https://img.shields.io/badge/💼_LINKEDIN-Connect-4d96ff?style=for-the-badge&labelColor=0a0a1a)](https://www.linkedin.com/in/vishan-rabari-7634ab392)
[![Gmail](https://img.shields.io/badge/📧_GMAIL-Email_Me-ff4444?style=for-the-badge&labelColor=1a0a0a)](mailto:rabarivishan2@gmail.com)
[![WhatsApp](https://img.shields.io/badge/💬_WHATSAPP-Chat_Now-c8ff00?style=for-the-badge&labelColor=0a1a0a)](https://wa.me/918141314836)
[![Instagram](https://img.shields.io/badge/📸_INSTAGRAM-Follow-f472b6?style=for-the-badge&labelColor=1a0a1a)](https://www.instagram.com/thevishandeveloper7)
[![Resume](https://img.shields.io/badge/📄_RESUME-View_Now-ffd93d?style=for-the-badge&labelColor=1a1a0a)](https://drive.google.com/file/d/1upMC-OW445YW8oTZR3RY_UZ8RA6wsmvX/view)

</div>

<br/>

<!-- STATUS BADGES -->
<div align="center">

![Open](https://img.shields.io/badge/🟢_STATUS-OPEN_FOR_FREELANCE-c8ff00?style=for-the-badge&labelColor=0a150a)
![Location](https://img.shields.io/badge/📍_LOCATION-GANDHIDHAM_GUJARAT_🇮🇳-ffd93d?style=for-the-badge&labelColor=151000)
![Views](https://komarev.com/ghpvc/?username=Vishandeveloper29&label=PROFILE+VIEWS&color=c77dff&style=for-the-badge&labelColor=12001f)
[![Followers](https://img.shields.io/github/followers/Vishandeveloper29?label=FOLLOWERS&style=for-the-badge&color=4d96ff&labelColor=00061a&logo=github)](https://github.com/Vishandeveloper29)

</div>

<br/>

---

<!-- ██████ SECTION 1 — vishan.js ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s1bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1a0033"/><stop offset="50%" stop-color="#001a33"/><stop offset="100%" stop-color="#1a0033"/>
    </linearGradient>
    <linearGradient id="s1t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#c77dff"/><stop offset="50%" stop-color="#00e5ff"/><stop offset="100%" stop-color="#c77dff"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s1bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s1t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s1t)" text-anchor="middle" letter-spacing="4">⚡  vishan.js  —  ● running</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s1t)"/>
</svg>
</div>

<br/>

<table>
<tr>
<td width="55%">

```javascript
const developer = {
  name      : "Vishan Rabari",
  role      : "Frontend Developer & Creator",
  location  : "Gandhidham, Gujarat 🇮🇳",
  stack     : ["HTML5","CSS3","JavaScript",
               "Figma","REST APIs"],
  available : true,      // ✅ Open to freelance

  stats: {
    delivery     : "⚡ 3–5 days avg",
    repos        : "✨ 28+ GitHub repos",
    satisfaction : "🏆 100% Client rated",
    experience   : "🎓 1+ year",
    clients      : "🌍 Worldwide",
  },

  currentlyLearning : "React.js 🚀",
  philosophy : "Design first. Build second. Ship.",
  contact    : "rabarivishan2@gmail.com",
};

console.log("▶ Let's build something amazing!");
```

</td>
<td width="45%" align="center">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="300"/>

</td>
</tr>
</table>

<br/>

<div align="center">

|![](https://img.shields.io/badge/⚡_Fast_Delivery-3–5_days_avg-ffd93d?style=flat-square&labelColor=151000)|![](https://img.shields.io/badge/✨_GitHub_Repos-28%2B_Repos-4d96ff?style=flat-square&labelColor=00061a)|![](https://img.shields.io/badge/🏆_Satisfaction-100%25_Rated-c8ff00?style=flat-square&labelColor=0a150a)|![](https://img.shields.io/badge/🎓_Experience-1%2B_Year-c77dff?style=flat-square&labelColor=12001f)|![](https://img.shields.io/badge/🌍_Clients-Worldwide-f472b6?style=flat-square&labelColor=1a0a1a)|
|:---:|:---:|:---:|:---:|:---:|

</div>

<br/>

---

<!-- ██████ SECTION 2 — ABOUT ME ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s2bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1a0a00"/><stop offset="50%" stop-color="#001a00"/><stop offset="100%" stop-color="#1a0a00"/>
    </linearGradient>
    <linearGradient id="s2t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff6b6b"/><stop offset="50%" stop-color="#ffd93d"/><stop offset="100%" stop-color="#c8ff00"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s2bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s2t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s2t)" text-anchor="middle" letter-spacing="4">🧑‍💻  WHO I AM</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s2t)"/>
</svg>
</div>

<br/>

<img align="right" src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif" height="210"/>

I'm **Vishan Rabari**, a frontend developer from **Gandhidham, Gujarat, India**.
I specialize in building modern, pixel-perfect web interfaces that marry
**clean code** with **beautiful, intentional design**.

Currently deepening my **JavaScript** expertise and learning **React**, I'm passionate about transforming ideas into polished digital products — from e-commerce frontends to interactive API-powered tools.

<br/>

|🎨 Trait|💬 Detail|
|:---:|:---|
|☕|Fueled by chai & late-night builds|
|🎯|Detail-obsessed down to 1px|
|🚀|Always shipping something new|
|🎨|Design in Figma first — then code|
|🤝|Open to freelance & collaborations|
|🌍|Work with clients worldwide|

<br clear="right"/>

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20APIs-06B6D4?style=for-the-badge&logo=fastapi&logoColor=white)
![C](https://img.shields.io/badge/C%20Language-00599C?style=for-the-badge&logo=c&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

<br/>

---

<!-- ██████ SECTION 3 — SKILLS ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s3bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#001a33"/><stop offset="50%" stop-color="#1a0033"/><stop offset="100%" stop-color="#001a33"/>
    </linearGradient>
    <linearGradient id="s3t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#4d96ff"/><stop offset="50%" stop-color="#c77dff"/><stop offset="100%" stop-color="#f472b6"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s3bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s3t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s3t)" text-anchor="middle" letter-spacing="4">🛠️  SKILLS &amp; TOOLS</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s3t)"/>
</svg>
</div>

<br/>

<div align="center">

### 🌐 Core Frontend
![HTML5](https://img.shields.io/badge/HTML5-Expert-E34F26?style=flat-square&logo=html5&logoColor=white&labelColor=1a0000)
![CSS3](https://img.shields.io/badge/CSS3-Expert-1572B6?style=flat-square&logo=css3&logoColor=white&labelColor=000d1a)
![JavaScript](https://img.shields.io/badge/JavaScript-Advanced-F7DF1E?style=flat-square&logo=javascript&logoColor=black&labelColor=1a1600)
![Responsive](https://img.shields.io/badge/Responsive-Expert-06B6D4?style=flat-square&labelColor=001a1a)
![CSS Animations](https://img.shields.io/badge/CSS_Animations-Expert-a855f7?style=flat-square&labelColor=0d001a)
![DOM](https://img.shields.io/badge/DOM_Manipulation-Advanced-22c55e?style=flat-square&labelColor=001a00)

### 🎨 Design & Dev Tools
![Figma](https://img.shields.io/badge/Figma-Advanced-F24E1E?style=flat-square&logo=figma&logoColor=white&labelColor=1a0500)
![Git](https://img.shields.io/badge/Git-Advanced-F05032?style=flat-square&logo=git&logoColor=white&labelColor=1a0200)
![GitHub](https://img.shields.io/badge/GitHub_Pages-Advanced-ffffff?style=flat-square&logo=github&logoColor=black&labelColor=0d0d0d)
![REST APIs](https://img.shields.io/badge/REST_APIs-Advanced-38BDF8?style=flat-square&labelColor=001a22)
![Web Perf](https://img.shields.io/badge/Web_Performance-Advanced-ffd93d?style=flat-square&labelColor=1a1500)
![SEO](https://img.shields.io/badge/SEO-Intermediate-c8ff00?style=flat-square&labelColor=001200)

### 🚀 Currently Learning
![React](https://img.shields.io/badge/React.js-Learning_🌱-61DAFB?style=flat-square&logo=react&logoColor=black&labelColor=001a1f)
![Node](https://img.shields.io/badge/Node.js-Next_Goal-339933?style=flat-square&logo=node.js&logoColor=white&labelColor=001a00)
![GSAP](https://img.shields.io/badge/GSAP_Animations-Learning-88CE02?style=flat-square&logo=greensock&logoColor=white&labelColor=0d1400)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-Next_Goal-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white&labelColor=001214)
![TypeScript](https://img.shields.io/badge/TypeScript-Next_Goal-3178C6?style=flat-square&logo=typescript&logoColor=white&labelColor=00091a)

</div>

<br/>

<!-- COLORFUL SKILL BARS SVG — Enhanced -->
<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 880 360" width="95%">
  <defs>
    <linearGradient id="bar1" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#ff6b6b"/><stop offset="100%" stop-color="#ffd93d"/></linearGradient>
    <linearGradient id="bar2" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#c8ff00"/><stop offset="100%" stop-color="#00e5ff"/></linearGradient>
    <linearGradient id="bar3" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#4d96ff"/><stop offset="100%" stop-color="#c77dff"/></linearGradient>
    <linearGradient id="bar4" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#f472b6"/><stop offset="100%" stop-color="#fb923c"/></linearGradient>
    <linearGradient id="bar5" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#ffd93d"/><stop offset="100%" stop-color="#c8ff00"/></linearGradient>
    <linearGradient id="bar6" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#c77dff"/><stop offset="100%" stop-color="#f472b6"/></linearGradient>
    <linearGradient id="bar7" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#00e5ff"/><stop offset="100%" stop-color="#4d96ff"/></linearGradient>
    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" stop-color="#c8ff00"/><stop offset="50%" stop-color="#00e5ff"/><stop offset="100%" stop-color="#c8ff00"/></linearGradient>
    <filter id="glowBar">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="880" height="360" rx="16" fill="#0d0221"/>
  <rect width="880" height="5" rx="2" fill="url(#titleGrad)"/>

  <!-- Title -->
  <text x="440" y="35" font-family="monospace" font-size="15" font-weight="800" fill="url(#titleGrad)" text-anchor="middle" letter-spacing="4" filter="url(#glowBar)">📊 SKILL PROFICIENCY</text>

  <!-- HTML5 95% -->
  <text x="160" y="70" font-family="monospace" font-size="12.5" fill="#ff6b6b" text-anchor="end" font-weight="700">HTML5</text>
  <rect x="170" y="57" width="490" height="16" rx="8" fill="#1e1e2e"/>
  <rect x="170" y="57" width="466" height="16" rx="8" fill="url(#bar1)" filter="url(#glowBar)"/>
  <text x="670" y="70" font-family="monospace" font-size="12" fill="#ffd93d" font-weight="800">95% ⭐⭐⭐⭐⭐</text>

  <!-- CSS3 90% -->
  <text x="160" y="107" font-family="monospace" font-size="12.5" fill="#c8ff00" text-anchor="end" font-weight="700">CSS3</text>
  <rect x="170" y="94" width="490" height="16" rx="8" fill="#1e1e2e"/>
  <rect x="170" y="94" width="441" height="16" rx="8" fill="url(#bar2)" filter="url(#glowBar)"/>
  <text x="670" y="107" font-family="monospace" font-size="12" fill="#c8ff00" font-weight="800">90% ⭐⭐⭐⭐⭐</text>

  <!-- Responsive 90% -->
  <text x="160" y="144" font-family="monospace" font-size="12.5" fill="#00e5ff" text-anchor="end" font-weight="700">Responsive UI</text>
  <rect x="170" y="131" width="490" height="16" rx="8" fill="#1e1e2e"/>
  <rect x="170" y="131" width="441" height="16" rx="8" fill="url(#bar3)" filter="url(#glowBar)"/>
  <text x="670" y="144" font-family="monospace" font-size="12" fill="#4d96ff" font-weight="800">90% ⭐⭐⭐⭐⭐</text>

  <!-- CSS Animations 85% -->
  <text x="160" y="181" font-family="monospace" font-size="12.5" fill="#f472b6" text-anchor="end" font-weight="700">CSS Animations</text>
  <rect x="170" y="168" width="490" height="16" rx="8" fill="#1e1e2e"/>
  <rect x="170" y="168" width="417" height="16" rx="8" fill="url(#bar4)" filter="url(#glowBar)"/>
  <text x="670" y="181" font-family="monospace" font-size="12" fill="#f472b6" font-weight="800">85% ⭐⭐⭐⭐⭐</text>

  <!-- Git 80% -->
  <text x="160" y="218" font-family="monospace" font-size="12.5" fill="#ffd93d" text-anchor="end" font-weight="700">Git &amp; GitHub</text>
  <rect x="170" y="205" width="490" height="16" rx="8" fill="#1e1e2e"/>
  <rect x="170" y="205" width="392" height="16" rx="8" fill="url(#bar5)" filter="url(#glowBar)"/>
  <text x="670" y="218" font-family="monospace" font-size="12" fill="#ffd93d" font-weight="800">80% ⭐⭐⭐⭐</text>

  <!-- Figma 78% -->
  <text x="160" y="255" font-family="monospace" font-size="12.5" fill="#c77dff" text-anchor="end" font-weight="700">Figma / UI·UX</text>
  <rect x="170" y="242" width="490" height="16" rx="8" fill="#1e1e2e"/>
  <rect x="170" y="242" width="382" height="16" rx="8" fill="url(#bar6)" filter="url(#glowBar)"/>
  <text x="670" y="255" font-family="monospace" font-size="12" fill="#c77dff" font-weight="800">78% ⭐⭐⭐⭐</text>

  <!-- JS 65% -->
  <text x="160" y="292" font-family="monospace" font-size="12.5" fill="#00e5ff" text-anchor="end" font-weight="700">JavaScript ES6+</text>
  <rect x="170" y="279" width="490" height="16" rx="8" fill="#1e1e2e"/>
  <rect x="170" y="279" width="319" height="16" rx="8" fill="url(#bar7)" filter="url(#glowBar)"/>
  <text x="670" y="292" font-family="monospace" font-size="12" fill="#00e5ff" font-weight="800">65% ⭐⭐⭐ 🌱</text>

  <!-- REST APIs 72% -->
  <text x="160" y="329" font-family="monospace" font-size="12.5" fill="#fb923c" text-anchor="end" font-weight="700">REST APIs</text>
  <rect x="170" y="316" width="490" height="16" rx="8" fill="#1e1e2e"/>
  <rect x="170" y="316" width="353" height="16" rx="8" fill="url(#bar4)" filter="url(#glowBar)"/>
  <text x="670" y="329" font-family="monospace" font-size="12" fill="#fb923c" font-weight="800">72% ⭐⭐⭐⭐</text>

  <rect y="355" width="880" height="5" rx="2" fill="url(#titleGrad)"/>
</svg>
</div>

<br/>

---

<!-- ██████ SECTION 4 — SERVICES ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s4bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1a1500"/><stop offset="50%" stop-color="#001a00"/><stop offset="100%" stop-color="#1a1500"/>
    </linearGradient>
    <linearGradient id="s4t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ffd93d"/><stop offset="50%" stop-color="#c8ff00"/><stop offset="100%" stop-color="#00e5ff"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s4bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s4t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s4t)" text-anchor="middle" letter-spacing="4">💼  WHAT I OFFER — SERVICES</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s4t)"/>
</svg>
</div>

<br/>

<div align="center">

|🎨|Service|Description|Stack|💰 Price|
|:---:|:---|:---|:---:|:---:|
|🚀|**Landing Pages**|High-converting, visually stunning pages. Fast-loading & fully responsive.|![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square) ![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logoColor=black)|**From ₹6,000**|
|🛒|**E-Commerce**|Full-featured frontends — product listings, cart, seamless checkout UX.|![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square) ![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logoColor=black)|**From ₹12,000**|
|⚡|**Web Apps**|Interactive apps powered by REST APIs — weather, currency, GitHub explorers.|![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logoColor=black) ![API](https://img.shields.io/badge/REST_API-06B6D4?style=flat-square)|**From ₹10,000**|
|🎨|**UI/UX Design**|Figma-based UI with design systems, component libraries, dev handoffs.|![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)|**From ₹5,000**|
|📱|**Responsive Design**|Mobile-first websites flawless on every device. Fluid grids & breakpoints.|![Mobile](https://img.shields.io/badge/Mobile_First-c8ff00?style=flat-square&labelColor=001200)|**Included**|
|⚙️|**Performance Audit**|Core Web Vitals, minified code, lazy loading & image optimisation.|![Vitals](https://img.shields.io/badge/Web_Vitals-ffd93d?style=flat-square&labelColor=151000)|**From ₹5,000**|

</div>

<br/>

---

<!-- ██████ SECTION 5 — PROJECTS ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s5bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1a0020"/><stop offset="50%" stop-color="#00101a"/><stop offset="100%" stop-color="#1a0020"/>
    </linearGradient>
    <linearGradient id="s5t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff6b6b"/><stop offset="33%" stop-color="#ffd93d"/><stop offset="66%" stop-color="#c8ff00"/><stop offset="100%" stop-color="#00e5ff"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s5bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s5t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s5t)" text-anchor="middle" letter-spacing="4">🚀  FEATURED PROJECTS</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s5t)"/>
</svg>
</div>

<br/>

<div align="center">

[![ApexDeck](https://github-readme-stats.vercel.app/api/pin/?username=Vishandeveloper29&repo=Apex-Deck-Design&theme=tokyonight&hide_border=true&border_radius=15&title_color=ff6b6b&icon_color=ffd93d&text_color=ffffff&bg_color=0d0221)](https://github.com/Vishandeveloper29/Apex-Deck-Design)&nbsp;&nbsp;
[![Portfolio](https://github-readme-stats.vercel.app/api/pin/?username=Vishandeveloper29&repo=Vishandeveloper&theme=tokyonight&hide_border=true&border_radius=15&title_color=c8ff00&icon_color=00e5ff&text_color=ffffff&bg_color=0d0221)](https://github.com/Vishandeveloper29/Vishandeveloper)

</div>

<br/>

> ![](https://img.shields.io/badge/🎨_ApexDeck-Design_System-ff6b6b?style=flat-square&labelColor=1a0000) ![Featured](https://img.shields.io/badge/★_Featured-ffd93d?style=flat-square&labelColor=151000)
>
> A comprehensive, modern design system & component library with consistent spacing, typography, and interaction patterns.
>
> ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white) ![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) &nbsp;[**GitHub ↗**](https://github.com/Vishandeveloper29)

---

> ![](https://img.shields.io/badge/🛒_LK_Mart-E--Commerce-c8ff00?style=flat-square&labelColor=0a1a00) ![](https://img.shields.io/badge/Frontend-22c55e?style=flat-square)
>
> Full-featured e-commerce frontend with product listings, cart, and seamless shopping UX.
>
> ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white) ![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) &nbsp;[**Live ↗**](https://lkmart.onrender.com/) &nbsp;·&nbsp; [**GitHub ↗**](https://github.com/Vishandeveloper29)

---

> ![](https://img.shields.io/badge/💱_Currency_Converter-Web_API-00e5ff?style=flat-square&labelColor=001a22) ![Finance](https://img.shields.io/badge/Finance-ffd93d?style=flat-square)
>
> Real-time currency conversion. Supports 150+ world currencies with live exchange data.
>
> ![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![REST API](https://img.shields.io/badge/REST_API-06B6D4?style=flat-square) &nbsp;[**Live ↗**](https://vishandeveloper29.github.io/Currency-Converter/) &nbsp;·&nbsp; [**GitHub ↗**](https://github.com/Vishandeveloper29)

---

> ![](https://img.shields.io/badge/⛅_Weather_App-Real--time_API-4d96ff?style=flat-square&labelColor=00061a) ![Live](https://img.shields.io/badge/Live-c8ff00?style=flat-square)
>
> Live weather using OpenWeatherMap API with location search and animated weather icons.
>
> ![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![OpenWeather](https://img.shields.io/badge/OpenWeather_API-E96E4C?style=flat-square) &nbsp;[**Live ↗**](https://vishandeveloper29.github.io/Weather-app/) &nbsp;·&nbsp; [**GitHub ↗**](https://github.com/Vishandeveloper29)

---

> ![](https://img.shields.io/badge/🔍_GitHub_Explorer-GitHub_API-c77dff?style=flat-square&labelColor=0d001a) ![Featured](https://img.shields.io/badge/★_Featured-ffd93d?style=flat-square)
>
> Search and explore GitHub users & repositories in real-time with a clean, fast UI.
>
> ![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![GitHub API](https://img.shields.io/badge/GitHub_API-181717?style=flat-square&logo=github) &nbsp;[**Live ↗**](https://vishandeveloper29.github.io/GitHub-Explorer/) &nbsp;·&nbsp; [**GitHub ↗**](https://github.com/Vishandeveloper29)

---

> ![](https://img.shields.io/badge/🎬_Netflix_Clone-HTML/CSS-f472b6?style=flat-square&labelColor=1a001a) ![Clone](https://img.shields.io/badge/Clone-ec4899?style=flat-square)
>
> Pixel-perfect Netflix landing page clone. Fully responsive layout with hover effects & animations.
>
> ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white) &nbsp;[**GitHub ↗**](https://github.com/Vishandeveloper29/Netflix-Clone)

---

> ![](https://img.shields.io/badge/✅_To--Do_App-Vanilla_JS-fb923c?style=flat-square&labelColor=1a0a00) ![Productivity](https://img.shields.io/badge/Productivity-22c55e?style=flat-square)
>
> Clean, minimal dark-themed task manager with add, edit, complete & delete. Live stats, keyboard shortcuts, zero dependencies.
>
> ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white) ![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) &nbsp;[**Live ↗**](https://vishandeveloper29.github.io/To-Do-List/) &nbsp;·&nbsp; [**GitHub ↗**](https://github.com/Vishandeveloper29/To-Do-List)

---

> ![](https://img.shields.io/badge/⭐_Star_Catcher-Mini_Game-ffd93d?style=flat-square&labelColor=151000) ![Interactive](https://img.shields.io/badge/Interactive-c77dff?style=flat-square)
>
> Fast-paced reflex game — catch the star before time runs out! Particle bursts, danger mode & high score tracking. Zero dependencies.
>
> ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white) ![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) &nbsp;[**GitHub ↗**](https://github.com/Vishandeveloper29)

<br/>

<div align="center">

[![All Repos](https://img.shields.io/badge/🚀_View_All_28%2B_Projects-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0d0d)](https://github.com/Vishandeveloper29?tab=repositories)
[![Live Portfolio](https://img.shields.io/badge/🌐_See_Live_Portfolio-vishanrabari.vercel.app-ff6b6b?style=for-the-badge&labelColor=1a0000)](https://vishanrabari.vercel.app)

</div>

<br/>

---

<!-- ██████ SECTION 6 — GITHUB STATS ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s6bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0a1500"/><stop offset="50%" stop-color="#001a22"/><stop offset="100%" stop-color="#0a1500"/>
    </linearGradient>
    <linearGradient id="s6t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#c8ff00"/><stop offset="50%" stop-color="#00e5ff"/><stop offset="100%" stop-color="#4d96ff"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s6bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s6t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s6t)" text-anchor="middle" letter-spacing="4">📊  GITHUB STATS</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s6t)"/>
</svg>
</div>

<br/>

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Vishandeveloper29&show_icons=true&theme=tokyonight&hide_border=true&border_radius=15&include_all_commits=true&count_private=true&title_color=c8ff00&icon_color=ffd93d&text_color=ffffff&bg_color=0d0221" height="190"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vishandeveloper29&layout=compact&theme=tokyonight&hide_border=true&border_radius=15&langs_count=8&title_color=00e5ff&text_color=ffffff&bg_color=0d0221" height="190"/>
</div>

<br/>

<div align="center">
<img src="https://streak-stats.demolab.com?user=Vishandeveloper29&theme=tokyonight&hide_border=true&border_radius=15&fire=ff6b6b&ring=c8ff00&currStreakLabel=00e5ff&sideLabels=c77dff&dates=94a3b8" height="210"/>
</div>

<br/>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Vishandeveloper29&theme=tokyo-night&hide_border=true&area=true&custom_title=🔥%20Vishan's%20Contribution%20Graph&area_color=c8ff00&line=ffd93d&point=00e5ff&color=ffffff&bg_color=0d0221" width="97%"/>
</div>

<br/>

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=Vishandeveloper29&theme=radical&no-frame=true&no-bg=true&margin-w=8&column=7" width="97%"/>
</div>

<br/>

---

<!-- ██████ SECTION 7 — PROCESS ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s7bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1a0010"/><stop offset="50%" stop-color="#001519"/><stop offset="100%" stop-color="#1a0010"/>
    </linearGradient>
    <linearGradient id="s7t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#f472b6"/><stop offset="50%" stop-color="#fb923c"/><stop offset="100%" stop-color="#ffd93d"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s7bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s7t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s7t)" text-anchor="middle" letter-spacing="4">⚙️  HOW I WORK — MY PROCESS</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s7t)"/>
</svg>
</div>

<br/>

<div align="center">

|![](https://img.shields.io/badge/01-DISCOVER-ff6b6b?style=for-the-badge&labelColor=1a0000)|![](https://img.shields.io/badge/02-DESIGN-ffd93d?style=for-the-badge&labelColor=151000)|![](https://img.shields.io/badge/03-DEVELOP-c8ff00?style=for-the-badge&labelColor=0a1500)|![](https://img.shields.io/badge/04-DELIVER-00e5ff?style=for-the-badge&labelColor=001a22)|
|:---:|:---:|:---:|:---:|
|🔭|🎨|💻|🚀|
|Deep-dive into your goals, audience & vision through focused conversation and research.|Wireframes & Figma prototypes that define the visual direction before any code is written.|Clean, semantic code with pixel-perfect implementation, animations & cross-device testing.|Final handoff with docs, optimised assets, and **7-day post-delivery support** included.|
|**Day 1**|**Day 1–2**|**Day 2–4**|**Day 4–5**|

</div>

<br/>

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 880 52" width="95%">
  <defs>
    <linearGradient id="arrowGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#ff6b6b"/>
      <stop offset="33%"  stop-color="#ffd93d"/>
      <stop offset="66%"  stop-color="#c8ff00"/>
      <stop offset="100%" stop-color="#00e5ff"/>
    </linearGradient>
  </defs>
  <rect width="880" height="52" rx="10" fill="#0d0221"/>
  <rect width="880" height="4" rx="2" fill="url(#arrowGrad)"/>
  <text x="440" y="24" font-family="monospace" font-size="13" fill="url(#arrowGrad)" text-anchor="middle" font-weight="800" letter-spacing="1">
    DISCOVER ──────► DESIGN ──────► DEVELOP ──────► DELIVER
  </text>
  <text x="440" y="42" font-family="monospace" font-size="11" fill="#94a3b8" text-anchor="middle">
    Total Timeline:  3–5 Days Fast Delivery  ⚡  |  100% On Time  🏆
  </text>
  <rect y="48" width="880" height="4" rx="2" fill="url(#arrowGrad)"/>
</svg>
</div>

<br/>

---

<!-- ██████ SECTION 8 — JOURNEY ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s8bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#001a00"/><stop offset="50%" stop-color="#1a1500"/><stop offset="100%" stop-color="#001a00"/>
    </linearGradient>
    <linearGradient id="s8t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#c8ff00"/><stop offset="50%" stop-color="#ffd93d"/><stop offset="100%" stop-color="#fb923c"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s8bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s8t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s8t)" text-anchor="middle" letter-spacing="4">🕐  JOURNEY &amp; EXPERIENCE</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s8t)"/>
</svg>
</div>

<br/>

<div align="center">

|📅|🏆 Milestone|📖 Story|🏷️|
|:---:|:---:|:---|:---:|
|**Early 2025**|![](https://img.shields.io/badge/🌱_Started_Web_Dev-Self--Taught-c8ff00?style=flat-square&labelColor=001200)|Began with HTML and CSS fundamentals. Built first static pages, discovered a passion for beautiful web experiences.|![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square)|
|**Mid 2025**|![](https://img.shields.io/badge/⚡_JS_&_DOM_Mastery-Self--Taught-ffd93d?style=flat-square&labelColor=151000)|Dived deep into JavaScript — DOM manipulation, ES6+, async patterns, and first API integrations.|![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logoColor=black) ![APIs](https://img.shields.io/badge/APIs-00e5ff?style=flat-square) ![ES6+](https://img.shields.io/badge/ES6+-22c55e?style=flat-square)|
|**Late 2025**|![](https://img.shields.io/badge/💰_First_Freelance-Remote-ff6b6b?style=flat-square&labelColor=1a0000)|Landed first clients — landing pages, e-commerce fronts, portfolio sites. Learned deadlines and iterative design.|![Freelance](https://img.shields.io/badge/Freelance-f59e0b?style=flat-square) ![E-Comm](https://img.shields.io/badge/E--Commerce-22c55e?style=flat-square)|
|**Late 2025**|![](https://img.shields.io/badge/🎨_Figma_&_UI/UX-Design_Systems-c77dff?style=flat-square&labelColor=0d001a)|Expanded into Figma for design systems, prototypes, and thinking like a designer while coding like an engineer.|![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square) ![UI/UX](https://img.shields.io/badge/UI%2FUX-a855f7?style=flat-square)|
|**🟢 2026**|![](https://img.shields.io/badge/🚀_Advanced_&_React-OPEN_TO_WORK-00e5ff?style=flat-square&labelColor=001a22)|Building complex projects, expanding 28+ repos, learning React, seeking freelance and collaboration opportunities.|![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![OpenToWork](https://img.shields.io/badge/Open_To_Work-c8ff00?style=flat-square)|

</div>

<br/>

---

<!-- ██████ SECTION 9 — PRICING ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s9bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1a1000"/><stop offset="50%" stop-color="#001500"/><stop offset="100%" stop-color="#1a1000"/>
    </linearGradient>
    <linearGradient id="s9t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ffd93d"/><stop offset="33%" stop-color="#fb923c"/><stop offset="66%" stop-color="#ff6b6b"/><stop offset="100%" stop-color="#f472b6"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s9bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s9t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s9t)" text-anchor="middle" letter-spacing="4">💰  TRANSPARENT PRICING</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s9t)"/>
</svg>
</div>

<br/>

> 📦 All plans include **mobile-first responsive design**, **source code delivery**, and **7-day post-launch support**.

<br/>

<div align="center">

|🥉 **STARTER**|🥇 **PRO** ⭐|💎 **PREMIUM**|
|:---:|:---:|:---:|
|![](https://img.shields.io/badge/₹8%2C000-per_project-c8ff00?style=for-the-badge&labelColor=001200)|![](https://img.shields.io/badge/₹25%2C000-per_project-ffd93d?style=for-the-badge&labelColor=151000)|![](https://img.shields.io/badge/₹35%2C000-per_project-c77dff?style=for-the-badge&labelColor=0d001a)|
|*Landing pages & portfolios*|*Businesses & e-commerce*|*Full-scale web apps*|
|✅ 1–3 page website|✅ Up to 8 pages|✅ Unlimited pages|
|✅ Fully responsive|✅ Fully responsive|✅ Full web application|
|✅ Contact form|✅ E-commerce cart|✅ Multiple API integrations|
|✅ Basic animations|✅ API integrations|✅ Advanced animations|
|✅ 3-day delivery ⚡|✅ Custom animations|✅ Performance audit|
|❌ E-commerce|✅ 5-day delivery ⚡|✅ 14-day support|
|❌ API integrations|✅ Figma design file|✅ Full design system|
|[![Start](https://img.shields.io/badge/Get_Started-c8ff00?style=flat-square&labelColor=001200)](mailto:rabarivishan2@gmail.com)|[![Start](https://img.shields.io/badge/Get_Started-ffd93d?style=flat-square&labelColor=151000)](mailto:rabarivishan2@gmail.com)|[![Start](https://img.shields.io/badge/Get_Started-c77dff?style=flat-square&labelColor=0d001a)](mailto:rabarivishan2@gmail.com)|

</div>

<br/>

> 💬 **Need something custom?** Pricing starts at ₹3,000. I'm flexible and work within budgets. [**Let's talk →**](mailto:rabarivishan2@gmail.com)

<br/>

---

<!-- ██████ SECTION 10 — ROADMAP ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s10bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#001a22"/><stop offset="50%" stop-color="#1a0033"/><stop offset="100%" stop-color="#001a22"/>
    </linearGradient>
    <linearGradient id="s10t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00e5ff"/><stop offset="50%" stop-color="#4d96ff"/><stop offset="100%" stop-color="#c77dff"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s10bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s10t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s10t)" text-anchor="middle" letter-spacing="4">🌱  ROADMAP &amp; LEARNING</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s10t)"/>
</svg>
</div>

<br/>

<div align="center">

```javascript
const roadmap = {
  currentlyLearning : ["JavaScript ES6+", "DOM Manipulation", "Fetch API", "Async/Await"],
  nextGoals         : ["React.js", "Node.js", "GSAP Animations", "Tailwind CSS", "TypeScript"],
  designTools       : ["Figma", "Adobe XD"],
  otherLearning     : ["CSS Grid", "Flexbox", "Core Web Vitals", "SEO Optimisation"],
  workingOn         : "28+ GitHub Repos + Advanced Projects 🔨",
  dailyRoutine      : ["Code 💻", "Design 🎨", "Learn 📚", "Ship 🚀"],
  lifeGoal          : "Build products that millions of people love ❤️",
};
```

</div>

<br/>

<div align="center">

|✅ **Completed**|🔄 **In Progress**|🎯 **Next Up**|🔮 **Future**|
|:---:|:---:|:---:|:---:|
|![](https://img.shields.io/badge/HTML5-done-c8ff00?style=flat-square)|![](https://img.shields.io/badge/JavaScript_ES6+-wip-ffd93d?style=flat-square)|![](https://img.shields.io/badge/React.js-next-00e5ff?style=flat-square)|![](https://img.shields.io/badge/Next.js-future-c77dff?style=flat-square)|
|![](https://img.shields.io/badge/CSS3_&_Animations-done-c8ff00?style=flat-square)|![](https://img.shields.io/badge/DOM_Manipulation-wip-ffd93d?style=flat-square)|![](https://img.shields.io/badge/Node.js-next-00e5ff?style=flat-square)|![](https://img.shields.io/badge/MongoDB-future-c77dff?style=flat-square)|
|![](https://img.shields.io/badge/Responsive_Design-done-c8ff00?style=flat-square)|![](https://img.shields.io/badge/REST_APIs-wip-ffd93d?style=flat-square)|![](https://img.shields.io/badge/GSAP_Animations-next-00e5ff?style=flat-square)|![](https://img.shields.io/badge/TypeScript-future-c77dff?style=flat-square)|
|![](https://img.shields.io/badge/Figma_&_UI/UX-done-c8ff00?style=flat-square)|![](https://img.shields.io/badge/Async_/_Await-wip-ffd93d?style=flat-square)|![](https://img.shields.io/badge/Tailwind_CSS-next-00e5ff?style=flat-square)|![](https://img.shields.io/badge/GraphQL-future-c77dff?style=flat-square)|
|![](https://img.shields.io/badge/GitHub_Pages-done-c8ff00?style=flat-square)|![](https://img.shields.io/badge/Git_Advanced-wip-ffd93d?style=flat-square)|![](https://img.shields.io/badge/Core_Web_Vitals-next-00e5ff?style=flat-square)|![](https://img.shields.io/badge/Docker-future-c77dff?style=flat-square)|

</div>

<br/>

---

<!-- ██████ SECTION 11 — TESTIMONIALS ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s11bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1a0a00"/><stop offset="50%" stop-color="#1a001a"/><stop offset="100%" stop-color="#1a0a00"/>
    </linearGradient>
    <linearGradient id="s11t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#fb923c"/><stop offset="50%" stop-color="#f472b6"/><stop offset="100%" stop-color="#c77dff"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s11bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s11t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s11t)" text-anchor="middle" letter-spacing="4">⭐  WHAT CLIENTS SAY</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s11t)"/>
</svg>
</div>

<br/>

<table>
<tr>
<td width="50%">

> ![](https://img.shields.io/badge/★★★★★-ff6b6b?style=flat-square) &nbsp; **Dhruv Mangukiya** · *Startup Founder*
>
> *"Vishan delivered an exceptional landing page that exceeded our expectations. His attention to detail, clean code, and the final animations were absolutely world-class. Will definitely work with him again."*

</td>
<td width="50%">

> ![](https://img.shields.io/badge/★★★★★-ffd93d?style=flat-square) &nbsp; **Naresh Kriplani** · *E-Commerce Owner*
>
> *"Our e-commerce store was completely redesigned by Vishan and conversion rate improved significantly. The responsive design is flawless across all devices — truly impressive work."*

</td>
</tr>
<tr>
<td width="50%">

> ![](https://img.shields.io/badge/★★★★★-c8ff00?style=flat-square) &nbsp; **Ravi Mehta** · *Freelance Photographer*
>
> *"Vishan is a rare talent — he thinks like a designer but codes like an engineer. The portfolio website he built for me gets compliments from every client I show it to. Highly recommend!"*

</td>
<td width="50%">

> ![](https://img.shields.io/badge/★★★★★-00e5ff?style=flat-square) &nbsp; **Priya Desai** · *Brand Manager*
>
> *"Working with Vishan was a seamless experience from start to finish. He understood our brand and translated it into a website that our customers absolutely love. Fast, professional, talented."*

</td>
</tr>
</table>

<br/>

---

<!-- ██████ SECTION 12 — BLOG ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s12bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#001a1a"/><stop offset="50%" stop-color="#0a1500"/><stop offset="100%" stop-color="#001a1a"/>
    </linearGradient>
    <linearGradient id="s12t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00e5ff"/><stop offset="50%" stop-color="#c8ff00"/><stop offset="100%" stop-color="#ffd93d"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s12bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s12t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s12t)" text-anchor="middle" letter-spacing="4">📝  BLOG &amp; DEV NOTES</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s12t)"/>
</svg>
</div>

<br/>

|📅|🏷️ Tags|📖 Article|
|:---:|:---:|:---|
|Jan 2025|![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![Animations](https://img.shields.io/badge/Animations-c77dff?style=flat-square)|**[5 CSS Tricks I Use on Every Project](https://vishanrabari.vercel.app#blog)** — From custom scroll bars to clip-path animations — CSS patterns that make UIs stand out.|
|Dec 2025|![JS](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat-square&logoColor=black) ![Storage](https://img.shields.io/badge/localStorage-00e5ff?style=flat-square)|**[Building a Cart Without Any Framework](https://vishanrabari.vercel.app#blog)** — A fully functional shopping cart with localStorage, vanilla JS, zero dependencies.|
|Nov 2025|![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) ![Workflow](https://img.shields.io/badge/Workflow-c8ff00?style=flat-square)|**[Why I Started Using Figma Before Coding](https://vishanrabari.vercel.app#blog)** — The shift that tripled my speed — designing first means fewer rewrites & happier clients.|

<br/>

---

<!-- ██████ SECTION 13 — FAQ ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s13bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1a0020"/><stop offset="50%" stop-color="#001a22"/><stop offset="100%" stop-color="#1a0020"/>
    </linearGradient>
    <linearGradient id="s13t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#c77dff"/><stop offset="50%" stop-color="#00e5ff"/><stop offset="100%" stop-color="#c8ff00"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s13bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s13t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s13t)" text-anchor="middle" letter-spacing="4">❓  FAQ — COMMON QUESTIONS</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s13t)"/>
</svg>
</div>

<br/>

<details>
<summary><b>⏱️ How long does a typical project take?</b></summary>
<br/>
A landing page takes <b>3–5 days</b>. A full e-commerce site or web app takes <b>1–3 weeks</b>. I always discuss timelines upfront and deliver on time.
<br/><br/>
</details>

<details>
<summary><b>💰 What's your pricing / budget range?</b></summary>
<br/>
Pricing starts at <b>₹3,000</b> for landing pages. Full sites and web apps are quoted after understanding requirements. I'm flexible and work within budgets.
<br/><br/>
</details>

<details>
<summary><b>🌍 Do you work with clients outside India?</b></summary>
<br/>
Absolutely! I work <b>worldwide</b> via email, WhatsApp, and video calls. Clear communication and timely delivery guaranteed regardless of timezone.
<br/><br/>
</details>

<details>
<summary><b>📱 Will my website be mobile-friendly?</b></summary>
<br/>
<b>100% yes</b> — I build mobile-first by default. Every project is tested on multiple screen sizes for a flawless experience everywhere.
<br/><br/>
</details>

<details>
<summary><b>🛠️ Do you provide post-delivery support?</b></summary>
<br/>
Yes! I offer <b>7–14 days</b> of free post-delivery support for bug fixes. Ongoing maintenance can be arranged per retainer or per-task.
<br/><br/>
</details>

<br/>

---

<!-- ██████ SECTION 14 — CONTACT ██████ -->

<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 56" width="100%">
  <defs>
    <linearGradient id="s14bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00101a"/><stop offset="50%" stop-color="#1a0010"/><stop offset="100%" stop-color="#00101a"/>
    </linearGradient>
    <linearGradient id="s14t" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#4d96ff"/><stop offset="33%" stop-color="#c77dff"/><stop offset="66%" stop-color="#f472b6"/><stop offset="100%" stop-color="#ff6b6b"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" rx="12" fill="url(#s14bg)"/>
  <rect x="0" y="0" width="900" height="4" rx="2" fill="url(#s14t)"/>
  <text x="450" y="34" font-family="monospace" font-size="21" font-weight="800" fill="url(#s14t)" text-anchor="middle" letter-spacing="4">📬  LET'S BUILD GREAT THINGS</text>
  <rect x="0" y="52" width="900" height="4" rx="2" fill="url(#s14t)"/>
</svg>
</div>

<br/>

<div align="center">

### 💼 Open to Freelance · Collaborations · Full-Time Opportunities
*Fast delivery · Clean code · Pixel-perfect design · Worldwide clients*

<br/>

[![Portfolio](https://img.shields.io/badge/🌐_Visit_Portfolio-ff6b6b?style=for-the-badge&labelColor=1a0000)](https://vishanrabari.vercel.app)
[![Email](https://img.shields.io/badge/📧_Email_Me-ffd93d?style=for-the-badge&labelColor=151000)](mailto:rabarivishan2@gmail.com)
[![WhatsApp](https://img.shields.io/badge/💬_WhatsApp-c8ff00?style=for-the-badge&labelColor=001200)](https://wa.me/918141314836)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-4d96ff?style=for-the-badge&labelColor=00061a)](https://www.linkedin.com/in/vishan-rabari-7634ab392)
[![Instagram](https://img.shields.io/badge/📸_Instagram-f472b6?style=for-the-badge&labelColor=1a001a)](https://www.instagram.com/thevishandeveloper7)
[![Facebook](https://img.shields.io/badge/📘_Facebook-00e5ff?style=for-the-badge&labelColor=001a22)](https://www.facebook.com/share/1hkuo3wwlq/)

<br/>

|📡 Platform|🔗 Link|
|:---:|:---|
|🌐 Portfolio|[vishanrabari.vercel.app](https://vishanrabari.vercel.app)|
|💼 LinkedIn|[vishan-rabari-7634ab392](https://www.linkedin.com/in/vishan-rabari-7634ab392)|
|🐙 GitHub|[Vishandeveloper29](https://github.com/Vishandeveloper29)|
|📸 Instagram|[@thevishandeveloper7](https://www.instagram.com/thevishandeveloper7)|
|📘 Facebook|[Vishan Rabari](https://www.facebook.com/share/1hkuo3wwlq/)|
|📧 Gmail|rabarivishan2@gmail.com|
|📱 WhatsApp|[+91 81413 14836](https://wa.me/918141314836)|
|📍 Location|Gandhidham, Gujarat 370210, India|
|📄 Resume|[View on Google Drive](https://drive.google.com/file/d/1upMC-OW445YW8oTZR3RY_UZ8RA6wsmvX/view)|

</div>

<br/>

---

<!-- ░░░░░░░░░░░░░░░ FOOTER ░░░░░░░░░░░░░░░ -->

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=18&pause=900&color=C8FF00&center=true&vCenter=true&width=800&lines=Thanks+for+visiting!+⭐+Star+my+repos!;Always+open+to+freelance+%26+collaborations+🤝;Code+is+not+just+logic+—+it's+Art+✨;Let's+connect+%26+build+something+amazing+🚀" alt="Footer Typing"/>
</div>

<br/>

<div align="center">
  <i>✨ <b>"Crafting pixel-perfect, interactive web experiences — one line at a time."</b></i><br/>
  <b>— Vishan Rabari</b>
</div>

<br/>

<div align="center">

![Views](https://komarev.com/ghpvc/?username=Vishandeveloper29&label=👁️+Total+Profile+Views&color=0d0221&style=for-the-badge&labelColor=c77dff)
&nbsp;
![Made](https://img.shields.io/badge/Made_with-❤️_in_Gujarat_India-ff6b6b?style=for-the-badge&labelColor=1a0000)
&nbsp;
![Stars](https://img.shields.io/badge/⭐_Star_This-If_You_Like_It!-ffd93d?style=for-the-badge&labelColor=151000)

</div>

<br/>

<!-- FOOTER BANNER -->
<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 130" width="100%">
  <defs>
    <linearGradient id="ftBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   stop-color="#04101f"/>
      <stop offset="50%"  stop-color="#0d0221"/>
      <stop offset="100%" stop-color="#04101f"/>
    </linearGradient>
    <linearGradient id="ftRainbow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#ff6b6b"/>
      <stop offset="16%"  stop-color="#ffd93d"/>
      <stop offset="33%"  stop-color="#c8ff00"/>
      <stop offset="50%"  stop-color="#00e5ff"/>
      <stop offset="66%"  stop-color="#4d96ff"/>
      <stop offset="83%"  stop-color="#c77dff"/>
      <stop offset="100%" stop-color="#f472b6"/>
    </linearGradient>
    <filter id="glow3">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="900" height="130" fill="url(#ftBg)"/>
  <path d="M0,35 Q225,10 450,32 Q675,54 900,26 L900,0 L0,0 Z" fill="#04101f" opacity="0.6"/>
  <!-- particles -->
  <circle cx="80"  cy="92" r="4" fill="#ff6b6b" opacity="0.8" filter="url(#glow3)"/>
  <circle cx="200" cy="78" r="3" fill="#ffd93d" opacity="0.7" filter="url(#glow3)"/>
  <circle cx="350" cy="102" r="3.5" fill="#c8ff00" opacity="0.7" filter="url(#glow3)"/>
  <circle cx="550" cy="80" r="3" fill="#00e5ff" opacity="0.7" filter="url(#glow3)"/>
  <circle cx="700" cy="98" r="4" fill="#c77dff" opacity="0.8" filter="url(#glow3)"/>
  <circle cx="830" cy="82" r="3.5" fill="#f472b6" opacity="0.7" filter="url(#glow3)"/>
  <!-- text -->
  <text x="450" y="72" font-family="monospace" font-size="26" font-weight="900"
        fill="url(#ftRainbow)" text-anchor="middle" letter-spacing="5" filter="url(#glow3)">Let's Build Great Things! 🚀</text>
  <text x="450" y="98" font-family="monospace" font-size="12" fill="#64748b" text-anchor="middle" letter-spacing="2">© 2026 Vishan Rabari — Built with passion in Gujarat, India</text>
  <rect x="0" y="124" width="900" height="6" fill="url(#ftRainbow)"/>
</svg>
</div>
