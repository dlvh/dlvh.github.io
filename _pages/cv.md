---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version of this CV is available [here](/files/LyuDavid_CV_202601.pdf).

Education
======
* M.S. in Statistics, Stanford University, Sept 2024 – June 2026
* M.Sc. in Econometrics and Mathematical Economics (Merit), London School of Economics and Political Science, 2023
* B.A. in Economics and B.A. in Statistics (Highest Honors), University of California, Berkeley, 2021

Technical Skills
======
* **Programming**: Python (Pandas, NumPy, scikit-learn, PyTorch), R, SQL, STATA
* **Cloud & Big Data**: GCP, Spark, Snowflake, Databricks
* **ML / AI**: Deep Learning, LLMs, LangChain, LangGraph
* **Visualization**: Tableau, Recharts
* **Other**: Figma, Git, React, LaTeX
* **Languages**: Fluent English, Native Chinese (Mandarin, Wu), Business-Proficient Japanese (JLPT-N1)

Professional Experience
======
* **Inditex, S.A. (Zara)** — Data Scientist Intern, Technology / Data Solutions (June 2025 – Sept 2025), A Coruña, Spain
  * Built end-to-end data pipeline processing 2.2B+ RFID entries across all Zara stores in Spain using Python and SQL; developed an explainable anomaly detection algorithm with temporal pattern analysis and frequency-based scoring.
  * Applied process mining and clustering techniques to analyze article movement patterns; implemented multivariate statistical models to detect operational anomalies at scale across 400+ retail locations.
  * Presented findings to C-suite stakeholders via interactive dashboards; insights informed strategic decisions on RFID self-checkout deployment.

* **Kuaishou Technology** — Data Scientist, Data Platform / Experiments and A/B Testing (Oct 2023 – Jan 2024), Beijing, China
  * Supported platform-level A/B experimentation infrastructure serving 400M+ daily active users; conducted user experience research across three downstream workflows to optimize the experiment lifecycle.
  * Designed simulation studies evaluating rerandomization strategies on statistical power and Type I error rates; analyzed randomization quality via A/A test variations and bias detection.
  * Provided statistical consultation on causal inference, experimental design, significance testing, and power analysis; validated metric definitions and guardrail thresholds for product teams.

* **Goldman Sachs Group, Inc.** — Analyst, Financial Engineering / Controllers Modelling (July 2021 – Aug 2022), New York, NY
  * Led weekly EDA on large financial databases via complex SQL queries to support regulatory capital requirements and compliance reporting, with stakeholders in the US and the UK.
  * Optimized risk-weighted asset calculation models by implementing parallel computing in Slang (a GS-internal C++-based language), reducing weekly computation time by 20+ hours.

Research & Projects
======
* **Benchmark for Grading AI-Generated Patient-Friendly Radiology Reports** — Stanford AIDE Lab, Department of Radiology (Apr 2025 – Oct 2025; manuscript in preparation)
  * Designed statistical validation studies including inter-rater reliability analysis (Fleiss' Kappa) and power analysis to determine sample sizes for hypothesis testing with 80% power against baseline accuracy.
  * Conducted model evaluation through contingency table analyses and chi-square tests; designed randomized surveys via Qualtrics combining experimental design with field data collection.

* **Agentic AI System for Lung Nodule Segmentation and Radiology Report Generation** (Autumn 2024)
  * Built an end-to-end agentic system using MedSAM, the Gemini API, and PyTorch on GCP to segment lung nodules from 3D CT scans and generate radiology reports; collaborated with a radiologist to evaluate 25 AI-generated reports.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
