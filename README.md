
<div align="center">

<!-- ANIMATED TYPING HEADER -->
<a href="https://github.com/Berkeipekci">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=800&color=00FFD1&center=true&vCenter=true&multiline=false&repeat=true&width=600&height=60&lines=Building+Health+Tech+%F0%9F%A9%BA;T%C3%9CB%C4%B0TAK+Researcher+%F0%9F%94%AC;MIS+Student+%F0%9F%8E%93;Bridging+Medicine+%26+Code+%E2%9A%95%EF%B8%8F" alt="Typing SVG" />
</a>

<br/>

<!-- ECG / HEARTBEAT ANIMATED BANNER -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" width="100%" height="80">
  <defs>
    <linearGradient id="ecgGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117;stop-opacity:1" />
      <stop offset="20%" style="stop-color:#0d1117;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#00FFD1;stop-opacity:1" />
      <stop offset="80%" style="stop-color:#0d1117;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0d1117;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <style>
      .ecg-line {
        stroke-dasharray: 1200;
        stroke-dashoffset: 1200;
        animation: drawECG 3s ease-in-out infinite;
      }
      @keyframes drawECG {
        0%   { stroke-dashoffset: 1200; opacity: 0.2; }
        40%  { stroke-dashoffset: 0;    opacity: 1; }
        70%  { stroke-dashoffset: 0;    opacity: 1; }
        100% { stroke-dashoffset: -1200; opacity: 0.2; }
      }
    </style>
  </defs>
  <rect width="1200" height="120" fill="#0d1117"/>
  <!-- Grid lines -->
  <line x1="0" y1="60" x2="1200" y2="60" stroke="#1a2a2a" stroke-width="1" stroke-dasharray="4,8"/>
  <line x1="0" y1="30" x2="1200" y2="30" stroke="#1a2a2a" stroke-width="0.5" stroke-dasharray="2,10"/>
  <line x1="0" y1="90" x2="1200" y2="90" stroke="#1a2a2a" stroke-width="0.5" stroke-dasharray="2,10"/>
  <!-- ECG Waveform Path -->
  <path class="ecg-line"
    d="M0,60 L80,60 L100,60 L110,55 L120,60 L130,60
       L200,60 L220,60 L230,20 L240,95 L250,15 L260,60
       L270,60 L280,55 L290,60 L300,60
       L380,60 L400,60 L410,55 L420,60 L430,60
       L500,60 L520,60 L530,20 L540,95 L550,15 L560,60
       L570,60 L580,55 L590,60 L600,60
       L680,60 L700,60 L710,55 L720,60 L730,60
       L800,60 L820,60 L830,20 L840,95 L850,15 L860,60
       L870,60 L880,55 L890,60 L900,60
       L980,60 L1000,60 L1010,55 L1020,60 L1030,60
       L1100,60 L1120,60 L1130,20 L1140,95 L1150,15 L1160,60
       L1200,60"
    fill="none" stroke="#00FFD1" stroke-width="2.5" filter="url(#glow)"
  />
</svg>

<br/>

