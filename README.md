#!/usr/bin/env bash
# ============================================================
#  Sanjay A — GitHub Profile Setup (all-in-one)
# ------------------------------------------------------------
#  1. Edit GITHUB_USERNAME below (one line).
#  2. Run:  bash setup_profile.sh
#  3. It creates a ready-to-push folder called profile-repo/
#     containing README.md + both GitHub Actions workflows,
#     with your username already filled in everywhere.
#  4. cd profile-repo, git init, and push to a repo named
#     exactly your username (e.g. sanjay-a/sanjay-a).
# ============================================================

set -e

GITHUB_USERNAME="YOUR_GITHUB_USERNAME"   # <-- change this one line

OUT="profile-repo"
rm -rf "$OUT"
mkdir -p "$OUT/.github/workflows"

# ---------------------------------------------------------
# README.md
# ---------------------------------------------------------
cat > "$OUT/README.md" << 'EOF'
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=250&section=header&text=SANJAY%20A&fontSize=70&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Computer%20Science%20Engineering%20%26%20Cyber%20Security&descAlignY=55&descSize=22&descAlign=50" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&duration=2800&pause=900&color=8A2BE2&center=true&vCenter=true&multiline=true&width=760&height=100&lines=%3E+whoami+%3D%3D+Software+%26+Cybersecurity+Enthusiast;%3E+stack+%3D%3D+Android+%7C+Web+%7C+Linux+%7C+AI-Driven+Systems;%3E+status+%3D%3D+Building+%2B+Breaking+%2B+Securing" alt="Typing SVG" />

<br/>

<img src="https://komarev.com/ghpvc/?username=__USERNAME__&label=PROFILE+VIEWS&color=8a2be2&style=for-the-badge"/>
<img src="https://img.shields.io/github/followers/__USERNAME__?label=FOLLOWERS&style=for-the-badge&color=8a2be2"/>
<img src="https://img.shields.io/badge/OPEN%20TO-Software%20%7C%20Cybersecurity%20%7C%20IT-1a1a2e?style=for-the-badge&color=302b63"/>

