<h1 align="center">Hi 👋, I'm Aditya Kumar Gautam</h1> <h3 align="center"> 🚀 Full Stack Developer | Android Developer | Problem Solver </h3> <p align="center"> <img src="https://readme-typing-svg.demolab.com/?lines=Full+Stack+Developer;Android+Developer;Open+Source+Enthusiast;DSA+Problem+Solver;Tech+Explorer&center=true&width=500&height=50"> </p> --- <img align="right" alt="coding" width="350" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif"> # 💫 About Me - 🔭 Currently working on **Full Stack & Android Projects** - 🌱 Learning **Advanced MERN Stack & AI Integration** - 💻 Passionate about **Web Development & Mobile Apps** - ⚡ Love solving **DSA & Logic Problems** - 🎯 Goal: Become a **Top Software Engineer** - 🏆 Solved **250+ Coding Problems** - 🎨 Interested in **Creative UI/UX Design** --- # 🌐 Connect With Me <p align="left"> <a href="https://linkedin.com/in/adityakumargautam/" target="blank"> <img align="center" src="https://skillicons.dev/icons?i=linkedin" height="50" /> </a> <a href="mailto:adityakumar02042000@gmail.com"> <img align="center" src="https://skillicons.dev/icons?i=gmail" height="50" /> </a> <a href="https://github.com/Aditya02042000"> <img align="center" src="https://skillicons.dev/icons?i=github" height="50" /> </a> <a href="https://leetcode.com/u/AdityaKumarGautam/"> <img align="center" src="https://cdn.simpleicons.org/leetcode" height="50" /> </a> <a href="https://codolio.com/profile/oiryBwNG"> <img align="center" src="https://cdn.simpleicons.org/googlechrome" height="50" /> </a> </p> --- # 🚀 Tech Stack ## 👨‍💻 Languages <p> <img src="https://skillicons.dev/icons?i=java,js,python,c,cpp,kotlin,html,css,sql" /> </p> --- ## ⚛️ Frameworks & Technologies <p> <img src="https://skillicons.dev/icons?i=react,nodejs,express,mongodb,firebase" /> </p> --- ## 🛠️ Tools & Platforms <p> <img src="https://skillicons.dev/icons?i=git,github,vscode,androidstudio,aws,vercel" /> </p> --- # 📌 Featured Projects ## 💼 JobNest - Job Search Platform 🚀 Full-stack job portal built using MERN Stack. ### ✨ Features - User Authentication - Job Search & Filters - Apply for Jobs - Application Tracking - Responsive UI ### 🛠️ Tech Used React.js Node.js Express.js MongoDB --- ## 🌐 Portfolio Website ✨ Personal portfolio website showcasing projects, skills & achievements. ### 🔥 Features - Fully Responsive - Modern UI - Smooth Navigation - Interactive Design ### 🛠️ Tech Used HTML CSS React.js --- # 🧠 LeetCode Stats <p align="center"> <a href="https://leetcode.com/u/AdityaKumarGautam/"> <img src="https://leetcard.jacoblin.cool/AdityaKumarGautam?theme=dark&font=Karma&ext=contest" /> </a> </p> --- # 📊 GitHub Stats <p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=Aditya02042000&show_icons=true&theme=tokyonight" height="180em"/> <img src="https://github-readme-streak-stats.herokuapp.com/?user=Aditya02042000&theme=tokyonight" height="180em"/> </p> --- # 📈 Contribution Graph <p align="center"> <img src="https://github-readme-activity-graph.vercel.app/graph?username=Aditya02042000&theme=tokyo-night"/> </p> --- # 🏆 GitHub Trophies <p align="center"> <img src="https://github-profile-trophy.vercel.app/?username=Aditya02042000&theme=algolia&row=1&column=7"/> </p> --- # 🌐 Coding Profiles <p align="center"> <a href="https://leetcode.com/u/AdityaKumarGautam/"> <img src="https://img.shields.io/badge/LeetCode-Profile-orange?style=for-the-badge&logo=leetcode"/> </a> <a href="https://github.com/Aditya02042000"> <img src="https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github"/> </a> <a href="https://linkedin.com/in/adityakumargautam/"> <img src="https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin"/> </a> <a href="https://codolio.com/profile/oiryBwNG"> <img src="https://img.shields.io/badge/Codolio-Portfolio-purple?style=for-the-badge&logo=googlechrome"/> </a> </p> --- # 🏅 Competitive Programming & Portfolio <p align="center"> <a href="https://codolio.com/profile/oiryBwNG"> <img src="https://img.shields.io/badge/View%20My-Codolio%20Profile-8A2BE2?style=for-the-badge&logo=firefoxbrowser"/> </a> </p> <p align="center"> <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Aditya02042000&theme=tokyonight" /> </p> --- # 📈 GitHub Contribution Snake <p align="center"> <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" /> </p> --- # 💻 Developer Quote <p align="center"> <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight"/> </p> --- # 👀 Profile Views <p align="center"> <img src="https://komarev.com/ghpvc/?username=Aditya02042000&label=PROFILE+VIEWS&color=blueviolet&style=for-the-badge"/> </p> --- # ⚡ Fun Fact
javascript
const aditya = {
    code: ["Java", "JavaScript", "Python", "Kotlin"],
    askMeAbout: ["Web Dev", "Android Dev", "DSA"],
    technologies: {
        frontend: ["React"],
        backend: ["Node.js", "Express"],
        database: ["MongoDB", "Firebase", "MySQL"],
    },
    currentFocus: "Building scalable apps & improving problem solving",
    funFact: "I turn coffee ☕ into code 💻"
};
--- # 🐍 Contribution Snake Animation
yml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"

  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v3

      - uses: Platane/snk@v3
        with:
          github_user_name: Aditya02042000
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
--- <h3 align="center"> ✨ "Code • Create • Innovate" ✨ </h3>
