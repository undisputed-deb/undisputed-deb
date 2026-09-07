<!-- CYBERPUNK HEADER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:7B2FBE,100:00FFFF&height=160&section=header&text=DEBASHRESTHA%20NANDI&fontSize=42&fontColor=00FFFF&fontAlignY=45&desc=SWE%20Intern%20%40%20Mutual%20of%20Omaha%20%7C%20Builder%20%7C%20Breaker&descAlignY=68&descSize=16&descFontColor=ffffff&animation=twinkling" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=22&duration=2800&pause=1200&color=00FFFF&center=true&vCenter=true&width=720&lines=building+Aura+%E2%86%92+AI+that+actually+preps+you+for+interviews;SWE+Intern+%40+Mutual+of+Omaha+(Fortune+300);prev+%40+Blackstone;97.4%25+ROC-AUC+on+284K+transactions;%2447K+revenue%2C+95%25+student+pass+rate;i+push+everything+I+build)](https://github.com/undisputed-deb)

</div>

---

<div align="center">

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-00FFFF?style=for-the-badge&logoColor=black)](https://debshrestho-portfolio.vercel.app)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-7B2FBE?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/debshrestho/)&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-FF2D78?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deb86011@gmail.com)&nbsp;
[![DS Tutoring](https://img.shields.io/badge/MY_COMPANY-0d0d0d?style=for-the-badge&logoColor=00FFFF)](https://dstutoringcenter.company/)

<img src="https://komarev.com/ghpvc/?username=undisputed-deb&color=00FFFF&style=for-the-badge&label=PROFILE+VIEWS" />

</div>

---

## what's good

I build things because I want to see if I can. Some of the repos below are noob-era projects, some are the real stuff. Right now I'm a SWE intern at Mutual of Omaha, a Fortune 300 company, and before that I did data engineering at Blackstone.

I also run a tutoring center as CTO. 120+ students, 95% pass rate, $47K in revenue last year. Those numbers matter more to me than any badge on this page.

**Locked in on right now:** Aura, the biggest thing I've shipped. ML systems that hold up under real data. APIs that don't fall over. Making the web work for everyone who uses it.

---

## the stack

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
</a>

</div>

---

## stuff I've shipped

### [Aura — AI Voice Mock Interview Platform](https://github.com/undisputed-deb/AURA) `FLAGSHIP`

Most people fail interviews for one reason: they never practice talking out loud. Reading tips doesn't fix that. Reps do.

Upload your resume, name the company you're interviewing at, and Aura runs a real voice interview with you. Groq Whisper transcribes you live, Gemini scores your answers on clarity and depth, and it tells you exactly where you fell short and why.

```yaml
impact:
  problem_targeted:  "candidates fail interviews from zero real practice"
  solution:          "full voice pipeline: resume parsing, live interview, AI scoring"
  coverage:          "resume grill, company-specific prep, STAR coaching, progress tracking"
  reliability:       "18+ endpoints, Redis session state, zero auth incidents"
```

**stack:**
`Next.js 16` `FastAPI` `Socket.IO` `PostgreSQL` `Supabase` `Redis (Upstash)` `Groq Whisper` `Google Gemini 2.5 Flash` `OpenAI TTS` `Clerk` `Stripe` `Remotion`

---

### [Credit Card Fraud Detection System](https://github.com/undisputed-deb/Credit-Card-Fraud-Detection-System)

9 ML algorithms with ensemble voting, trained on 284K+ transactions with a 577:1 class imbalance. SMOTE and SMOTE-Tomek plus stratified cross-validation to make it hold up on real-world data, not just a clean benchmark.

```
ROC-AUC:        97.4%
Accuracy:       99.7%
Fraud Recall:   91.8% at a 2.4% false positive rate
Business $:     $6,570 saved per 100 fraud attempts
```

`Python` `XGBoost` `scikit-learn` `SMOTE` `pandas` `matplotlib` `seaborn`

---

### [All-in-One Document and Media Processing Service](https://github.com/undisputed-deb/all-in-one-tools)

18+ endpoints, one Spring Boot 3.x + React/TypeScript service, three separate tools I used to run apart now merged into one. PDF, image, and video operations behind JWT auth with bcrypt, CORS, and rate limiting. FFmpeg and ImageMagick do the heavy lifting underneath.

```
Concurrent ops:   50+ file operations handled simultaneously
Auth incidents:   0
Workflows merged: 3 separate services into 1
```

`Java` `Spring Boot 3.x` `React` `TypeScript` `Tailwind CSS` `FFmpeg` `ImageMagick`

---

### [PromptPower](https://github.com/undisputed-deb/PromptPower)

Turns vague AI prompts into ones that actually get results. IP-based rate limiting, XSS protection, persistent storage — the security work everyone skips until it bites them.

`Next.js 15` `React 19` `Gemini API` `TypeScript`

---

### [Food Waste Management System](https://github.com/undisputed-deb/Food-Waste-Management)

Full-stack platform tracking food waste from generation to composting. Role-based access, real-time analytics, containerized deployment.

`Spring Boot` `Vue.js` `PostgreSQL` `Docker` `JWT`

---

### [AI Meeting Notes Automation](https://github.com/undisputed-deb/ai-meeting-notes)

Automated transcription and AI summaries that cut a 40% chunk off meeting follow-up time. One-click PDF export, sentiment analysis, MongoDB behind it.

`Python` `React` `Google Gemini` `MongoDB` `TypeScript`

---

### [AI Resume Analyzer](https://github.com/undisputed-deb/AI-Resume-Analyzer)

NLP-powered resume scoring against ATS criteria. 95% accuracy, cuts recruiter screening time by 60%, improves candidate-role matching by 35%.

`Flask` `Python` `NLP` `Google Gemini AI`

---

## the receipts

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=undisputed-deb&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&title_color=00FFFF&icon_color=7B2FBE&text_color=ffffff&bg_color=0d0d0d&ring_color=FF2D78&hide=issues" />
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=undisputed-deb&layout=compact&hide_border=true&langs_count=8&title_color=00FFFF&text_color=ffffff&bg_color=0d0d0d&hide=html,css,jupyter%20notebook" />

<img width="55%" src="https://streak-stats.demolab.com/?user=undisputed-deb&hide_border=true&ring=00FFFF&fire=FF2D78&currStreakLabel=00FFFF&background=0d0d0d&stroke=7B2FBE&dates=ffffff&sideLabels=ffffff&sideNums=00FFFF&currStreakNum=FF2D78" />

<img width="80%" src="https://github-profile-trophy.vercel.app/?username=undisputed-deb&theme=radical&no-frame=true&no-bg=true&margin-w=8&column=7" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=undisputed-deb&bg_color=0d0d0d&color=00FFFF&line=7B2FBE&point=FF2D78&area=true&hide_border=true" />

</div>

---

## experience

**Software Engineer Intern** — **Mutual of Omaha** *(Fortune 300)*
`Jan 2026 – Present` · Omaha, Nebraska
Spring Boot + Groovy microservices for a mainframe-to-microservice migration serving 3M+ policyholders. Moved IIB integrations to GitHub-based workflows. Spock testing, Kubernetes and Docker deployments.

**Data Engineering Intern** — **Blackstone**
`Jun 2025 – Aug 2025` · Manhattan, NY
ETL pipelines processing 10K+ listings a day. Algolia search at 50K+ queries a day. PowerBI dashboards that saved the team 16 hours a week. Databricks and PySpark work that cut query time by 2.3x.

**Software Engineering Intern** — **Baxter St. Camera Club**
`Sept 2025 – Dec 2025` · Manhattan, NY
Brought 500+ digital assets to WCAG 2.1 AA. Built APIs on Firestore and Cloud Functions. Set up CI/CD on Azure DevOps.

**Chief Technical Officer** — **D.S. Tutoring Center**
`Mar 2024 – Present` · Bronx, NY
$47K+ revenue last year, 120+ students, 95% pass rate. Built the full-stack exam portal myself.

---

## numbers that hit

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
| false positive rate, fraud model | **2.4%** |

</div>

---

## currently locked in on

- Aura — making it the go-to interview prep tool
- advanced ML and deep learning
- cloud architecture across AWS, GCP, and Azure
- data engineering with Apache Spark

---

<div align="center">

## let's build something

Open for internships, collabs, open source, and cool projects in general.

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-00FFFF?style=for-the-badge&logoColor=black)](https://debshrestho-portfolio.vercel.app)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-7B2FBE?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/debshrestho/)&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-FF2D78?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deb86011@gmail.com)

---

**"I push everything — the good stuff, the bad stuff, the 3am stuff. All of it."**

</div>

<!-- CYBERPUNK FOOTER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00FFFF,50:7B2FBE,100:0d0d0d&height=120&section=footer&animation=twinkling" />
