<!-- CYBERPUNK HEADER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:7B2FBE,100:00FFFF&height=160&section=header&text=DEBASHRESTHA%20NANDI&fontSize=42&fontColor=00FFFF&fontAlignY=45&desc=SWE%20Intern%20%40%20Mutual%20of%20Omaha%20%7C%20Builder%20%7C%20Breaker&descAlignY=68&descSize=16&descFontColor=ffffff&animation=twinkling" />

<!-- ANIMATED TYPING SVG -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=22&duration=2800&pause=1200&color=00FFFF&center=true&vCenter=true&width=720&lines=building+Aura+%E2%86%92+AI+that+actually+preps+you+for+interviews;SWE+Intern+%40+Mutual+of+Omaha+(Fortune+300);prev+%40+Blackstone;97.4%25+ROC-AUC+on+284K+transactions;%2447K+revenue+with+a+95%25+student+pass+rate;i+push+everything+%E2%9C%8C%EF%B8%8F)](https://github.com/undisputed-deb)

</div>

---

<!-- CONNECT BADGES -->
<div align="center">

[![Portfolio](https://img.shields.io/badge/%E2%97%88_PORTFOLIO-00FFFF?style=for-the-badge&logoColor=black)](https://debshrestho-portfolio.vercel.app)&nbsp;
[![LinkedIn](https://img.shields.io/badge/%E2%97%88_LINKEDIN-7B2FBE?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/debshrestho/)&nbsp;
[![Email](https://img.shields.io/badge/%E2%97%88_HIT_ME_UP-FF2D78?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deb86011@gmail.com)&nbsp;
[![DS Tutoring](https://img.shields.io/badge/%E2%97%88_MY_COMPANY-0d0d0d?style=for-the-badge&logoColor=00FFFF)](https://dstutoringcenter.company/)

</div>

---

## ◈ what's good

honestly just love building things. if i think of something, i build it and push it. check the repos, lotta noob stuff early on, some actually solid ones now. SWE intern @ Mutual of Omaha right now, previously data engineering @ Blackstone. also ran a tutoring center as CTO, 120+ students, 95% pass rate, those are the numbers i care about.

**currently locked in on:** Aura (biggest project yet), ML systems, APIs that don't suck, making the web accessible for real

---

## ◈ the stack

<div align="center">

**languages**

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=java,python,typescript,javascript,cpp&theme=dark" />
</a>

**backend and infra**

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=spring,fastapi,flask,django,nodejs,docker,kubernetes,redis&theme=dark" />
</a>

**frontend**

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vue&theme=dark" />
</a>

**data and cloud**

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=postgresql,mongodb,firebase,supabase,aws,gcp,azure&theme=dark" />
</a>

**ai and ml**

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=tensorflow,pytorch&theme=dark" />
</a>&nbsp;
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white)&nbsp;
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logoColor=white)&nbsp;
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)&nbsp;
![RAG](https://img.shields.io/badge/RAG_Pipelines-00FFFF?style=flat-square&logoColor=black)

</div>

---

## ◈ stuff i've shipped

<!-- AURA -->
### ⚡ [Aura — AI Voice Mock Interview Platform](https://github.com/undisputed-deb) &nbsp;`FLAGSHIP`

> **the problem:** 80%+ of candidates choke in interviews because they never practice speaking out loud. reading tips does nothing. you need reps.

you upload your resume, pick the company you're interviewing at, and Aura runs a real voice interview with you. it listens in real-time with Groq Whisper, scores you on clarity, depth, and structure, and tells you exactly where you dropped the ball and why.

```yaml
impact:
  problem_targeted:  "80%+ interview failure from zero real practice"
  solution:          "full voice pipeline: resume parsing + live interview + AI scoring"
  coverage:          "resume grill + company-specific prep + STAR coaching + progress tracking"
  reliability:       "18+ endpoints, Redis session state, zero auth incidents"
```

**stack:**
`Next.js 15` `FastAPI` `Socket.IO` `PostgreSQL` `Supabase` `Redis (Upstash)` `Groq Whisper` `ElevenLabs` `Google Gemini 1.5` `Clerk` `Stripe` `Remotion`

---

<!-- FRAUD DETECTION -->
### 🔍 [Credit Card Fraud Detection System](https://github.com/undisputed-deb/Credit-Card-Fraud-Detection-System)

> catching bad guys at 99.7% accuracy

9 ML algorithms + ensemble voting on 284K+ transactions with a brutal 577:1 class imbalance. SMOTE + SMOTE-Tomek + stratified CV to make it work on real-world data.

```
ROC-AUC:        97.4%
Accuracy:       99.7%
Fraud Recall:   91.8% at only 2.4% false positives
Business $:     $6,570 saved per 100 fraud attempts
```

`Python` `XGBoost` `scikit-learn` `SMOTE` `pandas` `matplotlib` `seaborn`

---

<!-- ALL IN ONE -->
### 🛠 [All-in-One Document and Media Processing Service](https://github.com/undisputed-deb/all-in-one-tools)

> 18+ endpoints, one unified service, zero excuses

full-stack platform consolidating PDF tools, image processing, and video ops into one Spring Boot 3.x + React/TypeScript app. JWT auth, bcrypt, CORS, rate limiting, FFmpeg and ImageMagick underneath.

```
Concurrent ops:   50+ file operations handled simultaneously
Auth incidents:   0
Workflows merged: 3 separate services into 1
```

`Java` `Spring Boot 3.x` `React` `TypeScript` `Tailwind CSS` `FFmpeg` `ImageMagick`

---

<!-- PROMPTPOWER -->
### ⚙ [PromptPower](https://github.com/undisputed-deb/PromptPower)

> production-grade prompt optimizer with actual security built in

transforms vague AI prompts into something that gets results. IP-based rate limiting, XSS protection, persistent storage, all the boring security stuff nobody wants to build but everyone needs.

`Next.js 15` `React 19` `Gemini API` `TypeScript`

---

<!-- FOOD WASTE -->
### 🌱 [Food Waste Management System](https://github.com/undisputed-deb/Food-Waste-Management)

full-stack platform tracking food waste from generation to composting. RBAC, real-time analytics, containerized. trying to build something that actually matters.

`Spring Boot` `Vue.js` `PostgreSQL` `Docker` `JWT`

---

<!-- AI MEETING -->
### 📋 [AI Meeting Notes Automation](https://github.com/undisputed-deb/ai-meeting-notes)

automated transcription + AI summaries, 40% productivity boost. one-click PDF export, sentiment analysis, MongoDB. your meetings just got useful.

`Python` `React` `Google Gemini` `MongoDB` `TypeScript`

---

<!-- RESUME ANALYZER -->
### 📄 [AI Resume Analyzer](https://github.com/undisputed-deb/AI-Resume-Analyzer)

NLP-powered resume analyzer with instant ATS scoring. 95% accuracy, 60% faster recruiter screening, 35% better candidate matches.

`Flask` `Python` `NLP` `Google Gemini AI`

---

## ◈ the receipts

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=undisputed-deb&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&title_color=00FFFF&icon_color=7B2FBE&text_color=ffffff&bg_color=0d0d0d&ring_color=FF2D78&hide=issues" />
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=undisputed-deb&layout=compact&hide_border=true&langs_count=8&title_color=00FFFF&text_color=ffffff&bg_color=0d0d0d&hide=html,css,jupyter%20notebook" />

<img width="55%" src="https://streak-stats.demolab.com/?user=undisputed-deb&hide_border=true&ring=00FFFF&fire=FF2D78&currStreakLabel=00FFFF&background=0d0d0d&stroke=7B2FBE&dates=ffffff&sideLabels=ffffff&sideNums=00FFFF&currStreakNum=FF2D78" />

<img width="80%" src="https://github-profile-trophy.vercel.app/?username=undisputed-deb&theme=radical&no-frame=true&no-bg=true&margin-w=8&column=7" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=undisputed-deb&bg_color=0d0d0d&color=00FFFF&line=7B2FBE&point=FF2D78&area=true&hide_border=true" />

</div>

---

## ◈ experience

**Software Engineer Intern** @ **Mutual of Omaha** *(Fortune 300)*
`Jan 2026 - Present` Omaha, Nebraska
Spring Boot + Groovy microservices, mainframe-to-microservice migration serving 3M+ policyholders, IIB to GitHub modernization, Spock testing, Kubernetes/Docker deployments

**Data Engineering Intern** @ **Blackstone**
`Jun 2025 - Aug 2025` Manhattan, NY
ETL pipelines at 10K+ listings/day, Algolia at 50K+ queries/day, PowerBI dashboards saving 16 hrs/week, Databricks + PySpark 2.3x query improvement

**Software Engineering Intern** @ **Baxter St. Camera Club**
`Sept 2025 - Dec 2025` Manhattan, NY
WCAG 2.1 AA on 500+ assets, Firestore/Cloud Functions APIs, Azure DevOps CI/CD

**Chief Technical Officer** @ **D.S Tutoring Center**
`Mar 2024 - Present` Bronx, NY
$47K+ revenue last year, 120+ students, 95% pass rate, full-stack exam portal

---

## ◈ numbers that hit

<div align="center">

| metric | number |
|---|---|
| ML fraud detection accuracy | **99.7%** |
| revenue generated | **$47K+** |
| policyholders served via microservices | **3M+** |
| daily ETL throughput | **10K+ listings** |
| WCAG accessibility coverage | **85%** |
| student pass rate | **95%** |
| weekly hours saved with dashboards | **16 hrs** |
| false positive rate (fraud model) | **2.4%** |

</div>

---

## ◈ currently locked in on

- Aura, making it the go-to interview prep tool
- advanced ML + deep learning (the actually fun stuff)
- cloud architecture across AWS/GCP/Azure
- data engineering with Apache Spark

---

<div align="center">

## ◈ let's build something

open for: **internships** **collabs** **open source** **cool projects in general**

[![Portfolio](https://img.shields.io/badge/%E2%97%88_PORTFOLIO-00FFFF?style=for-the-badge&logoColor=black)](https://debshrestho-portfolio.vercel.app)&nbsp;
[![LinkedIn](https://img.shields.io/badge/%E2%97%88_LINKEDIN-7B2FBE?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/debshrestho/)&nbsp;
[![Email](https://img.shields.io/badge/%E2%97%88_EMAIL-FF2D78?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deb86011@gmail.com)

---

**`"i push everything, the good stuff, the bad stuff, the 3am stuff. all of it." ✌️`**

![Profile Views](https://komarev.com/ghpvc/?username=undisputed-deb&color=00FFFF&style=flat-square&label=PROFILE+VIEWS)

</div>

<!-- CYBERPUNK FOOTER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00FFFF,50:7B2FBE,100:0d0d0d&height=120&section=footer&animation=twinkling" />
