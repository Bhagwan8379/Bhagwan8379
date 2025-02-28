<!-- Profile Header -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&duration=2000&pause=1000&color=FF0000,FF7300,FFEE00,00FF00,00FFFF,007BFF,8A2BE2&center=true&vCenter=true&width=900&lines=Hi+%F0%9F%91%8B%2C+I'm+Bhagwan;Fullstack+Web+Developer;React+Native+Developer;Frontend+Developer;Graphic+Designer;JavaScript+%7C+React+%7C+React+Native+Expert;Building+Awesome+Projects!">
</p>



<!-- Fun SVG Animation -->
<p align="center">
  <img src="https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" width="50" />
</p>

<!-- Profile Views -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=bhagwan8379&label=Profile%20views&color=F7B93E&style=flat" alt="Profile Views" />
</p>

<!-- GitHub Trophies -->
<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=bhagwan8379&theme=onestar&no-frame=true&margin-w=10&column=6" alt="GitHub Trophies"/>
  </a>
</p>

<!-- 3D Stylish GitHub Contribution Graph -->
<p align="center">
  <img src="https://github.com/bhagwan8379/bhagwan8379/raw/output/github-snake-dark.svg" alt="VIP Styled Contribution Graph"/>
</p>


---

## 🔥 About Me
- 👨‍💻 All of my projects are available at [bhagwan-portfolio.com](https://bhagwan-portfolio.com)  
- 💬 Ask me about **React, React Native, JavaScript**  
- 📫 How to reach me **bhagwangire05@gmail.com**  
- ⚡ Hobbies **Listening to songs & traveling**  

---

## 🌐 Connect With Me:
<p align="center">
  <a href="https://www.linkedin.com/in/bhagwan-gire-84013a293" target="_blank">
    <img src="https://img.icons8.com/fluency/48/ff0000/linkedin.png" width="40" height="40" />
  </a>
  <a href="https://www.instagram.com/bhagwan_gire_96k" target="_blank">
    <img src="https://img.icons8.com/fluency/48/ff0000/instagram-new.png" width="40" height="40" />
  </a>
  <a href="https://leetcode.com/Bhagwan8379/" target="_blank">
    <img src="https://img.icons8.com/external-tal-revivo-bold-tal-revivo/48/ff0000/external-level-up-your-coding-skills-and-quickly-land-a-job-logo-bold-tal-revivo.png" width="40" height="40" />
  </a>
</p>

---

## 🚀 Languages & Tools:
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,redux,js,ts,html,css,bootstrap,tailwind,nodejs,express,mongodb,git,github,android,postman" alt="Skills" />
</p>

---

## 📊 GitHub Stats:
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bhagwan8379&show_icons=true&theme=radical" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=bhagwan8379&theme=highcontrast" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=bhagwan8379&show_icons=true&locale=en&layout=compact&theme=dracula" alt="Top Languages" />
</p>

---

## 📈 GitHub Activity Graph:
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=bhagwan8379&theme=redical" alt="GitHub Activity Graph" />
</p>

---

## 🎭 Fun Animation:
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1000&color=00E676&center=true&vCenter=true&width=600&lines=Thanks+for+visiting+my+profile!;Happy+Coding+💻" alt="Typing SVG" />
</p>













# 🚀 Bhagwan's GitHub Profile  

Welcome to my GitHub profile! Here’s a **3D animated stylish GitHub Contribution Graph** to showcase my activity.  

---

## 🔥 3D Stylish GitHub Contribution Graph  
<!-- This will display an animated snake graph of contributions -->
<p align="center">
  <img src="https://github.com/bhagwan8379/bhagwan8379/raw/output/github-snake-dark.svg" alt="VIP Styled Contribution Graph"/>
</p>

---

## 🔧 How It Works  
This **3D animated snake graph** updates automatically using **GitHub Actions**. It tracks my contributions in real-time and displays them in a **dark-themed, stylish design**.  

---

## 📜 GitHub Action Setup  
To ensure the graph updates correctly, this GitHub Action workflow is running in the background:  

```yaml
name: Generate Stylish 3D GitHub Contribution Graph

on:
  schedule:
    - cron: "0 0 * * *"  # Runs every day at midnight UTC
  workflow_dispatch:  # Allows manual trigger

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Generate the Contribution Snake Graph
        uses: Platane/snk@v3
        with:
          github_user_name: "bhagwan8379"
          outputs: |
            dist/github-snake-dark.svg
          color_scheme: "dark"  # Options: light, dark, neon, custom

      - name: Push the Graph to GitHub Pages
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

