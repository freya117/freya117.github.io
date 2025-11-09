---
title: "AI for Sustainable Urban Energy Systems"
permalink: /courses/ai-urban-energy/
layout: wide
author_profile: false
header:
  overlay_color: "#ffffff"
---

<style>
  /* Make all content smaller */
  .page__content {
    font-size: 0.75em;
    padding-top: 0;
  }
  
  /* Style the page title */
  .page__title {
    color: #0033A0 !important;
    font-size: 1.8em !important;
    font-weight: bold !important;
    margin-bottom: 1em !important;
    margin-top: 0 !important;
    text-decoration: none !important;
    border-bottom: none !important;
    max-width: 1024px !important;
    margin-left: auto !important;
    margin-right: auto !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
  }
  
  /* Make headings blue */
  .page__content h2 {
    font-size: 1.25em;
    color: #0033A0;
    margin-top: 1.5em;
    margin-bottom: 0.5em;
  }
  
  .page__content h3 {
    font-size: 1.05em;
    color: #0033A0;
    margin-top: 1.2em;
    margin-bottom: 0.5em;
  }
  
  /* Course info box */
  .course-info-box {
    background-color: #f8f9fa;
    border-left: 4px solid #0033A0;
    padding: 1em 1.2em;
    margin: 1.5em 0;
    border-radius: 4px;
  }
  
  .course-info-box p {
    margin: 0.3em 0;
    font-size: 0.95em;
  }
  
  .course-info-box strong {
    color: #0033A0;
  }
  
  /* ILO list styling */
  .ilo-list {
    counter-reset: ilo-counter;
    list-style: none;
    padding-left: 0;
  }
  
  .ilo-list li {
    counter-increment: ilo-counter;
    margin-bottom: 0.8em;
    padding-left: 2em;
    position: relative;
  }
  
  .ilo-list li:before {
    content: counter(ilo-counter) ".";
    position: absolute;
    left: 0;
    color: #0033A0;
    font-weight: bold;
  }
  
  /* Table styling */
  table {
    width: 100%;
    border-collapse: collapse;
    margin: 1em 0;
    font-size: 0.9em;
  }
  
  table th {
    background-color: #0033A0;
    color: white;
    padding: 0.6em;
    text-align: left;
    font-weight: bold;
  }
  
  table td {
    padding: 0.6em;
    border-bottom: 1px solid #e0e0e0;
  }
  
  table tr:nth-child(even) {
    background-color: #f8f9fa;
  }
  
  /* Assessment box styling */
  .assessment-box {
    background-color: #fff;
    border: 1px solid #e0e0e0;
    border-radius: 4px;
    padding: 1em;
    margin: 1em 0;
  }
  
  .assessment-box h4 {
    color: #0033A0;
    margin-top: 0;
    font-size: 1em;
  }
  
  /* Rubric table */
  .rubric-table {
    font-size: 0.85em;
  }
  
  .rubric-table th {
    font-size: 0.9em;
  }
  
  /* Adjust list items */
  .page__content ul li {
    font-size: 0.9em;
    margin-bottom: 0.4em;
  }
</style>

## Course Information

<div class="course-info-box">
  <p><strong>Course number:</strong> 3-3-6</p>
  <p><strong>Meeting times:</strong> TBD</p>
  <p><strong>Classroom location:</strong> TBD</p>
  <p><strong>Website URL or learning management system:</strong> TBD</p>
</div>

## Instructor Information

**Freya Tan** (she/her)  
Email: freya117@mit.edu  
Office location: TBD  
Office hours: TBD  
Phone number: TBD

## Course Description

Cities use over two-thirds of the world's energy and drive the majority of carbon emissions. **AI for Urban Energy Systems** is a practice-oriented course where we learn—together as a community of analysts, planners, and engineers—how data and algorithms can help cities become cleaner, more affordable, and more resilient.

