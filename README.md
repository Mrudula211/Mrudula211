<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,100:38BDF8&height=250&section=header&text=Mrudula%20Gharat&fontSize=60&fontColor=ffffff&animation=fadeIn&desc=AI%2FML%20Engineer%20%7C%20Building%20AI%20for%20the%20Real%20World&descSize=20&descAlignY=65" width="100%"/>
</div>

<div align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=800&lines=Computer+Vision+%E2%80%A2+Edge+AI+%E2%80%A2+LLM+Agents;IEEE+CVMI+2026+%E2%80%94+MediScopic-BC;YOLO+on+an+NPU+%E2%80%94+ex-AI+Intern+%40+RAMS+Digital;AI+that+knows+when+not+to+trust+itself" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <br/>
  <a href="https://www.linkedin.com/in/mrudula-gharat/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://mrudula211.github.io/Mrudula.dev-portfolio/"><img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="mailto:mrudulagharat0211@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <br/><br/>
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,100:38BDF8&height=2" width="100%"/>

### Hey, I'm Mrudula Gharat

I'm a **third-year B.Tech CSE (AI & ML) student** at Universal Ai University who builds AI systems end to end: datasets, models, evaluation, and the software that ships them.

So far I've built systems that:

- <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=opencv&logoColor=38bdf8" valign="middle"/> Detect warehouse rack damage and missing PPE with YOLO, running on an embedded NPU *(RAMS Digital internship)*
- <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=autodesk&logoColor=38bdf8" valign="middle"/> Generate IS-code-driven CAD drawing packages for water infrastructure in minutes *(SALT, team project)*
- <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=pytorch&logoColor=38bdf8" valign="middle"/> Flag their own likely mistakes before a medical diagnosis reaches a doctor *(IEEE CVMI 2026)*
- <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=googlegemini&logoColor=38bdf8" valign="middle"/> Answer questions in plain English with an LLM agent that is never allowed to state a number itself

Previously **AI Intern at RAMS Digital** (Apr–Jul 2026). Currently building a predictive-maintenance pipeline with my team for **Tata Elxsi TELIPORT Season 4**.

<br clear="right"/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,100:38BDF8&height=2" width="100%"/>

## How I Think About AI

> **Most AI projects end at "it works on test data." I try to report what the numbers really mean.**<br/>
> *Will this hold up when a doctor relies on it? When a warehouse worker's safety depends on it? When the model is wrong?*

1. <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=checkmarx&logoColor=38bdf8" valign="middle"/> **Honest evaluation:** held-out tests, multiple seeds, failed reproductions written down, not hidden.
2. <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=read-the-docs&logoColor=8b5cf6" valign="middle"/> **Calibrated uncertainty:** conformal bands, error auditors and humans in the loop.
3. <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=shieldsdotio&logoColor=10b981" valign="middle"/> **Safe failure:** deterministic guardrails, fallbacks, and rollback when a model gets worse.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,100:38BDF8&height=2" width="100%"/>

## Featured Work

<table width="100%">
<tr>
<td width="50%" valign="top">

### <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=pytorch&logoColor=white" valign="middle"/> MediScopic-BC
**Reliability-aware breast cancer histopathology AI · IEEE CVMI 2026**

A ResNet-50 classifier plus a ~5k-parameter auditor that reads the classifier's own confidence signals and flags likely errors for review. Co-author (2nd of 6), presented at COEP Technological University.

- **95.53%** accuracy, **0.967** F1 (image-level split)
- Auditor flagged **52 of 53 errors (98.1%)** at a 61% review rate
- Patient-level evaluation reported too: 81.98 ± 5.84%

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/ResNet--50-8B5CF6?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Grad--CAM-0EA5E9?style=for-the-badge&logoColor=white"/>

</td>
<td width="50%" valign="top">

### <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=googlegemini&logoColor=white" valign="middle"/> [Portfolio Analytics Agent](https://github.com/Mrudula211/portfolio-analytics-agent)
**LLM tool-calling agent over financial data**

Ask portfolio questions in plain English. Gemini plans guarded SQL and exposure-calculator calls; code formats every figure from the database.

