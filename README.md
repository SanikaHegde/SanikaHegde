<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=auto&height=250&section=header&text=Sanika%20Hegde&fontSize=70&animation=fadeIn&fontAlignY=35&desc=Full%20Stack%20Developer%20|%20AI%20&%20Data%20Science&descSize=20&descAlignY=60" />
</p>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=30&pause=1000&color=FF3366&center=true&vCenter=true&width=600&lines=Coding+the+Future;Building+Scalable+Solutions;Data-Driven+Innovation" alt="Typing SVG" />
</div>

---

## 🚀 About Me

<table border="0">
  <tr>
    <td width="60%" valign="top">
      <p>
        I'm a <b>Full Stack Developer</b> and <b>Data Science Enthusiast</b> who loves turning complex problems into elegant, high-performance solutions. 
      </p>
      <ul>
        <li>🔥 **Expertise:** Full Stack Web Development & Machine Learning</li>
        <li>💡 **Philosophy:** Data-driven logic meets creative UI</li>
        <li>🎓 **Learning:** Advanced Deep Learning & Cloud Scalability</li>
        <li>📫 **Reach me:** [sanisanika10@gmail.com](mailto:sanisanika10@gmail.com)</li>
      </ul>
      <p align="left">
        <a href="https://www.linkedin.com/in/sanika-h-r-a34029259"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
        <a href="mailto:sanisanika10@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
      </p>
    </td>
    <td width="40%" valign="top">
      <img src="https://github-readme-stats.vercel.app/api?username=SanikaHegde&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="Sanika's GitHub Stats" width="100%"/>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">
  <table border="0">
    <tr>
      <td align="center"><b>Frontend & Backend</b></td>
      <td align="center"><b>Data & AI</b></td>
      <td align="center"><b>Tools</b></td>
    </tr>
    <tr>
      <td>
        <img src="https://skillicons.dev/icons?i=js,react,html,css,tailwind,mongodb,mysql&perline=4" />
      </td>
      <td>
        <img src="https://skillicons.dev/icons?i=py,jupyter,pandas,numpy&perline=2" />
      </td>
      <td>
        <img src="https://skillicons.dev/icons?i=vscode,git,github,postman&perline=2" />
      </td>
    </tr>
  </table>
</div>

---

## 📈 Activity & Impact

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SanikaHegde&theme=radical&hide_border=true&area=true" width="100%" />
</div>

<br />

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SanikaHegde&layout=compact&theme=radical&hide_border=true&hide=jupyter%20notebook" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SanikaHegde&theme=radical&hide_border=true" />
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <img src="https://raw.githubusercontent.com/SanikaHegde/SanikaHegde/output/github-contribution-grid-snake-dark.svg" alt="Snake Animation" />
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=SanikaHegde&label=PROFILE%20VIEWS&color=FF3366&style=for-the-badge" alt="Profile Views" />
</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=100&section=footer" />
</p>

<p align="center">
  <b><i>"Innovating with passion, coding with purpose."</i></b>
</p>

<!-- 
  ======================================================================
  🛠️ SETUP & AUTOMATION GUIDE (FOR COPY-PASTE)
  ======================================================================
  Everything below this line is for YOUR setup and won't be visible 
  until you click to expand. Click the "SNAKE AUTOMATION STEP" to copy 
  the code for your GitHub Action!
  ======================================================================
-->

<details>
<summary><b>🛠️ Setup & Automation Instructions (Click to Expand)</b></summary>

### 1. The README
Copy everything in this file (up to the "Innovating with passion" line) and paste it into the `README.md` of your special repository (the one named `SanikaHegde`).

### 2. Snake Automation Step (CRITICAL)
For the snake animation to work, you **MUST** create a new file in your GitHub repository at this exact path:
`.github/workflows/snake.yml`

**Copy and paste the code below into that file:**

```yaml
name: generate animation

on:
  schedule:
    - cron: "0 */24 * * *" 
  workflow_dispatch:
  push:
    branches:
    - main
    
jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10
    
    steps:
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
          
      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

### 3. Final Step
Commit and push these changes. Go to your GitHub **Actions** tab, click "generate animation", and click "Run workflow". Your snake will appear shortly!

</details>


