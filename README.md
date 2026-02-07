<div align="center">

<!-- Header Banner -->
<img src="./assets/header.svg" alt="header" width="100%" />

<!-- Live Typewriter Intro -->
<h1 align="center">
  <span id="typewriter" style="
    font-family: 'Space Grotesk', sans-serif;
    font-weight: 600;
    font-size: 32px;
    color: #E57DA2;
  "></span>
  <span id="cursor" style="
    display: inline-block;
    width: 8px;
    height: 26px;
    background: #E57DA2;
    margin-left: 6px;
    border-radius: 4px;
    animation: blink 1s infinite;
  "></span>
</h1>

<!-- Cursor Animation -->
<style>
@keyframes blink {
  0%, 50%, 100% { opacity: 1; }
  25%, 75% { opacity: 0; }
}
</style>

<!-- Typewriter Logic -->
<script>
const phrases = [
  "Hi, I'm Kamala",
  "I'm a CS Grad Student",
  "I'm an AI/ML Researcher",
  "I study LLM reasoning",
  "I work on context window limits",
  "I build systems that ship"
];

const el = document.getElementById("typewriter");

let phraseIndex = 0;
let charIndex = 0;
let deleting = false;

function typeLoop() {
  const current = phrases[phraseIndex];

  if (!deleting) {
    el.textContent = current.slice(0, ++charIndex);
    if (charIndex === current.length) {
      setTimeout(() => deleting = true, 1200);
    }
  } else {
    el.textContent = current.slice(0, --charIndex);
    if (charIndex === 0) {
      deleting = false;
      phraseIndex = (phraseIndex + 1) % phrases.length;
    }
  }

  setTimeout(typeLoop, deleting ? 40 : 70);
}

typeLoop();
</script>

<p align="center">
  <img src="./assets/divider.svg" alt="divider" width="80%" />
</p>

<!-- Bio (Static, Minimal) -->
<p style="font-size: 15px; color: #8e2a4d; line-height: 1.8; max-width: 620px; margin: 18px auto;">
  Graduate student in Computer Science focused on AI/ML and large language models ◇ Researching practical failures in LLM reasoning with an emphasis on context window limitations ✦ Former software engineering intern who built and shipped end-to-end systems including data tooling, voice agents, notetaking assistants, and production web platforms ◇ Currently exploring Reinforcement Learning and Graph ML
</p>

<p align="center">
  <img src="./assets/divider.svg" alt="divider" width="80%" />
</p>

<!-- Social Links -->
<p align="center">
  <a href="https://linkedin.com/in/yourprofile">
    <img src="./assets/linkedin-badge.svg" alt="LinkedIn" />
  </a>
  <a href="https://medium.com/@yourprofile">
    <img src="./assets/medium-badge.svg" alt="Medium" />
  </a>
  <a href="https://yourname.github.io">
    <img src="./assets/website-badge.svg" alt="Website" />
  </a>
  <a href="mailto:your.email@example.com">
    <img src="./assets/email-badge.svg" alt="Email" />
  </a>
</p>

<p align="center">
  <img src="./assets/divider.svg" alt="divider" width="80%" />
</p>

<!-- Stats -->
## ◇ Stats & Highlights

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=dracula&bg_color=ffffff&title_color=e57da2&text_color=8e2a4d&icon_color=f6b4c3&border_color=f1a2b7&border_radius=15" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=dracula&background=ffffff&stroke=f1a2b7&ring=e57da2&fire=db4f7d&currStreakLabel=8e2a4d&sideLabels=c72b5e&currStreakNum=8e2a4d&sideNums=8e2a4d&border=f1a2b7&border_radius=15" width="48%" />

</div>

<p align="center">
  <img src="./assets/divider.svg" alt="divider" width="80%" />
</p>

<!-- Tech Stack -->
## ✦ Tech Stack

<div align="center">

### Languages
<img src="https://img.shields.io/badge/Python-ed8ea9?style=for-the-badge&logo=python&logoColor=8e2a4d" />
<img src="https://img.shields.io/badge/JavaScript-f6b4c3?style=for-the-badge&logo=javascript&logoColor=8e2a4d" />
<img src="https://img.shields.io/badge/TypeScript-f1a2b7?style=for-the-badge&logo=typescript&logoColor=8e2a4d" />

### Frameworks & Tools
<img src="https://img.shields.io/badge/React-f6b4c3?style=for-the-badge&logo=react&logoColor=8e2a4d" />
<img src="https://img.shields.io/badge/Node.js-ed8ea9?style=for-the-badge&logo=node.js&logoColor=8e2a4d" />
<img src="https://img.shields.io/badge/Docker-e57da2?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Figma-f1a2b7?style=for-the-badge&logo=figma&logoColor=8e2a4d" />

</div>

<p align="center">
  <img src="./assets/divider.svg" alt="divider" width="80%" />
</p>

<!-- Currently -->
## ◇ Currently

```js
const currentFocus = {
  research: ["LLM Reasoning", "Context Windows", "Agents"],
  learning: ["Reinforcement Learning", "Graph ML"],
  building: ["AI Systems", "Research Tooling"],
  interests: ["Clean Design", "Minimal Interfaces"]
};
<p align="center"> <img src="./assets/divider.svg" alt="divider" width="80%" /> </p> <!-- Contribution Graph -->
✦ Contribution Graph
<div align="center"> <img src="https://github-readme-activity-graph.vercel.app/graph?username=yourusername&bg_color=ffffff&color=8e2a4d&line=e57da2&point=f6b4c3&area=true&area_color=f1a2b7&border_color=f1a2b7&radius=15" width="95%" /> </div> <p align="center"> <img src="./assets/divider.svg" alt="divider" width="80%" /> </p> <!-- Footer -->
✦ Let’s Connect ◇
<p style="color: #b12b4f; font-size: 14px;"> Open to collaborations in AI/ML, LLM reasoning, agents, reinforcement learning, and graph-based learning systems </p> <img src="https://komarev.com/ghpvc/?username=yourusername&label=Profile+Views&color=f6b4c3&style=for-the-badge" /> <img src="./assets/footer.svg" alt="footer" width="100%" />

<sub>✦ Crafted with code, curiosity, and intent ◇</sub>

</div> ```
