<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <style>
    body {
      background: linear-gradient(135deg, #0c0c0c 0%, #1a1a2e 50%, #16213e 100%);
      color: #ffffff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }
    .portal {
      text-align: center;
      margin: 50px 0;
      animation: glow 2s ease-in-out infinite alternate;
    }
    @keyframes glow {
      from { text-shadow: 0 0 20px #FFD700; }
      to { text-shadow: 0 0 30px #FFD700, 0 0 40px #FFD700; }
    }
    .card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 215, 0, 0.3);
      border-radius: 15px;
      padding: 20px;
      margin: 20px 0;
      backdrop-filter: blur(10px);
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
    }
    .tech-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
      gap: 20px;
      margin: 20px 0;
    }
    .tech-item {
      text-align: center;
      padding: 15px;
      background: rgba(255, 215, 0, 0.1);
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .tech-item:hover {
      transform: translateY(-5px);
    }
    .stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      margin: 20px 0;
    }
    .project-card {
      background: linear-gradient(135deg, rgba(255, 215, 0, 0.1), rgba(0, 255, 255, 0.1));
      border: 1px solid rgba(255, 215, 0, 0.5);
      border-radius: 15px;
      padding: 20px;
      margin: 20px 0;
      position: relative;
      overflow: hidden;
    }
    .project-card::before {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(255, 215, 0, 0.2), transparent);
      transition: left 0.5s;
    }
    .project-card:hover::before {
      left: 100%;
    }
    .social-links {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin: 30px 0;
    }
    .social-link {
      display: inline-block;
      padding: 12px 24px;
      background: linear-gradient(45deg, #FFD700, #FFA500);
      color: #000;
      text-decoration: none;
      border-radius: 25px;
      font-weight: bold;
      transition: all 0.3s;
      box-shadow: 0 4px 15px rgba(255, 215, 0, 0.3);
    }
    .social-link:hover {
      transform: translateY(-3px);
      box-shadow: 0 6px 20px rgba(255, 215, 0, 0.5);
    }
    .ascii-art {
      font-family: monospace;
      white-space: pre;
      color: #FFD700;
      text-align: center;
      margin: 20px 0;
    }
    .timeline {
      position: relative;
      margin: 50px 0;
    }
    .timeline::before {
      content: '';
      position: absolute;
      left: 50%;
      top: 0;
      bottom: 0;
      width: 2px;
      background: linear-gradient(to bottom, #FFD700, #FFA500, #FFD700);
      transform: translateX(-50%);
    }
    .timeline-item {
      margin: 40px 0;
      position: relative;
    }
    .timeline-item:nth-child(even) {
      text-align: right;
      padding-right: 60px;
    }
    .timeline-item:nth-child(odd) {
      text-align: left;
      padding-left: 60px;
    }
    .timeline-dot {
      position: absolute;
      left: 50%;
      top: 50%;
      transform: translate(-50%, -50%);
      width: 20px;
      height: 20px;
      background: #FFD700;
      border-radius: 50%;
      border: 3px solid #000;
    }
  </style>
</head>
<body>
  <div class="container">

    <!-- PORTAL ENTRANCE -->
    <div class="portal">
      <h1 style="font-size: 4em; margin: 0; color: #FFD700;">🌟 PORTAL TO INFINITY 🌟</h1>
      <p style="font-size: 1.5em; color: #00FFFF;">Welcome, Traveler. You have entered the Digital Dimension of Sanjay V.</p>
      <div class="ascii-art">
   _____
  /     \
 |  🚀  |
  \_____/
     |
    / \
   |   |
    \ /
     V
      </div>
    </div>

    <!-- HERO SECTION -->
    <div class="card">
      <p align="center">
        <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:FFD700&height=260&section=header&text=SANJAY%20V&fontSize=50&fontColor=FFD700&animation=fadeIn&fontAlignY=35" />
      </p>
      <p align="center">
        <img src="https://readme-typing-svg.herokuapp.com?color=FFD700&size=26&center=true&vCenter=true&width=700&lines=Welcome+to+the+Matrix+of+Code;Where+Algorithms+Become+Art;Building+Tomorrow's+Innovations+Today;Explorer+of+Infinite+Possibilities;Join+the+Revolution+of+Creativity!" />
      </p>
    </div>

    <!-- STORY INTRODUCTION -->
    <div class="card">
      <h2 style="text-align: center; color: #FFD700;">📖 The Legend Begins</h2>
      <p style="text-align: center; font-size: 1.2em; line-height: 1.6;">
        In the vast universe of code, I am <strong>Sanjay V</strong>, a digital architect forging pathways through the cosmos of technology.
        Armed with the spirit of a thousand adventures and the wisdom of countless algorithms, I transform ideas into reality.
        My journey is not just about writing code—it's about creating worlds, solving mysteries, and pushing the boundaries of what's possible.
      </p>
      <div style="text-align: center; margin: 20px 0;">
        <img src="https://media.giphy.com/media/3o7TKz9bX9Z8LxOq5K/giphy.gif" alt="Digital Adventure" width="300"/>
      </div>
      <blockquote style="border-left: 5px solid #FFD700; padding-left: 20px; font-style: italic; color: #00FFFF;">
        "In this digital realm, every bug is a dragon to slay, every feature is a treasure to uncover, and every project is an epic quest waiting to unfold."
      </blockquote>
    </div>

    <!-- JOURNEY TIMELINE -->
    <div class="timeline">
      <h2 style="text-align: center; color: #FFD700; margin-bottom: 50px;">🗺️ My Epic Journey</h2>

      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="card" style="margin: 0;">
          <h3>🎓 The Awakening</h3>
          <p>Embarked on the path of Computer Science Engineering, discovering the magic of programming.</p>
        </div>
      </div>

      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="card" style="margin: 0;">
          <h3>🌐 Web Development Mastery</h3>
          <p>Mastered the art of crafting immersive web experiences, turning concepts into interactive realities.</p>
        </div>
      </div>

      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="card" style="margin: 0;">
          <h3>🚀 Project Creation</h3>
          <p>Built real-world applications, from language translators to productivity tools, each a step in the grand adventure.</p>
        </div>
      </div>

      <div class="timeline-item">
        <div class="timeline-dot"></div>
        <div class="card" style="margin: 0;">
          <h3>🔮 Future Horizons</h3>
          <p>Exploring AI, machine learning, and innovative technologies to shape the future of digital experiences.</p>
        </div>
      </div>
    </div>

    <!-- TECH ARSENAL -->
    <div class="card">
      <h2 style="text-align: center; color: #FFD700;">⚔️ Arsenal of Technologies</h2>
      <div class="tech-grid">
        <div class="tech-item">
          <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="JavaScript" width="64" height="64" />
          <br><strong>JavaScript</strong>
          <p>The spellbook of interactivity</p>
        </div>
        <div class="tech-item">
          <img src="https://techstack-generator.vercel.app/react-icon.svg" alt="React" width="64" height="64" />
          <br><strong>React</strong>
          <p>Crafting dynamic interfaces</p>
        </div>
        <div class="tech-item">
          <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python" width="64" height="64" />
          <br><strong>Python</strong>
          <p>The serpent of versatility</p>
        </div>
        <div class="tech-item">
          <img src="https://techstack-generator.vercel.app/nodejs-icon.svg" alt="Node.js" width="64" height="64" />
          <br><strong>Node.js</strong>
          <p>Server-side sorcery</p>
        </div>
        <div class="tech-item">
          <img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="MySQL" width="64" height="64" />
          <br><strong>MySQL</strong>
          <p>Data vaults of wisdom</p>
        </div>
        <div class="tech-item">
          <img src="https://techstack-generator.vercel.app/github-icon.svg" alt="GitHub" width="64" height="64" />
          <br><strong>GitHub</strong>
          <p>The forge of collaboration</p>
        </div>
      </div>
    </div>

    <!-- PROJECTS GALAXY -->
    <div class="card">
      <h2 style="text-align: center; color: #FFD700;">🚀 Featured Quests (Projects)</h2>

      <div class="project-card">
        <h3>🌐 English to Kannada Translator</h3>
        <p>A mystical bridge connecting languages across cultures, powered by advanced translation algorithms.</p>
        <div style="display: flex; gap: 10px; margin: 10px 0;">
          <img src="https://img.shields.io/badge/Live%20Demo-Active-brightgreen?style=flat-square&logo=vercel" alt="Live Demo"/>
          <img src="https://img.shields.io/badge/Tech-HTML%2FCSS%2FJS-blue?style=flat-square" alt="Tech Stack"/>
        </div>
        <p><strong>🔗 Portal:</strong> <a href="https://english-to-kannada-translator-4-omoa.onrender.com" style="color: #FFD700;">Enter the Translation Realm</a></p>
        <ul>
          <li>⚡ Instant linguistic teleportation</li>
          <li>🎨 Ethereal user interface design</li>
          <li>🌍 Cultural dimension bridging</li>
          <li>📱 Multi-device compatibility</li>
        </ul>
      </div>

      <div class="project-card">
        <h3>📊 Attendance Tracker System</h3>
        <p>A powerful artifact for monitoring presence and calculating mystical percentages in educational realms.</p>
        <div style="display: flex; gap: 10px; margin: 10px 0;">
          <img src="https://img.shields.io/badge/Live%20Demo-Active-brightgreen?style=flat-square&logo=vercel" alt="Live Demo"/>
          <img src="https://img.shields.io/badge/Tech-HTML%2FCSS%2FJS-blue?style=flat-square" alt="Tech Stack"/>
        </div>
        <p><strong>🔗 Portal:</strong> <a href="https://attendance-tracker-6-xysf.onrender.com" style="color: #FFD700;">Access the Tracking Dimension</a></p>
        <ul>
          <li>📈 Real-time attendance sorcery</li>
          <li>📊 Percentage calculation magic</li>
          <li>🎯 Intuitive interface design</li>
        </ul>
      </div>

      <div style="text-align: center; margin: 30px 0;">
        <img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" alt="More Coming" width="200"/>
        <p style="font-size: 1.2em; color: #00FFFF;">More legendary projects are forging in the depths... Stay tuned!</p>
      </div>
    </div>

    <!-- ANALYTICS REALM -->
    <div class="card">
      <h2 style="text-align: center; color: #FFD700;">📊 Analytics Dimension</h2>
      <div class="stats-grid">
        <div>
          <img src="https://github-readme-stats.vercel.app/api?username=Sanju143v&show_icons=true&theme=dark&hide_border=true&bg_color=000000&title_color=FFD700&text_color=FFFFFF&icon_color=FFD700" alt="GitHub Stats" />
        </div>
        <div>
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sanju143v&theme=dark&hide_border=true&background=000000&stroke=FFD700&ring=FFD700&fire=FFD700&currStreakLabel=FFD700" alt="GitHub Streak" />
        </div>
      </div>
      <div style="text-align: center; margin: 20px 0;">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sanju143v&layout=compact&theme=dark&hide_border=true&bg_color=000000&title_color=FFD700&text_color=FFFFFF" alt="Top Languages" />
      </div>
    </div>

    <!-- ACHIEVEMENTS HALL -->
    <div class="card">
      <h2 style="text-align: center; color: #FFD700;">🏆 Hall of Achievements</h2>
      <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px;">
        <div style="text-align: center; padding: 20px; background: rgba(255, 215, 0, 0.1); border-radius: 10px;">
          <h3>🚀 Project Deployments</h3>
          <p>Successfully launched multiple web applications to the cloud</p>
        </div>
        <div style="text-align: center; padding: 20px; background: rgba(255, 215, 0, 0.1); border-radius: 10px;">
          <h3>🌐 Language Bridge Builder</h3>
          <p>Created tools connecting diverse linguistic communities</p>
        </div>
        <div style="text-align: center; padding: 20px; background: rgba(255, 215, 0, 0.1); border-radius: 10px;">
          <h3>📚 Continuous Learning</h3>
          <p>Mastering new technologies and frameworks relentlessly</p>
        </div>
      </div>
    </div>

    <!-- CONNECT PORTAL -->
    <div class="card">
      <h2 style="text-align: center; color: #FFD700;">🌐 Dimensional Portals (Connect)</h2>
      <div class="social-links">
        <a href="https://github.com/Sanju143v" class="social-link">GitHub Realm</a>
        <a href="https://www.linkedin.com/in/sanjay-v-403966286/" class="social-link">LinkedIn Dimension</a>
        <a href="https://instagram.com/iamsanjay143" class="social-link">Instagram Universe</a>
        <a href="mailto:svsanju341@gmail.com" class="social-link">Email Nexus</a>
      </div>
    </div>

    <!-- FUN ZONE -->
    <div class="card">
      <h2 style="text-align: center; color: #FFD700;">🎭 Fun Dimension</h2>
      <div style="text-align: center;">
        <p style="font-size: 1.2em; color: #00FFFF;">Random facts about this digital explorer:</p>
        <ul style="list-style: none; padding: 0;">
          <li>🎯 Can debug code while dreaming</li>
          <li>☕ Powered by infinite coffee and curiosity</li>
          <li>🌟 Believes every bug is just a feature in disguise</li>
          <li>🚀 Dreams in algorithms and wakes up with solutions</li>
        </ul>
      </div>
    </div>

    <!-- EXIT PORTAL -->
    <div class="portal">
      <h2 style="color: #FFD700;">🌟 Thank You for Exploring</h2>
      <p style="color: #00FFFF;">You've journeyed through my digital universe. May your own adventures be filled with innovation and success!</p>
      <div class="ascii-art">
   _____
  /     \
 |  👋  |
  \_____/
     |
    / \
   |   |
    \ /
     V
      </div>
      <p style="color: #FFD700; font-size: 1.2em;">"Until our paths cross again in the code..."</p>
      <img src="https://visitor-badge.laobi.icu/badge?page_id=Sanju143v.Sanju143v" alt="Visitor Count"/>
    </div>

  </div>
</body>
</html>  

🛠️ Tech:
- HTML  
- CSS  
- JavaScript  

---

## 📊 Attendance Tracker System

🔗 Live: https://attendance-tracker-6-xysf.onrender.com  

📌 Features:
- Attendance tracking  
- Percentage calculation  
- Simple interface  

🛠️ Tech:
- HTML  
- CSS  
- JavaScript  

---
# 🧪 Experiment Zone

I like trying small ideas and turning them into projects.

Future ideas:
- AI-based tools  
- Real-world problem solvers  
- Productivity tools  

<!-- ===================== SKILLS ===================== -->
# 🧠 Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,python,git" />
</p>

---

<!-- ===================== STATS ===================== -->
# 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sanju143v&show_icons=true&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sanju143v&theme=tokyonight&hide_border=true" />
</p>

---

<!-- ===================== GRAPH ===================== -->
# 📈 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Sanju143v&theme=react-dark" />
</p>

---

<!-- ===================== TIMELINE ===================== -->
# 🧭 Developer Timeline

- Started learning programming  
- Built first mini projects  
- Created real-world applications  
- Improving consistency daily  

---

<!-- ===================== MINDSET ===================== -->
# ⚡ Developer Mindset

```
while(alive){
    learn();
    build();
    fail();
    improve();
}
```

---

<!-- ===================== PERSONAL BRAND ===================== -->
# 🧠 What Makes Me Different

- I focus on building instead of just watching tutorials  
- I prefer simple and useful solutions  
- I am consistent even when motivation is low  

---

<!-- ===================== CONNECT ===================== -->
# 🌐 Connect With Me

<p align="center">
  <a href="mailto:svsanju341@gmail.com">📧 Email</a> •
  <a href="https://www.linkedin.com/in/sanjay-v-403966286/">💼 LinkedIn</a> •
  <a href="https://instagram.com/iamsanjay143">📷 Instagram</a>
</p>

---

<!-- ===================== VISITOR ===================== -->
# 👀 Visitors

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Sanju143v&color=blue&style=flat-square" />
</p>

---

<!-- ===================== FOOTER ===================== -->
<p align="center">
  ⚡ Building step by step. Improving every day.
</p>
![Snake animation](https://github.com/Sanju143v/snake-game/blob/output/snake.svg)
