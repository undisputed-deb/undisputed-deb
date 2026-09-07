<!-- CYBERPUNK HEADER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:7B2FBE,100:00FFFF&height=160&section=header&text=DEBASHRESTHA%20NANDI&fontSize=42&fontColor=00FFFF&fontAlignY=45&desc=SWE%20Intern%20%40%20Mutual%20of%20Omaha%20%7C%20Builder%20%7C%20Breaker&descAlignY=68&descSize=16&descFontColor=ffffff&animation=twinkling" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=22&duration=2800&pause=1200&color=00FFFF&center=true&vCenter=true&width=760&lines=just+shipped+FinAdvisor+%E2%86%92+portfolio+analysis+that+gives+real+verdicts;built+Aura+%E2%86%92+AI+that+runs+you+through+a+voice+interview;SWE+Intern+%40+Mutual+of+Omaha+(Fortune+300);prev+%40+Blackstone;97.4%25+ROC+AUC+on+284K+transactions;%2447K+revenue%2C+95%25+student+pass+rate;i+push+everything+I+build)](https://github.com/undisputed-deb)

</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-00FFFF?style=for-the-badge&logoColor=black)](https://deb-portfolio-2flw.vercel.app/)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-7B2FBE?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/debshrestho/)&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-FF2D78?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deb86011@gmail.com)&nbsp;
[![DS Tutoring](https://img.shields.io/badge/MY_COMPANY-0d0d0d?style=for-the-badge&logoColor=00FFFF)](https://dstutoringcenter.company/)

</div>

## what's good

I build things to find out whether I can. Some repos below are noob era experiments. Some are the real stuff. Right now I'm a SWE intern at Mutual of Omaha, a Fortune 300 company, and before that I did data engineering at Blackstone.

I also run a tutoring center as CTO. 120+ students, 95% pass rate, $47K revenue last year. Those numbers mean more to me than any badge on this page.

**Locked in right now:** FinAdvisor and Aura, the two biggest things I've shipped. ML systems that survive real data. APIs that stay up. Web that works for everyone who touches it.

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

## stuff I've shipped

### [FinAdvisor · Portfolio Analysis Dashboard](https://github.com/undisputed-deb/Stock_predictor) `NEW`

Most portfolio trackers show you a pie chart and stop there. FinAdvisor gives you a verdict on every position.

Paste your holdings or drop a broker screenshot. The tool scores your financial health, checks your emergency fund runway and cash flow, then rates each position buy, hold, trim, or sell with an entry price grade, a target, a stop loss, and a DCA size. A what if drawer recalculates weights, yield, and concentration before you place a trade. Gap analysis flags the sectors you're missing. Everything exports to a PDF report.

```yaml
what_it_does:
  health_score:     "net worth, emergency fund runway, cash flow"
  per_position:     "buy/hold/trim/sell verdict, entry grade, target, stop, DCA size"
  scenario_drawer:  "recompute weights, yield, concentration before you trade"
  gap_analysis:     "new positions to close sector gaps and cut concentration risk"
  benchmarking:     "portfolio vs S&P 500, year long rebalance simulation"
  export:           "full PDF portfolio report"
```

**stack:**
`Next.js 14` `TypeScript` `Tailwind CSS` `Recharts` `TanStack Query` `Zustand` `FastAPI` `pandas` `yfinance` `Google Gemini`

### [Aura · AI Voice Mock Interview Platform](https://github.com/undisputed-deb/AURA) `FLAGSHIP`

People lose interviews for one reason: they never practice talking out loud. Reading tips doesn't fix that. Reps do.

Upload your resume, name the company, and Aura runs a real voice interview. Groq Whisper transcribes you live, Gemini scores your answers on clarity and depth, and it tells you where you fell short and why. It grills you on your own resume, preps you company by company, coaches STAR structure, and tracks your progress across sessions.

```yaml
impact:
  problem_targeted:  "candidates fail interviews from zero real practice"
  solution:          "full voice pipeline: resume parsing, live interview, AI scoring"
  coverage:          "resume grill, company specific prep, STAR coaching, progress tracking"
  reliability:       "18+ endpoints, Redis session state, zero auth incidents"
```

**stack:**
`Next.js 16` `FastAPI` `Socket.IO` `SQLAlchemy 2.0` `PostgreSQL` `Supabase` `Redis (Upstash)` `Groq Whisper` `Google Gemini 2.5 Flash` `OpenAI TTS` `Clerk` `Stripe` `Remotion`

### [Credit Card Fraud Detection System](https://github.com/undisputed-deb/Credit-Card-Fraud-Detection-System)

9 ML algorithms with ensemble voting, trained on 284K+ transactions at a 577:1 class imbalance. SMOTE and SMOTE plus Tomek links, with stratified cross validation, so it holds up on real world data instead of a clean benchmark.

```
ROC AUC:        97.4%
Accuracy:       99.7%
Fraud Recall:   91.8% at a 2.4% false positive rate
Business $:     $6,570 saved per 100 fraud attempts
```

`Python` `XGBoost` `scikit-learn` `SMOTE` `pandas` `matplotlib` `seaborn`

### [All in One Document and Media Processing Service](https://github.com/undisputed-deb/all-in-one-tools)

18+ endpoints, one Spring Boot 3.x and React/TypeScript service, three tools I used to run apart now merged into one. PDF, image, and video operations behind JWT auth with bcrypt, CORS, and rate limiting. FFmpeg and ImageMagick do the heavy lifting.

```
Concurrent ops:   50+ file operations at once
Auth incidents:   0
Workflows merged: 3 services into 1
```

`Java` `Spring Boot 3.x` `React` `TypeScript` `Tailwind CSS` `FFmpeg` `ImageMagick`

### [PromptPower](https://github.com/undisputed-deb/PromptPower)

Turns vague AI prompts into ones that get results. IP based rate limiting, XSS protection, persistent storage. The security work most people skip until it bites them.

`Next.js 15` `React 19` `Gemini API` `TypeScript`

### [Food Waste Management System](https://github.com/undisputed-deb/Food-Waste-Management)

Full stack platform tracking food waste from generation to composting. Role based access, real time analytics, containerized deployment.

`Spring Boot` `Vue.js` `PostgreSQL` `Docker` `JWT`

### [AI Meeting Notes Automation](https://github.com/undisputed-deb/ai-meeting-notes)

Automated transcription and AI summaries that cut meeting follow up time by 40%. One click PDF export, sentiment analysis, MongoDB behind it.

`Python` `React` `Google Gemini` `MongoDB` `TypeScript`

### [AI Resume Analyzer](https://github.com/undisputed-deb/AI-Resume-Analyzer)

NLP resume scoring against ATS criteria. 95% accuracy, cuts recruiter screening time by 60%, improves candidate to role matching by 35%.

`Flask` `Python` `NLP` `Google Gemini AI`

## experience

**Software Engineer Intern** · **Mutual of Omaha** *(Fortune 300)*
`Jan 2026 to Present` · Omaha, Nebraska
Spring Boot and Groovy microservices for a mainframe to microservice migration serving 3M+ policyholders. Moved IIB integrations to GitHub based workflows. Spock testing, Kubernetes and Docker deployments.

**Data Engineering Intern** · **Blackstone**
`Jun 2025 to Aug 2025` · Manhattan, NY
ETL pipelines processing 10K+ listings a day. Algolia search at 50K+ queries a day. PowerBI dashboards that saved the team 16 hours a week. Databricks and PySpark work that cut query time by 2.3x.

**Software Engineering Intern** · **Baxter St. Camera Club**
`Sept 2025 to Dec 2025` · Manhattan, NY
Brought 500+ digital assets to WCAG 2.1 AA. Built APIs on Firestore and Cloud Functions. Set up CI/CD on Azure DevOps.

**Chief Technical Officer** · **D.S. Tutoring Center**
`Mar 2024 to Present` · Bronx, NY
$47K+ revenue last year, 120+ students, 95% pass rate. Built the full stack exam portal myself.

## numbers that hit

```
ML fraud detection accuracy               99.7%
revenue generated                         $47K+
policyholders served via microservices    3M+
daily ETL throughput                      10K+ listings
WCAG accessibility coverage               85%
student pass rate                         95%
weekly hours saved with dashboards        16 hrs
false positive rate, fraud model          2.4%
```

## currently locked in on

▸ FinAdvisor and Aura, pushing both toward real users
▸ advanced ML and deep learning
▸ cloud architecture across AWS, GCP, and Azure
▸ data engineering with Apache Spark

<div align="center">

## let's build something

Open for internships, collabs, open source, and interesting problems in general.

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-00FFFF?style=for-the-badge&logoColor=black)](https://deb-portfolio-2flw.vercel.app/)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-7B2FBE?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/debshrestho/)&nbsp;
[![Email](https://img.shields.io/badge/EMAIL-FF2D78?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deb86011@gmail.com)

**"I push everything. The good stuff, the bad stuff, the 3am stuff. All of it."**

</div>

<!-- CYBERPUNK FOOTER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00FFFF,50:7B2FBE,100:0d0d0d&height=120&section=footer&animation=twinkling" />