<!-- PROFILE BADGES ROW -->
![Profile Views](https://komarev.com/ghpvc/?username=Berkeipekci&color=00FFD1&style=for-the-badge&label=PROFILE+VIEWS)
&nbsp;
[![GitHub followers](https://img.shields.io/github/followers/Berkeipekci?color=00FFD1&logo=github&style=for-the-badge&label=FOLLOWERS)](https://github.com/Berkeipekci)
&nbsp;
![TÜBİTAK Researcher](https://img.shields.io/badge/TÜBİTAK-Researcher-00FFD1?style=for-the-badge&logo=researchgate&logoColor=white)
&nbsp;
![Health Tech](https://img.shields.io/badge/Health%20Tech-Innovator-FF6B9D?style=for-the-badge&logo=heart&logoColor=white)

</div>

---

## 🧬 About Me

```python
class HealthTechDeveloper:
    def __init__(self):
        self.name         = "Muhammed Berke İpekçi"
        self.role         = "Final-Year MIS Student & TÜBİTAK Researcher"
        self.university   = "Management Information Systems"
        self.location     = "Türkiye 🇹🇷"
        self.focus        = ["Health Tech", "Medical Data Science", "Digital Transformation"]
        self.mission      = "Bridging the gap between medicine and code"

    @property
    def origin_story(self):
        return (
            "My father spent 17+ years in the medical device industry. "
            "Watching him navigate complex systems sparked a fire in me — "
            "to build the digital infrastructure that healthcare deserves."
        )

    def current_projects(self):
        return {
            "HealthyCRM" : "TÜBİTAK-funded CRM process model for the medical device sector",
            "MedFlow Lite": "Full-featured Android app for medical device field installations",
        }

    def life_philosophy(self):
        print("Every line of code is a heartbeat for better healthcare. 🩺")

me = HealthTechDeveloper()
me.life_philosophy()
# Output: Every line of code is a heartbeat for better healthcare. 🩺
```

---

## 🚀 Featured Projects

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### 🏥 HealthyCRM
> *TÜBİTAK-Funded Research Project*

A next-generation **CRM process model** purpose-built for the **medical device sector**. Designed to streamline customer relationship workflows, regulatory compliance tracking, and after-sales service management — filling a critical gap in healthcare operations infrastructure.

**Highlights:**
- 📐 Domain-specific CRM architecture for MedTech
- 🔬 Research-grade methodology (TÜBİTAK funded)
- 📊 Data-driven process optimization
- 🔗 Bridging sales, service & regulatory workflows

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![ML](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

</td>
<td width="50%" valign="top">

### 📱 MedFlow Lite
> *Android Field Operations App*

A **full-featured Android application** engineered for medical device **field installation teams**. Empowers technicians with real-time checklists, device commissioning workflows, digital documentation, and field-to-office data sync — replacing paper-based chaos with precision.

**Highlights:**
- 📋 Digital installation & commissioning checklists
- 🔄 Real-time field-to-office synchronization
- 📸 In-app documentation & photo capture
- 🛠️ Device lifecycle tracking on the go

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

</td>
</tr>
</table>

</div>

---

## 🛠️ Tech Stack & Skills

<div align="center">

### 💻 Languages
[![Python](https://skillicons.dev/icons?i=python)](https://www.python.org/)&nbsp;
[![JavaScript](https://skillicons.dev/icons?i=js)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)&nbsp;
[![C](https://skillicons.dev/icons?i=c)](https://en.wikipedia.org/wiki/C_(programming_language))&nbsp;
[![Java](https://skillicons.dev/icons?i=java)](https://www.java.com/)&nbsp;
[![Kotlin](https://skillicons.dev/icons?i=kotlin)](https://kotlinlang.org/)&nbsp;
[![HTML](https://skillicons.dev/icons?i=html)](https://developer.mozilla.org/en-US/docs/Web/HTML)&nbsp;
[![CSS](https://skillicons.dev/icons?i=css)](https://developer.mozilla.org/en-US/docs/Web/CSS)

### 🗄️ Data & ML
[![PostgreSQL](https://skillicons.dev/icons?i=postgres)](https://www.postgresql.org/)&nbsp;
[![MySQL](https://skillicons.dev/icons?i=mysql)](https://www.mysql.com/)&nbsp;
[![TensorFlow](https://skillicons.dev/icons?i=tensorflow)](https://www.tensorflow.org/)&nbsp;
[![sklearn](https://skillicons.dev/icons?i=sklearn)](https://scikit-learn.org/)

### 📱 Mobile & Tools
[![Android](https://skillicons.dev/icons?i=androidstudio)](https://developer.android.com/studio)&nbsp;
[![Git](https://skillicons.dev/icons?i=git)](https://git-scm.com/)&nbsp;
[![GitHub](https://skillicons.dev/icons?i=github)](https://github.com/)&nbsp;
[![VSCode](https://skillicons.dev/icons?i=vscode)](https://code.visualstudio.com/)&nbsp;
[![Linux](https://skillicons.dev/icons?i=linux)](https://www.linux.org/)

</div>

<br/>

<div align="center">

| Domain | Tools & Technologies |
|--------|---------------------|
| 🤖 **Machine Learning** | Scikit-Learn · Pandas · NumPy · Matplotlib |
| 🎨 **Frontend** | HTML5 · CSS3 · JavaScript · Canvas API |
| 🗃️ **Databases** | SQL · PostgreSQL · MySQL · SQLite |
| 📱 **Mobile** | Android (Java / Kotlin) · Android Studio |
| 🔬 **Research** | Data Analysis · Process Modeling · CRM Architecture |

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Berkeipekci&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00FFD1&icon_color=00FFD1&text_color=c9d1d9&ring_color=00FFD1" alt="GitHub Stats"/>
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=Berkeipekci&theme=tokyonight&hide_border=true&background=0d1117&ring=00FFD1&fire=FF6B9D&currStreakLabel=00FFD1&sideLabels=00FFD1" alt="GitHub Streak"/>

<br/><br/>

<img width="42%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Berkeipekci&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00FFD1&text_color=c9d1d9&langs_count=8" alt="Top Languages"/>
&nbsp;&nbsp;
<img width="54%" src="https://github-readme-activity-graph.vercel.app/graph?username=Berkeipekci&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00FFD1&line=00FFD1&point=FF6B9D&area=true&area_color=00FFD1" alt="Contribution Graph"/>

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Berkeipekci/Berkeipekci/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Berkeipekci/Berkeipekci/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/Berkeipekci/Berkeipekci/output/github-snake-dark.svg" />
</picture>

> ⚙️ *To enable the snake animation, add a [GitHub Actions workflow](https://github.com/Platane/snk) to your repo that generates the SVG on a schedule.*

</div>

---

## 🌱 Current Focus

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                    2025 RESEARCH ROADMAP                     ║
╠══════════════════════════════════════════════════════════════╣
║  🔬  Finalizing HealthyCRM model for TÜBİTAK submission      ║
║  📱  Expanding MedFlow Lite with IoT device integration      ║
║  🤖  Applying ML to medical device failure prediction        ║
║  📊  Exploring digital transformation in Turkish MedTech     ║
║  🎓  Completing MIS degree with honors                       ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

---

## 💡 Health Tech Philosophy

<div align="center">

> *"My father spent over 17 years in the field — installing, maintaining, and troubleshooting medical devices that kept people alive.*
> *He navigated that world with paper forms, fragmented systems, and sheer expertise.*
> *I build software so the next generation of medical device professionals doesn't have to.*
> **Every feature I ship is for him, and for the patients at the end of the chain."***

</div>

---

## 🤝 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/berkeipekci/)
&nbsp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Berke.ipekci@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Berkeipekci)
&nbsp;
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white)](https://researchgate.net)

<br/>

**Open to:** Research collaborations · Health tech internships · MedTech startup conversations

</div>

---

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 40" width="80%" height="40">
  <defs>
    <style>
      .pulse {
        stroke-dasharray: 800;
        stroke-dashoffset: 800;
        animation: pulse 4s ease-in-out infinite;
      }
      @keyframes pulse {
        0%   { stroke-dashoffset: 800; }
        50%  { stroke-dashoffset: 0; }
        100% { stroke-dashoffset: -800; }
      }
    </style>
  </defs>
  <rect width="800" height="40" fill="#0d1117" rx="6"/>
  <path class="pulse"
    d="M0,20 L60,20 L75,20 L82,10 L88,28 L93,5 L99,20 L106,20 L115,20
       L175,20 L190,20 L197,10 L203,28 L208,5 L214,20 L221,20 L230,20
       L290,20 L305,20 L312,10 L318,28 L323,5 L329,20 L336,20 L345,20
       L405,20 L420,20 L427,10 L433,28 L438,5 L444,20 L451,20 L460,20
       L520,20 L535,20 L542,10 L548,28 L553,5 L559,20 L566,20 L575,20
       L635,20 L650,20 L657,10 L663,28 L668,5 L674,20 L681,20 L690,20
       L750,20 L765,20 L772,10 L778,28 L783,5 L789,20 L800,20"
    fill="none" stroke="#00FFD1" stroke-width="2" opacity="0.8"
  />
</svg>

<br/>

*Made with* ❤️ *for the intersection of medicine & technology*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=80&section=footer&animation=twinkling)

</div>
