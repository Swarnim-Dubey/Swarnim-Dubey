# Hi there 👋, I'm Swarnim

### 🌟 About Me
I'm a passionate programmer and aspiring Data Scientist with hands-on experience in **Python, C, C++, SQL**, and working knowledge of **PostgreSQL, Docker, Ubuntu, and Kali Linux**.  
Currently, I am learning **Data Structures & Algorithms** and **Data Science** to deepen my skills and build impactful projects.  

I enjoy solving real-world problems and have actively participated in **Smart India Hackathon (SIH)** and other hackathons.  

---

### 💻 Skills & Tech Stack

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Data Science](https://img.shields.io/badge/Data%20Science-FF6F61?style=for-the-badge)
![Algorithms](https://img.shields.io/badge/Algorithms-4B0082?style=for-the-badge)
![Hackathon](https://img.shields.io/badge/Hackathon-008080?style=for-the-badge)
![SIH](https://img.shields.io/badge/Smart%20India%20Hackathon-FF5733?style=for-the-badge)

---

### 📫 Connect with Me

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Swarnim-Dubey)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/swarnim-dubey-594921328/)

---

### 🚀 Projects
- **Hackathon & SIH Projects:** Developed software tools and innovative solutions for real-world problems.  
- **Data Science Projects:** Data analysis, visualization, and predictive modeling using Python, Pandas & NumPy.  
- **Database Projects:** CRUD operations, advanced SQL queries, and PostgreSQL database management.  


---

### 🏆 Achievements
- Participated in **Smart India Hackathon (SIH)**  
- Active participant in multiple hackathons  
- Building strong problem-solving skills through **DSA practice**  

---

### ⚡ Fun Fact
I love exploring **Linux environments**, building software projects, and experimenting with **data-driven solutions**.  

---

![Swarnim's GitHub stats](https://github-readme-stats.vercel.app/api?username=Swarnim-Dubey&show_icons=true&theme=tokyonight&count_private=true)

---

## 🧠 LeetCode Progress Tracker

Track my problem-solving journey on [LeetCode](https://leetcode.com/)!

### 📊 Progress Overview

| Difficulty | Solved | Total | Progress |
|-------------|---------|--------|-----------|
| Easy        | 45      | 682    | ![Progress](https://progress-bar.dev/7/?title=easy) |
| Medium      | 30      | 1475   | ![Progress](https://progress-bar.dev/2/?title=medium) |
| Hard        | 8       | 608    | ![Progress](https://progress-bar.dev/1/?title=hard) |
| **Total**   | **83**  | **2765** | ![Progress](https://progress-bar.dev/3/?title=total) |

> 🧩 *Updated manually or via automation — see below.*

---

### 📅 Recent Submissions

| Date | Problem | Language | Status |
|------|----------|-----------|--------|
| 2025-11-07 | [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/) | Python | ✅ |
| 2025-11-06 | [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | C++ | ✅ |
| 2025-11-05 | [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) | Java | ✅ |

---

### ⚙️ Automate Updates (Optional)

If you’d like to auto-refresh your stats daily, use a GitHub Action with [LeetCode API](https://leetcode.com/graphql) or [leetcode-cli](https://github.com/skygragon/leetcode-cli).

Example workflow file:  
`.github/workflows/update-leetcode.yml`

```yaml
name: Update LeetCode Progress
on:
  schedule:
    - cron: "0 12 * * *" # every day at 12:00 UTC
  workflow_dispatch:
jobs:
  update:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Update Progress
        run: python scripts/update_progress.py
      - name: Commit Changes
        run: |
          git config --global user.name "github-actions"
          git config --global user.email "actions@github.com"
          git add README.md progress.json
          git commit -m "Auto update LeetCode progress"
          git push