- Read-only SQL enforced by SQLite's authorizer
- **10/10 exact** on the official set with the offline fallback
- **312 tests**, CI, Docker, [live on Render](https://portfolio-analytics-agent.onrender.com/)

<img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=opencv&logoColor=white" valign="middle"/> Edge AI for Warehouse Safety
**RAMS Digital internship · Apr–Jul 2026**

- Merged 7 public PPE datasets into a **32,269-image** corpus
- YOLO detectors up to **89.7% mAP@0.5**
- Deployed to a **Realtek AMB82-mini NPU** with ONNX and INT8 quantization
- Arduino C++ firmware with MQTT event publishing

<img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black"/>
<img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white"/>
<img src="https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white"/>

</td>
<td width="50%" valign="top">

### <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=autodesk&logoColor=white" valign="middle"/> SALT
**CAD automation for water infrastructure · RAMS Digital (team)**

*"Design a 2 MLD water plant" → multi-sheet DXF package in minutes, against 3–10 days of manual drafting.*

- Precedent library from 38 real drawings across 9 projects
- 26-check automated QA module
- The LLM only composes views; deterministic Python draws all geometry

<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/ezdxf-6B7280?style=for-the-badge&logoColor=white"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=mlflow&logoColor=white" valign="middle"/> Self-Healing Fleet
**Predictive maintenance · Tata Elxsi TELIPORT S4 (team, ongoing)**

NASA C-MAPSS sensor data → remaining-useful-life estimate with a conformal 90% band → automatic work orders.

- Test RMSE **10.0–11.2** across all 4 subsets (capped truth)
- 708 of 709 replayed engines flagged ≥5 cycles before failure
- MLflow drift → retrain → promote → automatic rollback

<img src="https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>

</td>
<td width="50%" valign="top">

### <img src="https://img.shields.io/badge/-%20-1e293b?style=flat-square&logo=pytest&logoColor=white" valign="middle"/> More projects
- **[AgniDrishti](https://github.com/Mrudula211/AgniDrishti)**: burn-in reliability screening with PASS / REVIEW / REJECT evidence cards (SIH 2026, PS 26170)
- **Think-or-Stop**: adaptive early-exit CNN, 89.28% CIFAR-10 accuracy at 63.5% of full-depth compute (41 tests)
- **Team hackathons (Regnum Carya):** [ANVESHA](https://github.com/codebyAtharva09/Anvesha) (ISRO beacon tracking), [EdgeSwarm](https://github.com/codebyAtharva09/AMR) (decentralized robot fleets), [Touchstone](https://github.com/codebyAtharva09/touchstone) (multi-agent job-offer verifier), [SkillBridge](https://github.com/codebyAtharva09/skillbridge) (on-chain credentials)

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,100:38BDF8&height=2" width="100%"/>

## Technical Arsenal

<table width="100%" align="center">
  <tr>
    <td width="30%" align="right"><b>Languages</b></td>
    <td width="70%">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="30%" align="right"><b>ML & Computer Vision</b></td>
    <td width="70%">
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
      <img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black"/>
      <img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="30%" align="right"><b>LLMs & Agents</b></td>
    <td width="70%">
      <img src="https://img.shields.io/badge/Gemini_API-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white"/>
      <img src="https://img.shields.io/badge/Tool_Calling-0EA5E9?style=for-the-badge&logoColor=white"/>
      <img src="https://img.shields.io/badge/LLM_Evaluation-10B981?style=for-the-badge&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="30%" align="right"><b>Backend & Frontend</b></td>
    <td width="70%">
      <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="30%" align="right"><b>MLOps & Tools</b></td>
    <td width="70%">
      <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
      <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
    </td>
  </tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,100:38BDF8&height=2" width="100%"/>

## Milestones & Achievements

| | |
|---|---|
| <img src="https://img.shields.io/badge/-%20-1e293b?style=for-the-badge&logo=ieee&logoColor=38bdf8" valign="middle"/> **IEEE CVMI 2026** | Co-author (2nd of 6), MediScopic-BC; presented at COEP Technological University, Pune |
| <img src="https://img.shields.io/badge/-%20-1e293b?style=for-the-badge&logo=opencv&logoColor=38bdf8" valign="middle"/> **RAMS Digital** | AI Intern (Apr–Jul 2026); Certificate of Appreciation and Letter of Recommendation |
| <img src="https://img.shields.io/badge/-%20-1e293b?style=for-the-badge&logo=hackthebox&logoColor=10b981" valign="middle"/> **Hackathons** | Tata Elxsi TELIPORT S4 · SIH 2026 · SerpApi India Hackathon 2026 · HackWithMumbai × UGF 2026 (Team Regnum Carya) |
| <img src="https://img.shields.io/badge/-%20-1e293b?style=for-the-badge&logo=kaggle&logoColor=f59e0b" valign="middle"/> **AI Odyssey** | Organizer; Certificate of Appreciation, AI Odyssey 1.0 (2025) |
| <img src="https://img.shields.io/badge/-%20-1e293b?style=for-the-badge&logo=jupyter&logoColor=10b981" valign="middle"/> **Rural AI Outreach** | Group Leader, SMART Project: AI sessions at government schools |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,100:38BDF8&height=2" width="100%"/>

## GitHub Activity

<div align="center">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=mrudula211&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=8b5cf6" />
  <br/><br/>
  <!-- Public server temporarily down: <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mrudula211&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&langs_count=8"/> -->
  <img height="160" src="./streak.svg" alt="Mrudula Gharat - GitHub Contribution Streak" />
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8B5CF6,100:38BDF8&height=2" width="100%"/>

## Open To

<div align="center">
  <img src="https://img.shields.io/badge/-%20-1e293b?style=for-the-badge&logo=pytorch&logoColor=38bdf8" valign="middle"/> <b>AI/ML Engineering Internships</b> &nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/-%20-1e293b?style=for-the-badge&logo=opencv&logoColor=5c3ee8" valign="middle"/> <b>Computer Vision & Edge AI</b> &nbsp;&nbsp;&nbsp;
  <img src="https://img.shields.io/badge/-%20-1e293b?style=for-the-badge&logo=googlegemini&logoColor=8b5cf6" valign="middle"/> <b>Applied LLM Systems</b>
</div>

<br/>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:38BDF8,100:8B5CF6&height=100&section=footer&animation=fadeIn"/>
  <i>AI that knows when not to trust itself. Systems that fail safely. Code that ships.</i>
</div>