In this course, you'll frame real city energy problems, decide which AI tools fit (and why), and build clean, reproducible data workflows using meter/building and weather data. Through short demos, discussions, and weekly labs you will produce and evaluate forecasts (for demand or solar), formulate and solve operational decisions (like battery or EV-charging schedules), and detect anomalies in buildings and devices using interpretable methods. Because methods have consequences, you will also identify equity, privacy, bias, and security risks and propose practical safeguards for each use case. Throughout, you'll practice clear visuals, concise writing, and peer code reviews so your work is useful to both technical teams and city stakeholders.

This course connects to energy systems, data science, operations research, and public policy, and prepares you for roles in utilities, city sustainability offices, climate-tech, and consulting. No prior energy course is required; we provide on-ramps and emphasize collaborative learning and steady feedback. If you aim to make a measurable climate impact in cities, this course gives you tools to do it responsibly.

## Prerequisites/Corequisites

**Recommended:** Introductory programming course (Python, R, or MATLAB) and basic knowledge of energy or environmental systems.

**No formal prerequisites**; students from diverse majors are encouraged to enroll.

## Intended Learning Outcomes

By the end of this course, students will be able to:

<ol class="ilo-list">
  <li>Define a city-scale energy challenge and justify an AI approach to address it, stating key assumptions and limitations of the method chosen.</li>
  <li>Build a clean, reproducible data workflow for urban energy data (e.g., meter and building-management data plus weather): ingest, clean, document, and version the pipeline.</li>
  <li>Produce and evaluate short-term forecasts for demand or solar generation using appropriate baselines and error metrics, and communicate uncertainty clearly.</li>
  <li>Formulate and solve a practical operational decision (e.g., scheduling storage or EV charging) under real-world constraints, and compare alternatives on cost, emissions, and reliability.</li>
  <li>Detect and diagnose abnormal patterns in building or device data using interpretable features or models, and recommend feasible corrective actions.</li>
  <li>Evaluate ethical and societal risks—equity, privacy, bias, security—in data and models, and propose concrete safeguards suited to the use case.</li>
  <li>Communicate technical findings to mixed audiences with clear visuals and concise writing, and collaborate productively using peer code reviews and basic issue tracking.</li>
</ol>

## Course Materials

### Texts / Readings

- Curated articles, standards, and case studies (posted weekly on Canvas)
- Optional references posted per unit (e.g., forecasting primers, cvxpy documentation, utility tariff guides)

### Software / Hardware

- **Laptop** (8 GB RAM minimum recommended)
- **Python 3.11**, conda/mamba, Jupyter/VS Code, Git + GitHub
- **Packages:** pandas, numpy, matplotlib, scikit-learn, xgboost/lightgbm, prophet (optional), statsmodels, cvxpy, pydantic, hydra (or similar), mlflow (optional)
- We provide a repo template with environment.yml, Makefile, and example pipelines

### Data Access

- Open city datasets (AMI samples, BMS traces, PV outputs, weather) provided via Canvas + links to portals/APIs
- Course-specific sample datasets are cleared for class use

## What to Expect in This Course

This is a practice-oriented course built around doing, reflecting, and improving. Class time blends short concept introductions with guided practice and brief discussion so ideas move quickly from theory to use. Labs and studios give structured space to try methods on real data and get concrete feedback on visuals, writing, and reasoning. The team project ties pieces together on a realistic urban energy question and emphasizes clear recommendations backed by honest evaluation. Participation is flexible—speaking, writing, sketching, or peer feedback all count—and the classroom climate is collaborative and respectful. The overall aim is to build repeatable habits: clean workflows, calibrated forecasts, workable decisions, and clear communication to mixed audiences.

### Active Learning

Learning here is interactive by design. Most sessions include moments to think individually, compare ideas with peers, and share concise takeaways with the group. Roles in small groups rotate so airtime and responsibility are shared, and a written contribution is always an acceptable alternative to speaking. The goal is not performance but progress—regular practice with timely feedback—so everyone can engage meaningfully regardless of background.

