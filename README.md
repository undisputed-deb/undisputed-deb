```text
    ____  _____ ____
   |  _ \| ____| __ )    DEBASHRESTHA NANDI
   | | | |  _| |  _ \    ─────────────────────────────────────────
   | |_| | |___| |_) |   swe intern  ·  mutual of omaha (fortune 300)
   |____/|_____|____/     prev        ·  data engineering  ·  blackstone
                          cto         ·  d.s. tutoring center
```

> I build things to find out whether I can. Some repos here are experiments from
> when I was learning. Some run in production and people depend on them. Whatever
> it is, I push it.

`Omaha, Nebraska`  &nbsp;·&nbsp;  [portfolio](https://deb-portfolio-2flw.vercel.app/)  &nbsp;·&nbsp;  [linkedin](https://linkedin.com/in/debshrestho/)  &nbsp;·&nbsp;  [email](mailto:deb86011@gmail.com)  &nbsp;·&nbsp;  [my company](https://dstutoringcenter.company/)

<img src="https://profile-counter.glitch.me/undisputed-deb/count.svg" alt="visitor count" />

## now

Two builds have my attention. **FinAdvisor**, a portfolio tool that gives a real
verdict on every position instead of a pie chart. **Aura**, an AI that runs you
through a full voice interview and tells you where you cracked. Everything else is
ML that survives real data and APIs that stay up.

## shiplog

### FinAdvisor  ·  portfolio analysis dashboard

Paste your holdings or drop a broker screenshot. FinAdvisor scores your financial
health, checks emergency fund runway and cash flow, then rates every position buy,
hold, trim, or sell with an entry grade, a target, a stop loss, and a DCA size. A
what if drawer recomputes weights, yield, and concentration before you place a
trade. Gap analysis flags the sectors you are missing. All of it exports to a PDF.

```
verdict engine     buy / hold / trim / sell per position
health score       net worth, runway, cash flow
scenario drawer    recompute weights, yield, concentration pre trade
benchmarking       portfolio vs S&P 500, year long rebalance sim
output             full PDF portfolio report
```

**built with** &nbsp; Next.js 14 &nbsp; TypeScript &nbsp; Tailwind &nbsp; Recharts &nbsp; TanStack Query &nbsp; Zustand &nbsp; FastAPI &nbsp; pandas &nbsp; yfinance &nbsp; Gemini

[repo](https://github.com/undisputed-deb/Stock_predictor)

### Aura  ·  AI voice mock interview platform

People lose interviews because they never practice talking out loud. Reading tips
does nothing. Reps do. Upload your resume, name the company, and Aura runs a live
voice interview. Groq Whisper transcribes you in real time, Gemini scores clarity
and depth, and it tells you exactly where you fell short. It grills you on your own
resume, preps you company by company, coaches STAR structure, and tracks progress
across sessions.

```
pipeline       resume parse, live voice interview, AI scoring
coverage       resume grill, company prep, STAR coaching, progress
surface        18+ endpoints, Redis session state
security       zero auth incidents, Stripe webhook verification
```

**built with** &nbsp; Next.js 16 &nbsp; FastAPI &nbsp; Socket.IO &nbsp; SQLAlchemy 2.0 &nbsp; PostgreSQL &nbsp; Supabase &nbsp; Redis &nbsp; Groq Whisper &nbsp; Gemini 2.5 Flash &nbsp; OpenAI TTS &nbsp; Clerk &nbsp; Stripe

[repo](https://github.com/undisputed-deb/AURA)

### Credit Card Fraud Detection

Nine ML algorithms with ensemble voting, trained on 284K+ transactions at a 577 to
1 class imbalance. SMOTE plus Tomek links and stratified k fold so it holds up on
real data, not a clean benchmark.

```
roc auc            97.4%
accuracy           99.7%
fraud recall       91.8% at a 2.4% false positive rate
money saved        $6,570 per 100 fraud attempts
```

**built with** &nbsp; Python &nbsp; XGBoost &nbsp; scikit-learn &nbsp; SMOTE &nbsp; pandas &nbsp; matplotlib &nbsp; seaborn

[repo](https://github.com/undisputed-deb/Credit-Card-Fraud-Detection-System)

### All in One  ·  document and media processing

Eighteen plus endpoints, one Spring Boot 3.x and React service, three tools I used
to run apart now merged into one. PDF, image, and video operations behind JWT auth
with bcrypt, CORS, and rate limiting. FFmpeg and ImageMagick do the heavy lifting.

```
concurrency        50+ file operations at once
auth incidents     0
consolidation      3 services into 1
```

**built with** &nbsp; Java &nbsp; Spring Boot 3.x &nbsp; React &nbsp; TypeScript &nbsp; Tailwind &nbsp; FFmpeg &nbsp; ImageMagick

[repo](https://github.com/undisputed-deb/all-in-one-tools)

### PromptPower

Turns vague AI prompts into ones that get results. IP based rate limiting, XSS
protection, persistent storage. The security work most people skip until it bites.

**built with** &nbsp; Next.js 15 &nbsp; React 19 &nbsp; Gemini API &nbsp; TypeScript

[repo](https://github.com/undisputed-deb/PromptPower)

### Food Waste Management

Full stack platform tracking food waste from generation to composting. Role based
access, real time analytics, containerized deployment.

**built with** &nbsp; Spring Boot &nbsp; Vue.js &nbsp; PostgreSQL &nbsp; Docker &nbsp; JWT

[repo](https://github.com/undisputed-deb/Food-Waste-Management)

### AI Meeting Notes

Automated transcription and AI summaries that cut meeting follow up time by 40
percent. One click PDF export, sentiment analysis, MongoDB behind it.

**built with** &nbsp; Python &nbsp; React &nbsp; Gemini &nbsp; MongoDB &nbsp; TypeScript

[repo](https://github.com/undisputed-deb/ai-meeting-notes)

### AI Resume Analyzer

NLP resume scoring against ATS criteria. 95 percent accuracy, cuts recruiter
screening time by 60 percent, improves candidate to role matching by 35 percent.

**built with** &nbsp; Flask &nbsp; Python &nbsp; NLP &nbsp; Gemini

[repo](https://github.com/undisputed-deb/AI-Resume-Analyzer)

## track record

```
fraud model accuracy                       99.7%
revenue generated at the tutoring center   $47K+
policyholders served via microservices     3M+
daily ETL throughput at blackstone         10K+ listings
query time cut with databricks + pyspark   2.3x
weekly hours saved by my dashboards        16
student pass rate                          95%
students taught                            120+
wcag coverage on 500+ assets               85%
```

## where I have worked

**Software Engineer Intern**  ·  Mutual of Omaha (Fortune 300)
`Jan 2026 to now`  ·  Omaha, Nebraska
Spring Boot and Groovy microservices for a mainframe to microservice migration
serving 3M+ policyholders. Moved IIB integrations onto GitHub based workflows.
Spock testing, Kubernetes and Docker deployments.

**Data Engineering Intern**  ·  Blackstone
`Jun 2025 to Aug 2025`  ·  Manhattan, New York
ETL pipelines processing 10K+ listings a day. Algolia search at 50K+ queries a
day. PowerBI dashboards that saved the team 16 hours a week. Databricks and
PySpark work that cut query time by 2.3x.

**Software Engineering Intern**  ·  Baxter St. Camera Club
`Sept 2025 to Dec 2025`  ·  Manhattan, New York
Brought 500+ digital assets to WCAG 2.1 AA. Built APIs on Firestore and Cloud
Functions. Set up CI/CD on Azure DevOps.

**Chief Technical Officer**  ·  D.S. Tutoring Center
`Mar 2024 to now`  ·  Bronx, New York
$47K+ revenue last year, 120+ students, 95 percent pass rate. Built the full stack
exam portal myself.

## stack

```
languages     Python · Java · TypeScript · C++ · JavaScript
backend       Spring Boot · FastAPI · Flask · Django · Node
frontend      React · Next.js · Vue · Tailwind
data + cloud  PostgreSQL · MongoDB · Supabase · AWS · GCP · Azure · Docker · Kubernetes · Redis
ml            PyTorch · TensorFlow · scikit-learn · XGBoost
```

## reach me

Open for internships, collabs, open source, and interesting problems.

[portfolio](https://deb-portfolio-2flw.vercel.app/) &nbsp;·&nbsp; [linkedin](https://linkedin.com/in/debshrestho/) &nbsp;·&nbsp; [email](mailto:deb86011@gmail.com)

```text
I push everything. The good, the bad, the 3am commits. All of it.
```
