<!-- ANIMATED BANNER — capsule-render generates an SVG wave header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Kevin%20&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Fullstack%20Developer%20/%20Open%20Source%20Fan&descSize=16&descAlignY=55" />
</div>
<!-- TYPING SVG — simulates a terminal typing effect -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=4A9EFF&center=true&vCenter=true&width=600&lines=Hi+there!+I'm+Kevin+Moenga;Fullstack+Developer;Always+learning+new+things!" />
</div>

## About Me
- Currently working on some projects
- Learning **TypeScript & Node.js**
- Ask me about **PHP, CSS, HTML5, JS, MySQL**
- Reach me at **kmoenga2@gmail.com**
<!-- SOCIAL BADGES — shields.io badges with logo icons -->
<!-- SOCIAL BADGES -->
<div align="center">

<a href="https://www.linkedin.com/search/results/all/?keywords=Kevin%20Moenga" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/Moenga254" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.instagram.com/jvst.__.mk/" target="_blank">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
</a>

<a href="https://wa.me/254785721923" target="_blank">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>
<a href="https://moenga254.github.io/My-portfolio/" target="_blank">
  <img src="https://img.shields.io/badge/Portfolio-ff5252?style=for-the-badge&logo=google-chrome&logoColor=white"/>
</a>

</div>

<!-- STREAK STATS -->
<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Moenga254&theme=tokyonight&hide_border=true"/>

</div>

<!-- TECH BADGES — shields.io with simple-icons logos -->
## Tech Stack
**Languages**
<!-- TECH STACK -->
<h2 align="center">⚡ Tech Stack</h2>

<p align="center">
<img src="https://skillicons.dev/icons?i=html,css,js,react,php,mysql,vercel,git,github" />
</p>

<p align="center">
HTML5 • CSS3 • JavaScript • React • PHP • MySQL • Vercel • Git • GitHub • REST API
</p>

<!-- PROFILE VIEW COUNTER — komarev.com/ghpvc / visitorbadge.io -->
<!-- Place this near the top of your README -->

<!-- Option A: flat-square, subtle -->
<img src="https://komarev.com/ghpvc/?username=Moenga254&color=4a9eff&style=flat-square&label=Profile+Views" alt="Profile Views"/>

<!-- Option B: for-the-badge, bold -->
<img src="https://komarev.com/ghpvc/?username=Moenga254&color=ff5252&style=for-the-badge" alt="Profile Views"/>

<!-- Option C: visitorbadge.io alternative -->
<img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FMoenga254&label=Visitors&countColor=%234a9eff" alt="Visitors"/>

-- CONTRIBUTION SNAKE — Platane/snk GitHub Action -->
<!-- Step 1: create .github/workflows/snake.yml in your profile repo -->
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_USERNAME
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<!-- Step 2: add this to your README after the first workflow run -->
<picture>
  <source media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg">
  <img alt="contribution snake"
    src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg">
</picture>