## Assessments

### Overview & Weighting

- **Weekly Labs (best 8 of 10) — 40%**: Hands-on notebooks that develop your data pipeline, forecasting, optimization/control, and anomaly-detection skills.
- **Team Project (2–3 students) — 50% total**: 
  - Proposal 5% (Week 4)
  - Milestone 15% (Week 8)
  - Final Report 20%
  - Demo + 1-page Stakeholder Brief 10%
- **Participation & Peer Review — 10%**: Thoughtful questions, studio engagement, code reviews, and constructive feedback.

**ILOs covered:** Labs emphasize 2–5; Project integrates 1–7; Participation centers on 7 and supports 1.

### Assessment Details

<div class="assessment-box">
  <h4>1) Weekly Labs (40%)</h4>
  
  <p><strong>What you do to succeed:</strong></p>
  <ul>
    <li>Start from the provided template; implement your own steps for ingest/cleaning, modeling/optimization, and evaluation.</li>
    <li>Keep a reproducible repo: README.md, environment.yml/requirements.txt, and a simple run command (e.g., make reproduce).</li>
    <li>Use appropriate metrics (e.g., MAE/RMSE; reliability/calibration plots for probabilistic forecasts) and short, plain-language interpretations.</li>
  </ul>
  
  <p><strong>Alignment to ILOs:</strong> ILO 2 (pipelines), ILO 3 (forecasting & metrics), ILO 4 (optimization/control), ILO 5 (fault detection), with ongoing attention to ILO 6 (risk checks) and ILO 7 (clear figures/notes).</p>
  
  <p><strong>Grading rubric:</strong></p>
  <ul>
    <li>Technical correctness (data handling, models/solvers, constraints) – 40%</li>
    <li>Reproducibility (env file, run script, organization) – 25%</li>
    <li>Evaluation & interpretation (metrics used correctly; uncertainty explained) – 25%</li>
    <li>Presentation (figure readability; concise summary) – 10%</li>
  </ul>
  
  <p><strong>How class prepares you:</strong></p>
  <ul>
    <li>Formative supports: 5–10 min pre-lab checks, live notebook demos, and TA passes during lab to catch leakage, bad splits, or infeasible constraints.</li>
    <li>After-lab feedback: rubric comments within 7 days; sample solutions or exemplars when useful.</li>
  </ul>
</div>

<div class="assessment-box">
  <h4>2) Team Project (50%)</h4>
  
  <p><strong>Deliverables & weights:</strong></p>
  <ul>
    <li><strong>Proposal (5%, W4):</strong> Problem framing (stakeholders, objectives, constraints), data plan, success metrics, and identified risks.</li>
    <li><strong>Milestone (15%, W8):</strong> Working pipeline; initial forecasting/optimization results; evaluation plan; equity/privacy safeguards in progress.</li>
    <li><strong>Final Report (20%):</strong> 8–10 pages integrating methods, experiments, results, limitations, and a concrete safeguards plan.</li>
    <li><strong>Demo + Stakeholder Brief (10%):</strong> 6-minute demo and a 1-page plain-language brief with a specific recommendation.</li>
  </ul>
  
  <p><strong>How to succeed:</strong></p>
  <ul>
    <li>Choose a real urban energy use case (e.g., building load forecasting + battery scheduling).</li>
    <li>Build a clean, documented pipeline; compare at least one baseline and one improved method; report metrics honestly.</li>
    <li>Formulate constraints (e.g., demand charges, power limits) and justify trade-offs among cost, emissions, reliability.</li>
    <li>Identify equity/privacy/bias/security risks and propose practical safeguards.</li>
    <li>Communicate clearly to technical and non-technical audiences; practice team hygiene (issues, PRs, code reviews).</li>
  </ul>
  
  <p><strong>Overall grading rubric:</strong></p>
  <ul>
    <li>Problem relevance & framing – 15%</li>
    <li>Technical correctness & methodological rigor – 25%</li>
    <li>Reproducibility & documentation – 15%</li>
    <li>Evaluation depth & insight (baselines, metrics, uncertainty) – 15%</li>
    <li>Ethics & equity analysis (risks + feasible safeguards) – 10%</li>
    <li>Communication & stakeholder usefulness (report, brief, demo) – 20%</li>
  </ul>
  
  <p><strong>How class prepares you:</strong></p>
  <ul>
    <li>Studios (Weeks 8 & 12): structured peer critique on figures, methods, and risk plans.</li>
    <li>Optional draft review: upload a draft 24 hours before the deadline for targeted feedback.</li>
    <li>Scaffolded labs: forecasting and optimization labs mirror the project workflow so you can reuse patterns.</li>
  </ul>