<br/><br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-8A2BE2?style=for-the-badge&logo=firefox&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](#)
[![Tamil Nadu](https://img.shields.io/badge/📍_Tamil%20Nadu-India-1a1a2e?style=for-the-badge)](#)

</div>

<br/>

<div align="center">
<img src="https://raw.githubusercontent.com/__USERNAME__/__USERNAME__/output/github-contribution-grid-snake-dark.svg" width="100%"/>
<sub>⚙️ Auto-generated nightly by the included GitHub Actions workflow.</sub>
</div>

<br/>

## 🧬 About Me

<table>
<tr>
<td width="60%" valign="top">

```python
class Sanjay:
    def __init__(self):
        self.role         = "CSE & Cyber Security Student"
        self.institution  = "BIHER, Tamil Nadu, India"
        self.languages    = ["Python", "C", "JavaScript", "Kotlin"]
        self.focus_areas  = [
            "Software Development", "Cybersecurity",
            "Android Development", "AI / ML"
        ]
        self.currently    = "Practicing Kali Linux & ethical hacking"
        self.mission      = (
            "Turning real-world problems into secure, "
            "intelligent, production-ready software."
        )

    def debug(self):
        while bug_exists:
            terminal.open()
            coffee.drink()
            bug_exists = not fixed()
```

</td>
<td width="40%" valign="top">

**⚡ Quick Facts**

🎓 B.Tech CSE & Cyber Security
🔐 Kali Linux & network security
📱 Android · Kotlin · Jetpack Compose
🌐 Full-stack web (Flask, Node, MySQL, Firebase)
🤖 Exploring AI-assisted app features
🏆 Hackathon & academic project builder
🎯 Targeting: Software Dev / Cybersecurity / IT roles

</td>
</tr>
</table>

<br/>

## 🧠 Skill Matrix

<div align="center">
<img src="https://skillicons.dev/icons?i=python,c,js,kotlin,html,css,flask,nodejs,mysql,firebase,androidstudio,linux,kali,git,github,vscode&theme=dark&perline=8"/>
</div>

<br/>

<details open>
<summary><b>📊 Proficiency Breakdown</b></summary>
<br/>

| Domain | Stack | Level |
|---|---|---|
| **Programming** | Python · C · JavaScript · Kotlin | ████████░░ 80% |
| **Web Development** | HTML5 · CSS3 · JS · Chart.js | ████████░░ 80% |
| **Backend & DB** | Flask · Node.js · MySQL · Firebase | ███████░░░ 70% |
| **Mobile (Android)** | Kotlin · Jetpack Compose | ███████░░░ 70% |
| **Cybersecurity & Linux** | Kali Linux · CLI · Networking · VPN/DNS | ██████░░░░ 60% |
| **Tools & Workflow** | Git · GitHub · VS Code · Android Studio | ████████░░ 80% |

</details>

<br/>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">
<h3>🛡️ SafeHer</h3>
<i>Women Safety Application</i>
<br/><br/>
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white"/> <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white"/>
<br/><br/>
Mobile app concept for women's safety & emergency assistance — login/registration flows, communication, and intelligent support features.
</td>
<td width="50%" valign="top">
<h3>🏥 Rural Healthcare Platform</h3>
<i>AI/ML-assisted healthcare access</i>
<br/><br/>
<img src="https://img.shields.io/badge/AI%2FML-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/Multilingual-4CAF50?style=flat-square"/>
<br/><br/>
Offline/online hybrid concept for underserved communities — multilingual, voice-based, AI-assisted communication & emergency support.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>💰 Money Control & Expense Manager</h3>
<i>Personal finance dashboard</i>
<br/><br/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chart.js&logoColor=white"/> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
<br/><br/>
Income/expense tracking with monthly analytics, visual charts, Excel/PDF export, Firebase-ready auth & storage.
</td>
<td width="50%" valign="top">
<h3>🔒 Cybersecurity Portfolio</h3>
<i>Dark-themed professional showcase</i>
<br/><br/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
<br/><br/>
Professional site presenting cybersecurity skills, projects, and learning areas in a dark, security-focused UI.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>✂️ Tailoring Business Websites</h3>
<i>Responsive business sites</i>
<br/><br/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<br/><br/>
Service showcases, customer contact flows, mobile-first responsive layouts.
</td>
<td width="50%" valign="top">
<h3>🌐 Business & Service Web Projects</h3>
<i>Cafes · travel · small business systems</i>
<br/><br/>
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<br/><br/>
Auth, databases, payment integration concepts, admin dashboards, and APIs.
</td>
</tr>
</table>

<br/>

## 🖥️ Cybersecurity & Linux Lab

<div align="center">

```bash
┌──(sanjay㉿kali)-[~/security-lab]
└─$ cat skills.txt
  ✔ Linux CLI fundamentals: pwd ls cd mkdir touch cp mv rm cat less head tail man --help
  ✔ Kali Linux fundamentals
  ✔ Networking: DNS · VPN · Wi-Fi security · privacy fundamentals
  ➜ Currently exploring: ethical hacking & network security

└─$ echo "Building secure systems, one command at a time."
```

</div>

<br/>

## 📊 GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=__USERNAME__&show_icons=true&theme=radical&hide_border=true&count_private=true&include_all_commits=true"/>
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=__USERNAME__&layout=compact&theme=radical&hide_border=true"/>

<img width="100%" src="https://github-readme-streak-stats.herokuapp.com/?user=__USERNAME__&theme=radical&hide_border=true"/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=__USERNAME__&theme=redical&hide_border=true"/>

</div>

<details>
<summary align="center"><b>🧊 3D Isometric Contribution Metrics</b></summary>
<br/>
<div align="center">
<img src="https://raw.githubusercontent.com/__USERNAME__/__USERNAME__/main/github-metrics.svg" width="100%"/>
</div>
Rendered by the included <code>metrics.yml</code> Action (lowlighter/metrics).
</details>

<br/>

## 🏆 Trophy Case

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=__USERNAME__&theme=radical&no-frame=true&no-bg=false&row=1&column=7"/>
</div>

<br/>

## 🎯 Focus Areas

<div align="center">

![Cybersecurity](https://img.shields.io/badge/-Cybersecurity%20%26%20Ethical%20Hacking-1a1a2e?style=for-the-badge)
![Linux](https://img.shields.io/badge/-Linux%20%26%20Network%20Security-1a1a2e?style=for-the-badge)
![Software](https://img.shields.io/badge/-Software%20Development-302b63?style=for-the-badge)
![Android](https://img.shields.io/badge/-Android%20Development-302b63?style=for-the-badge)
![Web](https://img.shields.io/badge/-Web%20Development-8a2be2?style=for-the-badge)
![AI](https://img.shields.io/badge/-AI%20%2F%20ML-8a2be2?style=for-the-badge)
![Health](https://img.shields.io/badge/-Healthcare%20Tech-24243e?style=for-the-badge)
![Safety](https://img.shields.io/badge/-Women%20Safety%20Tech-24243e?style=for-the-badge)
![FinTech](https://img.shields.io/badge/-FinTech-0f0c29?style=for-the-badge)
![Automation](https://img.shields.io/badge/-Automation-0f0c29?style=for-the-badge)

</div>

<br/>

## 💡 Strengths

<div align="center">

| 🧩 Problem-Solving | ⚡ Fast Learner | 🐛 Debugging | 🎨 Creative Design | 🤝 Team & Hackathons |
|:---:|:---:|:---:|:---:|:---:|

</div>

<br/>

## 📈 Career Objective

> Beginning a professional career in **Software Development, Cybersecurity, or IT** — applying programming and technical knowledge to real-world problems while continuously developing expertise in cybersecurity, Linux, application development, and emerging technologies.

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=150&section=footer"/>

**"Turning code into real-world impact — one project at a time."**
</div>
EOF

# fill in the username placeholder
sed -i "s/__USERNAME__/${GITHUB_USERNAME}/g" "$OUT/README.md"

# ---------------------------------------------------------
# .github/workflows/snake.yml
# ---------------------------------------------------------
cat > "$OUT/.github/workflows/snake.yml" << 'EOF'
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 2 * * *"
  workflow_dispatch: {}
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - name: Generate contribution snake
        uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push snake output to "output" branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
EOF

# ---------------------------------------------------------
# .github/workflows/metrics.yml
# ---------------------------------------------------------
cat > "$OUT/.github/workflows/metrics.yml" << 'EOF'
name: Generate Isometric Metrics

on:
  schedule:
    - cron: "0 3 * * *"
  workflow_dispatch: {}

jobs:
  metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          filename: github-metrics.svg
          token: ${{ secrets.METRICS_TOKEN }}
          base: ""
          plugin_isocalendar: yes
          plugin_isocalendar_duration: full-year
          config_timezone: Asia/Kolkata
EOF

echo "✅ Done. Created ./${OUT}/ with:"
echo "   README.md"
echo "   .github/workflows/snake.yml"
echo "   .github/workflows/metrics.yml"
echo ""
echo "Next steps:"
echo "  cd ${OUT}"
echo "  git init && git add . && git commit -m 'Init profile'"
echo "  git branch -M main"
echo "  git remote add origin https://github.com/${GITHUB_USERNAME}/${GITHUB_USERNAME}.git"
echo "  git push -u origin main"
echo ""
echo "  Then add a repo secret METRICS_TOKEN (a PAT with repo + read:user scopes)"
echo "  for the isometric-metrics workflow to work."
