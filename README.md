<div align="center">


[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=A855F7&center=true&vCenter=true&width=620&lines=Software+Developer+%40+S%C3%BBret%C3%A9+du+Qu%C3%A9bec;CS+%26+Software+Engineering+Student+%40+UQAM;Full-Stack+%7C+Data+Engineering+%7C+ML;Turning+messy+data+into+working+systems)](https://github.com/Matteodt974)

![UQAM](https://img.shields.io/badge/UQAM-B.S.%20Computer%20Science-8957E5?style=for-the-badge&logo=googlescholar&logoColor=white)
![Location](https://img.shields.io/badge/Montr%C3%A9al,%20QC-Canada-6366F1?style=for-the-badge&logo=googlemaps&logoColor=white)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/matteo-destriez-terrighi)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Matteodt974)
[![Email](https://img.shields.io/badge/Email-8957E5?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matteodestriez2@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=Matteodt974&label=Profile%20Views&color=8957E5&style=for-the-badge)
![Followers](https://img.shields.io/github/followers/Matteodt974?label=Followers&style=for-the-badge&color=8957E5&logo=github&logoColor=white)

</div>

---

## 👤 About

Computer Science & Software Engineering student at **UQAM** (Montréal), currently building production tooling as a **Software Developer at the Sûreté du Québec**. I work across the stack — Python services and ELT pipelines on the backend, Power BI / DAX analytics for end users, and full-stack apps for side projects. I care about systems that actually ship and data that's actually trustworthy.

Lately I've been going deeper on **data engineering** (Snowflake + dbt + Airflow) and **applied ML / RAG** — the gap between a demo and something reliable is where the interesting work is.

**🟢 Open to:** SWE / ML internships · New-grad roles (2027) · Research collaborations

---

## 🛠️ Tech Stack

**Languages**

![Languages](https://skillicons.dev/icons?i=py,java,cpp,js,html,css&theme=dark)

**Frontend**

![Frontend](https://skillicons.dev/icons?i=tailwind,flutter&theme=dark)

**Backend & Databases**

![Backend](https://skillicons.dev/icons?i=spring,flask,fastapi,mysql&theme=dark)
&nbsp;
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
**Data & ML**

![DataML](https://skillicons.dev/icons?i=pytorch,sklearn&theme=dark)
&nbsp;
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Cloud, DevOps & Tooling**

![DevOps](https://skillicons.dev/icons?i=docker,git,github,vscode,maven&theme=dark)
&nbsp;
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 🤖 AI / ML & Data

| Domain | Focus | Details |
|---|---|---|
| **Machine Learning** | Coursework + projects | Stanford Online *Supervised ML* (Andrew Ng) · scikit-learn · PyTorch |
| **Reinforcement Learning** | Personal project | AlphaZero-style MCTS + self-play for the board game **Hex** (4×4, 8×8) |
| **Data Engineering & Analytics** | Personnal projects | Python ELT pipelines · Snowflake + dbt · Power BI / DAX models |

---

## 🚀 Featured Projects

<details open>
<summary><b>Modern ELT Data Pipeline</b> — dbt · Snowflake · Airflow · Python · SQL · Docker</summary>

<br>

End-to-end ELT pipeline that ingests data from a public REST API, lands raw records in a Snowflake warehouse, then transforms them into analytics-ready models with dbt and automated data-quality tests.

| Aspect | Detail |
|---|---|
| **Stack** | dbt · Snowflake · Apache Airflow · Python · SQL · Docker |
| **Architecture** | Staging → Fact → Mart layering with warehouse governance |
| **Orchestration** | Incremental scheduled runs via Airflow DAGs |
| **Data Quality** | Automated dbt tests to enforce integrity |
| **Repository** | [`→ still in process`](https://github.com/Matteodt974) |

</details>

<details>
<summary><b>MyAm — Allergen-Aware Food Scanner</b> — Flutter · FastAPI · OCR · Computer Vision</summary>

<br>

Mobile app that reads packaged-food ingredient labels with OCR and cross-references them against a user's saved allergen profile to flag risks. A computer-vision model extends checks to dishes without labels by recognizing foods from photos.

| Aspect | Detail |
|---|---|
| **Stack** | Flutter · Python / FastAPI · OCR · Computer Vision |
| **Core** | OCR label parsing → allergen cross-reference against user profile |
| **ML** | Food recognition from meal photos (best-effort, label-free aid) |
| **Repository** | [`→ still in progress`](https://github.com/Matteodt974) |

</details>

<details>
<summary><b>Non-Profit Donation Platform — Shield of Athena</b> — Spring Boot · Angular · MySQL · n8n</summary>

<br>

Full-stack donation and engagement platform built for **Shield of Athena**, a non-profit supporting women and children. **Finalist at the Morgan Stanley Code to Give Hackathon.**

| Aspect | Detail |
|---|---|
| **Stack** | Spring Boot · Angular · TailwindCSS · MySQL · Docker · n8n |
| **Recognition** | 🏆 Morgan Stanley Code to Give — Finalist |
| **Automation** | Event-driven n8n pipeline: new-event triggers → content generation → publishing |
| **Impact** | Gamified outreach + recurring-donation flows, eliminating manual posting |
| **Repository** | [`→ repo link`]([https://github.com/Matteodt974](https://github.com/Matteodt974/CodeToGiveTeam3Montreal)) |

</details>

---

## 💼 Experience

**Software Developer** · *Sûreté du Québec* — Montréal, QC
`Aug 2024 – Present`

Building internal data tooling and workforce-management applications used across recruitment, finance, and team-performance domains.

- Cut data-processing time **~70%** by replacing manual workflows with Python ELT pipelines (Pandas, NumPy) that ingest, clean, and transform data from multiple internal sources.
- Improved reporting reliability for **150+ users** with real-time workforce-management web apps in Python/Flask, backed by JSON/REST API integration and a relational SQL database.
- Enabled executive self-serve analytics by designing Power BI data models with DAX measures, replacing the majority of manual Excel reporting.

`Python` `Flask` `Pandas` `NumPy` `SQL` `Power BI` `DAX` `REST`

---

## 🏆 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🏆 **Morgan Stanley Code to Give — Finalist** | Full-stack donation platform for Shield of Athena (non-profit for women & children) |

</div>

---

## 📜 Certifications

**Stanford Online · DeepLearning.AI**

[![Supervised ML](https://img.shields.io/badge/Coursera-Supervised%20Machine%20Learning-8957E5?style=for-the-badge&logo=coursera&logoColor=white)](https://www.coursera.org/learn/machine-learning)

*Supervised Machine Learning: Regression and Classification — Andrew Ng (Oct 2025)*

---

## 📊 GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Matteodt974&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&title_color=A855F7&icon_color=8B5CF6&text_color=C9D1D9&bg_color=0D1117" />
<img height="165" src="https://streak-stats.demolab.com?user=Matteodt974&hide_border=true&background=0D1117&stroke=8957E5&ring=A855F7&fire=8B5CF6&currStreakLabel=A855F7&sideLabels=C9D1D9&currStreakNum=C9D1D9&dates=8B949E&sideNums=C9D1D9" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Matteodt974&layout=compact&langs_count=8&hide_border=true&title_color=A855F7&text_color=C9D1D9&bg_color=0D1117" />

</div>

---

## 📈 Contribution Activity

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Matteodt974&bg_color=0D1117&color=A855F7&line=8B5CF6&point=C9D1D9&area=true&hide_border=true)

</div>


---

## 🎯 Current Focus

```yaml
focus:
  learning:   [" RAG pipelines", "LLM application patterns"]
  building:   ["End-to-end ELT systems", "MyAm - FullStack project"]
  exploring:  ["Graduate AI programs ", "MLOps"]
  open_to:    ["SWE / ML internships", "New-grad roles (2027)", "Research collaborations"]
```

---

## 🤝 Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-8957E5?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matteodestriez2@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/matteo-destriez-terrighi)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Matteodt974)

</div>

---

<div align="center">



</div>