</div>

<div class="assessment-box">
  <h4>3) Participation & Peer Review (10%)</h4>
  
  <p><strong>What you do to succeed:</strong> Contribute weekly (spoken or on the forum), complete assigned code reviews using the checklist, and respond to feedback professionally.</p>
  
  <p><strong>Alignment to ILOs:</strong> ILO 7 (communication/collaboration), supports ILO 1 (framing through discussion).</p>
  
  <p><strong>How it's graded:</strong> Consistency – 30%, Constructiveness – 40%, Professionalism – 30%</p>
  
  <p><strong>How class prepares you:</strong> Templates and examples for code reviews; instructor-modeled critique; short practice rounds.</p>
</div>

## Course Calendar

| Week | Topics/Focus | In-Class Activities | Lab/Studio | Deliverables (Due) |
|------|-------------|---------------------|------------|-------------------|
| 1 | Course on-ramp & ethics | Syllabus overview; AI-in-energy landscape; risk, bias & equity; Python refreshers | Environment setup & reproducibility checks | |
| 2 | Urban energy data & measurement | Data sources (AMI, BMS, DER, weather); data quality; feature engineering | Data audit & cleaning pipeline | |
| 3 | Time-series forecasting I | Baselines; splits; metrics (MAE/RMSE); classical models | Day-ahead building load forecasting | |
| 4 | Time-series forecasting II (ML/DL) | Gradient boosting; sequence models; uncertainty quantification | Model selection & validation pipeline | Project Proposal |
| 5 | Solar & wind forecasting; weather alignment | Weather features; spatial effects | PV power forecasting with probabilistic outputs | |
| 6 | Building energy modeling & analytics | Physics-informed vs. black-box; FDD concepts | Anomaly detection on BMS data | |
| 7 | Midterm studio & communication | Writing for stakeholders; model cards; reproducibility | Methods studio & peer critique | Midterm Methods Memo |
| 8 | Optimization & DER scheduling | Linear/convex formulations; tariffs; robustness | cvxpy: battery + demand-charge minimization | Project Milestone |
| 9 | Demand response & reinforcement learning | Control horizons; safety; offline RL basics | Simulated DR control | |
| 10 | EV charging & distribution impacts | Depot vs. public; fairness; transformer limits | Stochastic scheduling for EV fleets | |
| 11 | Microgrids & resilience | Islanding; contingency planning; unit commitment | Microgrid unit commitment (toy model) | |
| 12 | Scaling & MLOps for cities | Pipelines; monitoring; drift; security | Project peer critique (studio) | |
| 13 | Policy, procurement, and standards | Working with utilities/cities; data-sharing; privacy law | Cost–benefit & uncertainty communication | |
| 14 | Project demos & synthesis | Demos; course synthesis; retrospective | Final presentations | Final Report; Demo; Stakeholder Brief |

## Grading Philosophy & Procedures

- **Transparency:** Every assignment comes with a rubric you see in advance. Exemplars posted when available.
- **Flexibility:** Lowest two lab scores are dropped.
- **Revision option:** Use one revision token on either the Project Final Report or one Lab of your choice within 7 days for up to 50% point recovery. Include a brief change log describing fixes and validations.
- **AI tools policy:** You may use AI coding assistants with disclosure (note prompts, what you kept/changed, and how you verified). You are responsible for correctness, attribution, and data privacy.
- **Letter grades:** Per departmental scale (see Policies). Final scores are a weighted average of components above.

