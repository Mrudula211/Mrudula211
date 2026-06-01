<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a1a2e,100:16213e&height=220&section=header&text=Mrudula%20Gharat&fontSize=56&fontColor=ffffff&fontAlignY=40&desc=AI%20Engineer%20%E2%80%94%20I%20build%20AI%20that%20works%20in%20the%20real%20world&descAlignY=60&descSize=17&animation=fadeIn"/>

</div>

<div align="center">

<a href="https://readme-typing-svg.demolab.com"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1200&color=38BDF8&center=true&vCenter=true&width=750&lines=Computer+Vision+%E2%80%A2+Industrial+AI+%E2%80%A2+Healthcare+AI;Drone-based+rack+inspection+%E2%80%94+RAMS+Digital;CAD+automation+for+water+infrastructure+%E2%80%94+SALT;AI+that+doesn't+just+predict+%E2%80%94+AI+that+explains+itself" alt="Typing SVG" /></a>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mrudulag-92a394267)
[![Portfolio](https://img.shields.io/badge/-Portfolio-8B5CF6?style=flat-square&logo=vercel&logoColor=white)](https://mrudula211.github.io/Mrudula.devportfolio/)
[![Gmail](https://img.shields.io/badge/-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mrudula.gharat@universalai.in)
![Visitors](https://komarev.com/ghpvc/?username=mrudula211&color=38bdf8&style=flat-square&label=visitors)

</div>

---

<img align="right" width="340" src="https://github-readme-stats.vercel.app/api?username=mrudula211&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=8b5cf6" />

### Hey, I'm Mrudula

I'm a **sophomore AI/ML engineer** who got tired of AI being just a classroom topic.

So I went and built systems that:

- ![factory](https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=opencv&logoColor=38bdf8) Inspect warehouse racks using drones + YOLO *(real deployment)*
- ![cad](https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=autodesk&logoColor=38bdf8) Generate full CAD drawings from plain English *(IS-code compliant)*
- ![health](https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=pytorch&logoColor=38bdf8) Audit their own confidence before making medical diagnoses
- ![code](https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=git&logoColor=38bdf8) Mentor developers with explainable code feedback

I'm at **RAMS Digital** right now, doing this for real infrastructure.

<br clear="right"/>

---

## ![wip](https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=hammer&logoColor=38bdf8) What I'm Building Now

### ![cv](https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=opencv&logoColor=white) AI Rack Inspection System &nbsp;`@ RAMS Digital`
> *Drones fly, YOLO sees, humans stay safe.*

Warehouse racks fail silently — until they don't. I'm building the CV pipeline that catches it first.

```
INPUT  →  Drone-captured imagery of warehouse racks
MODEL  →  YOLO-based multi-class object + defect detection
OUTPUT →  [GREEN] Safe  |  [AMBER] Repair in 4 weeks  |  [RED] Unload immediately
```

Detects: `dents` · `bends` · `cracks` · `beam damage` · `protector issues` · `arrangement faults`

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logo=yolo&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)

---

### ![salt](https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=autodesk&logoColor=white) SALT — Structural AI Layout & Transformation &nbsp;`@ RAMS Digital`
> *"Design a 2MLD water treatment plant" → full CAD package in minutes.*

Engineers used to spend days drafting. SALT takes a natural language requirement and spits out fully annotated, IS-code-compliant drawings.

```
"Design a 2 MLD WTP for 50,000 people"
         ↓  LLM parses intent
         ↓  Hydraulic sizing engine
         ↓  CAD generation (ezdxf)
         ↓  Compliance validation
OUTPUT: DXF · DWG · PDF · SVG
```

**My contributions:** CAD engine · DXF pipeline · hydraulic sizing · QA framework · LLM design synthesis

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude%20Opus-CC785C?style=flat-square&logo=anthropic&logoColor=white)

---

## ![projects](https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=folder-open&logoColor=8b5cf6) Past Projects

<table>
<tr>
<td width="50%">

### ![mediscopic](https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=pytorch&logoColor=white) MediScopic-BC
**Novel Dual-Brain architecture for breast cancer screening**

Two separate neural networks — one diagnoses, one audits the diagnosis. Because in healthcare, knowing *when not to trust the model* matters more than accuracy alone.

- Brain-1: ResNet CNN → **84.84% val accuracy**
- Brain-2: Reliability auditor → `Certain` / `Uncertain`
- Human-in-the-loop by design

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![XAI](https://img.shields.io/badge/Explainable%20AI-8B5CF6?style=flat-square&logoColor=white)

</td>
<td width="50%">

### ![codementor](https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=git&logoColor=white) CodeMentor AI
**AI developer coaching with a custom DevScore**

Not another linter. An AI coach that explains *why* your code is good or bad, scores it 0–100, and tells you how to grow.

- DevScore: readability + modularity + best practices
- Transparent over black-box
- Full-stack delivery

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20AI-4285F4?style=flat-square&logo=google&logoColor=white)

</td>
</tr>
<tr>
<td width="50%">

### ![karmas](https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=chatbot&logoColor=white) KARMAS – SIH 2025
**Healthcare AI for migrant workers**

Context-aware conversational AI with session-persistent memory. Built for people who can't afford to repeat their medical history every visit.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/Prompt%20Engineering-0EA5E9?style=flat-square&logoColor=white)

</td>
<td width="50%">

### ![research](https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=researchgate&logoColor=white) AI for Sustainable Packaging
**Research contribution**

Literature review and data analysis on AI-driven sustainability solutions in packaging design.

![Research](https://img.shields.io/badge/Published%20Research-10B981?style=flat-square&logo=researchgate&logoColor=white)

</td>
</tr>
</table>

---

## ![stack](https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=stackshare&logoColor=38bdf8) My Stack

```yaml
languages:    [Python, JavaScript, TypeScript, SQL, HTML, CSS]

computer_vision:
  models:     [YOLO, ResNet, CNNs]
  libraries:  [OpenCV, PyTorch, Ultralytics]

generative_ai:
  llms:       [Claude Opus, Gemini AI]
  techniques: [Prompt Engineering, LLM Agents, RAG, Sentence Transformers]

full_stack:
  backend:    [FastAPI, Flask, Node.js, Express]
  frontend:   [React, Next.js, Tailwind CSS, Three.js]
  data:       [NumPy, Pandas, Scikit-learn, SQLite]

engineering:
  cad:        [ezdxf, DXF/DWG generation, CAD automation]
  deployment: [ONNX, Edge AI, ONNX Runtime]

tools:        [Git, GitHub, VS Code]
```

---

## ![activity](https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=github&logoColor=38bdf8) GitHub Activity

<div align="center">
  <!-- Public server temporarily down: <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mrudula211&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&langs_count=8"/> -->
  <img height="160" src="./streak.svg" alt="GitHub Streak" />
</div>

---

## ![thinking](https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=brain&logoColor=8b5cf6) How I Think About AI

Most AI projects end at **"it works on test data."**

Mine don't.

I ask: *Will this hold up when a doctor relies on it? When a warehouse worker's safety depends on it? When an engineer ships infrastructure with it?*

That's why my projects are built around three questions:

> ![q1](https://img.shields.io/badge/Does%20it%20work%3F-1e293b?style=flat-square&logo=checkmarx&logoColor=38bdf8) &nbsp; Accuracy, benchmarks, real data
>
> ![q2](https://img.shields.io/badge/Does%20it%20explain%20itself%3F-1e293b?style=flat-square&logo=read-the-docs&logoColor=8b5cf6) &nbsp; XAI, uncertainty estimation, human-in-the-loop
>
> ![q3](https://img.shields.io/badge/Does%20it%20fail%20gracefully%3F-1e293b?style=flat-square&logo=shieldsdotio&logoColor=10b981) &nbsp; Edge cases, confidence thresholds, fallback logic

---

## ![milestones](https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=github-actions&logoColor=38bdf8) Milestones

| | |
|---|---|
| ![ind](https://img.shields.io/badge/-Industrial%20CV-1e293b?style=flat-square&logo=opencv&logoColor=38bdf8) | Building production-grade rack inspection system at RAMS Digital |
| ![cad](https://img.shields.io/badge/-CAD%20Automation-1e293b?style=flat-square&logo=autodesk&logoColor=38bdf8) | Co-developing SALT — AI-to-engineering-drawing pipeline in production |
| ![arch](https://img.shields.io/badge/-Novel%20Architecture-1e293b?style=flat-square&logo=diagram&logoColor=8b5cf6) | Invented Dual-Brain AI design for clinical reliability |
| ![sih](https://img.shields.io/badge/-Smart%20India%20Hackathon%202025-1e293b?style=flat-square&logo=hackthebox&logoColor=10b981) | Built KARMAS healthcare AI system |
| ![award](https://img.shields.io/badge/-Certificate%20of%20Appreciation-1e293b?style=flat-square&logo=award&logoColor=f59e0b) | AI Odyssey 1.0 (2025) |
| ![outreach](https://img.shields.io/badge/-Rural%20AI%20Outreach-1e293b?style=flat-square&logo=openai&logoColor=10b981) | Led AI education sessions at government schools — SMART Project |
| ![paper](https://img.shields.io/badge/-Research%20Contributor-1e293b?style=flat-square&logo=researchgate&logoColor=38bdf8) | AI for Sustainable Packaging |
| ![event](https://img.shields.io/badge/-Event%20Organizer-1e293b?style=flat-square&logo=eventbrite&logoColor=8b5cf6) | Co-organized AI Odyssey & Hawkthon @ UAI University |

---

## ![open](https://img.shields.io/badge/-%20-0d1117?style=flat-square&logo=handshake&logoColor=38bdf8) Open To

<div align="center">

![r1](https://img.shields.io/badge/AI%2FML%20Research%20Internships-1e293b?style=for-the-badge&logo=academia&logoColor=38bdf8)
![r2](https://img.shields.io/badge/Applied%20AI%20Roles-1e293b?style=for-the-badge&logo=robot-framework&logoColor=8b5cf6)
![r3](https://img.shields.io/badge/Healthcare%20AI%20Collaborations-1e293b?style=for-the-badge&logo=redcross&logoColor=f43f5e)
![r4](https://img.shields.io/badge/Industrial%20CV%20Projects-1e293b?style=for-the-badge&logo=opencv&logoColor=5c3ee8)
![r5](https://img.shields.io/badge/Open%20Source%20AI-1e293b?style=for-the-badge&logo=github&logoColor=white)

<br/><br/>

[![Let's talk](https://img.shields.io/badge/Let's%20build%20something-Email%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mrudula.gharat@universalai.in)
[![Connect](https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mrudulag-92a394267)

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0a0a0a&height=100&section=footer&animation=fadeIn"/>

*AI that explains itself. Systems that fail safely. Code that ships.*

</div>
