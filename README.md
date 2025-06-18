<p align="center">
<svg width="100%" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Banner Team X Nexus">
    <style>
        .bg { fill: #101010; }
        .text {
            font-family: 'Courier New', Courier, monospace;
            font-size: 50px;
            font-weight: bold;
            text-anchor: middle;
            dominant-baseline: middle;
            letter-spacing: 2px;
        }
        .main-text {
            fill: #ff0000;
            filter: url(#glow); /* Terapkan efek glow */
            animation: text-flicker 3s infinite alternate;
        }
        .glitch-1 {
            fill: #00ffff; /* Warna Cyan untuk glitch */
            animation: glitch-anim-1 2s infinite alternate-reverse;
        }
        .glitch-2 {
            fill: #ff00ff; /* Warna Magenta untuk glitch */
            animation: glitch-anim-2 3s infinite alternate-reverse;
        }
        .scanline {
            fill: #ff0000;
            opacity: 0.3;
            animation: scanline-anim 4s infinite linear;
        }

        /* Keyframes untuk Animasi */
        @keyframes text-flicker {
            0% { opacity: 1; }
            50% { opacity: 0.8; }
            100% { opacity: 1; }
        }
        
        @keyframes scanline-anim {
            0% { transform: translateY(-10px); }
            100% { transform: translateY(210px); }
        }

        @keyframes glitch-anim-1 {
            0%, 100% { transform: translate(0, 0); clip-path: inset(0 0 0 0); }
            5% { transform: translate(3px, -2px); }
            10% { transform: translate(-3px, 2px); }
            15% { transform: translate(0, 0); clip-path: inset(20% 0 60% 0); }
            20% { clip-path: inset(80% 0 5% 0); }
            25%, 95% { clip-path: inset(0 0 0 0); }
            96% { transform: translate(4px, 3px); }
        }

        @keyframes glitch-anim-2 {
            0%, 100% { transform: translate(0, 0); }
            10% { transform: translate(-4px, 1px); }
            20% { transform: translate(4px, -1px); }
            80% { transform: translate(0, 0); }
        }
    </style>

    <defs>
        <filter id="glow">
            <feGaussianBlur stdDeviation="2.5" result="coloredBlur"></feGaussianBlur>
            <feMerge>
                <feMergeNode in="coloredBlur"></feMergeNode>
                <feMergeNode in="SourceGraphic"></feMergeNode>
            </feMerge>
        </filter>
    </defs>

    <rect class="bg" width="100%" height="100%"></rect>

    <g class="text">
        <text class="glitch-1" x="50%" y="50%">Team X Nexus</text>
        <text class="glitch-2" x="50%" y="50%">Team X Nexus</text>
        <text class="main-text" x="50%" y="50%">Team X Nexus</text>
    </g>

    <rect class="scanline" x="0" y="0" width="100%" height="4px"></rect>

</svg>
</p>

<div align="center">
  
**Offensive Security Operator | Adversary Emulation & Red Teaming**

</div>

I am an operator within **Team X Nexus**, a collective focused on advanced cybersecurity operations. My work centers on simulating sophisticated threat actors to test and enhance the security posture of complex digital environments.

- 🔭 My current focus: **EDR Evasion & C2 Framework Development.**
- 🌱 Continuously analyzing: **Latest APT Tactics, Techniques, and Procedures (TTPs).**
- 📫 Professional Inquiries: **qwertyknock69@gmail.com**

---

### 🛠️ Core Arsenal & Technologies

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kali%20Linux-26A4E2?style=for-the-badge&logo=kalilinux&logoColor=white"/>
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6600?style=for-the-badge&logo=burpsuite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nmap-FF6F61?style=for-the-badge&logo=nmap&logoColor=white"/>
</p>

---

### 📊 Contribution Graph & Stats

<p align="center">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=Zxhell27&show_icons=true&locale=en&theme=tokyonight" alt="github stats" />
</p>