## Course Expectations and Policies

- **Attendance:** In-person is encouraged for labs and studios; recordings for concept sessions posted within 24 hours. Two no-questions-asked absences. Pedagogical purpose: labs are where you practice skills with feedback.
- **Participation:** Quality over quantity. Ask questions, propose tests, help peers. Online discussion counts.
- **Collaboration:** Discuss concepts freely; code you submit must be your own or your team's (for team tasks). Cite any external snippets or AI assistants used.
- **Use of technology:** Laptops welcome; mute notifications. Using generative AI tools is allowed with disclosure—include a short "AI usage" note describing prompts and edits; you are responsible for verification.
- **Late work:** 48-hr grace period on labs (–10%); major deliverables –10%/day up to 3 days, then by petition. Extensions available for documented circumstances—talk to me early.
- **Data ethics & privacy:** Use only approved datasets; remove identifiers; follow any data-sharing agreements.
- **Lab safety:** If working with hardware (meters, sensors) in optional fieldwork, follow the safety checklist.

## Inclusivity Statement

MIT values an inclusive environment. I hope to foster a sense of community in this classroom and consider this classroom to be a place where you will be treated with respect. I welcome individuals of all backgrounds, beliefs, ethnicities, national origins, gender identities, sexual orientations, religious and political affiliations – and other visible and nonvisible differences. All members of this class are expected to contribute to a respectful, welcoming, and inclusive environment for every other member of the class. If this standard is not being upheld, please feel free to speak with me.

## Academic Integrity Statement

In this course, I will hold you to the high standard of academic integrity expected of all students at the Institute. I do this for two reasons. First, it is essential to the learning process that you are the one doing the work. I have structured the assignments in this course to enable you to gain a mastery of the course material. Failing to do the work yourself will result in a lesser understanding of the content, and therefore a less meaningful education for you. Second, it is important that there be a level playing field for all students in this course and at the Institute so that the rigor and integrity of the Institute's educational program is maintained.

Violating the Academic Integrity policy in any way (e.g., plagiarism, unauthorized collaboration, cheating, etc.) will result in official Institute sanction. Possible sanctions include receiving a failing grade on the assignment or exam, being assigned a failing grade in the course, having a formal notation of disciplinary action placed on your MIT record, suspension from the Institute, and expulsion from the Institute for very serious cases.

Please review the [Academic Integrity policy](https://integrity.mit.edu/) and related resources (e.g., working under pressure; how to paraphrase, summarize, and quote; etc.) and contact me if you have any questions about appropriate citation methods, the degree of collaboration that is permitted, or anything else related to the Academic Integrity of this course.

## Special Accommodations and Disability Support Services

If you need disability-related accommodations, I encourage you to meet with me early in the semester. If you have not yet been approved for accommodations, please contact Student Disability Services at sds-all@mit.edu.

I look forward to working with you to assist you with your approved accommodations.

## Mental Health

As a student, you may experience a range of challenges that can interfere with learning, such as strained relationships, increased anxiety, substance use, feeling down, difficulty concentrating and/or lack of motivation. These mental health concerns or stressful events may impact your ability to attend class, concentrate, complete work, take an exam, or participate in daily activities.

Support for undergraduate and graduate students is available through the [doingwell@mit](https://studentlife.mit.edu/doingwell) site. Support for postdocs is available through MyLifeServices. For urgent or after-hours concerns, please visit DoingWell's page of 24/7 resources. These include:

- MIT Student Mental Health & Counseling Services - Clinicians on Call [617-253-2916]
- Urgent Care @MIT Medical [617-253-1311]
- ULifeline Crisis Text Line [Text: "START" to 741-741]
- MIT Police [617-253-1212]
