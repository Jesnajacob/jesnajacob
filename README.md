![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=F7A41D&center=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B%2C+I'm+Jesna+Jacob;MSc+Computer+Science+Student;Data+Analytics+Enthusiast;Turning+data+into+insights)

![Jesna's GitHub stats](https://github-readme-stats.vercel.app/api?username=Jesnajacob&show_icons=true&theme=radical)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Jesnajacob&layout=compact&theme=radical)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Jesnajacob&theme=radical)
# .github/workflows/snake.yml
name: Generate Snake
on:
  schedule:
    - cron: "0 */6 * * *"
  push:
    branches: [main]
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
![Snake animation](https://raw.githubusercontent.com/Jesnajacob/Jesnajacob/output/github-contribution-grid-snake.svg)
[![My Skills](https://skillicons.dev/icons?i=python,java,mysql,tensorflow,git,vscode)](https://skillicons.dev)
![Visitor Count](https://komarev.com/ghpvc/?username=Jesnajacob&color=blueviolet&style=flat)
<img src="https://raw.githubusercontent.com/AnandVerma11/Github-Profile/main/wave.gif" width="30">


🎓 MSc Computer Science Student | 📊 Data Analytics Enthusiast  
💡 Interested in Data Analytics, Artificial Intelligence, and Machine Learning  
🐍 Working with Python, SQL,Java and Data Analysis tools  
📈 Passionate about turning data into meaningful insights  

---

## 🛠️ Skills
- Python
- Data Analytics
- Machine Learning
- SQL
- Data Visualization
- Java (Basics)

---

## 📚 Currently Learning
- Data Analytics
- JAVA
- Artificial Intelligence
- Agile development Methodologies
- Machine Learning Models
- Data Visualization Techniques  

---

## 📊 Tools & Technologies
Python | Pandas | NumPy | Matplotlib | Scikit-learn | SQL | Jupyter Notebook | Netbeans |

---

## 📫 Connect With Me
- GitHub: https://github.com/jesnajacob

---

⭐ *Exploring data, building models, and learning something new every day.*
