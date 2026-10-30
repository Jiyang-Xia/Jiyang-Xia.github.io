---
permalink: /
title: ""
excerpt: "Jiyang Xia — Ph.D. candidate in AI for Science at The University of Manchester. Seeking full-time opportunities starting in 2027."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>
![Urban landscape](../images/nature-7175030_1920.png)

I am a **Ph.D. candidate in AI for Science at The University of Manchester**, with expected completion in March 2027. My research brings together physics-guided deep learning, generative models, and scientific discovery agents to understand and simulate urban climate.

Alongside my research, I work on reliable LLM agents and model post-training. As a Qingyun Program intern at Tencent CSIG, I developed verification and refinement methods for DataBuddy and worked on tool-using SQL agents. Previously, I conducted research at Shanghai AI Laboratory on physics-guided urban climate modeling, leading to a first-author paper at **NeurIPS 2025**.

<div class="notice--info" markdown="1">
**Open to full-time opportunities starting in 2027.** I am actively seeking research and engineering roles in AI for Science, LLM agents, and model post-training. Please contact me at [jiyang.xia@manchester.ac.uk](mailto:jiyang.xia@manchester.ac.uk) to discuss opportunities.
</div>

<span class="anchor" id="-news"></span>

# 🔥 News
{: #news }

- *2026*: 🏅 Gold medal in the Kaggle Hull Tactical – Market Prediction competition.
- *2026.09*: Completed my Qingyun Program internship with the DataBuddy Agent Algorithms team at Tencent CSIG.
- *2026.08*: Our paper on automated LCZ mapping and thermal disparities was published in *Urban Climate*.
- *2026.05*: Received Google Cloud Research Credits to support agentic urban climate research.
- *2025.10*: Awarded the NeurIPS 2025 Scholar Award; my first-author paper on physics-guided urban climate modeling was accepted to NeurIPS 2025.
- *2025.07*: Presented at the 12th International Conference on Urban Climate, in the session on Digital Twins, AI/ML, and Open Data Science for Urban Climate.
- *2025*: Awarded the Doctoral Training and Development Support Fund by The University of Manchester.
- *2025.01*: Appointed as a Graduate Teaching Assistant for The Natural Scientists Toolkit course (2024–2025) at The University of Manchester.
- *2024.11*: My academic homepage is online!

# 🗂 Selected Projects
{: #projects }

### UrbanSurface-Agent
*2026 · Scientific discovery agents*

An autonomous system that combines LLMs with the SUEWS physical simulator to diagnose urban climate model errors. It proposes physical hypotheses, tests them through bounded parameter interventions, and uses a physics-based judge to distinguish meaningful improvements from compensating errors. Scenario-conditioned memory helps subsequent experiments learn from failed hypotheses. Evaluated across 20 real urban sites; the associated manuscript is under review.

### Remote Sensing + AutoML: Multi-Source Remote Sensing Fusion and High-Resolution Urban Climate Modeling
*2025–2026 · [Urban Climate 2026](https://doi.org/10.1016/j.uclim.2026.103001)*

- **Multi-source remote sensing fusion and feature engineering:** Built a multi-source Earth observation data pipeline in Google Earth Engine (GEE), integrating Sentinel-2 multispectral imagery, NDVI/NDBI spectral indices, GHSL building heights, and urban morphology features. Resampled and aligned data across spatial resolutions and time, then extracted features to create a **100 m urban surface feature dataset**.
- **AutoML classification and benchmarking:** Developed an automated remote sensing classification framework with FLAML, jointly selecting among LightGBM, XGBoost, and Random Forest and tuning their hyperparameters. Used class-balanced sampling and **25 polygon-level bootstrap validation runs** to avoid spatial sample leakage and assess robustness. Achieved **80% classification accuracy in Manchester**, a **5-percentage-point improvement over the WUDAPT baseline**, with cross-region validation in London and Barcelona.
- **Coupling remote sensing with climate modeling and evaluating extreme weather:** Converted remote-sensing-derived Local Climate Zone (LCZ) classifications into surface parameter inputs for the CLM5 land surface model. Combined these inputs with ERA5-Land meteorological forcing to run climate simulations at approximately **1 km resolution**. Validated heatwave air temperature simulations against **37 ground-based sensors**, reducing RMSE from **0.98 K to 0.90 K** and revealing **1.8 million person-hours of heat exposure** missed by conventional surface representations.

### Urban Climate RAG
*2026 · Retrieval and evidence-grounded generation*

A domain-specific knowledge system with two-stage retrieval: vector search followed by cross-encoder reranking. Answers are linked to source passages for traceable evidence. The system combines Qwen inference and embedding models with Ollama, FastAPI, Docker, and Open WebUI.

### Physics-Guided Urban Climate Emulation
*2024–2025 · NeurIPS 2025*

A multitask Transformer that models urban surface–atmosphere interactions using physical inductive biases. The model achieves **422× faster simulation** than the numerical baseline, improves prediction and cross-city generalization, and supports fine-tuning on real observations. Follow-up research has received NVIDIA academic support.

### Physics-Aware Diffusion for Urban Climate Adaptation
*2025–2026 · Ongoing research*

A generative modeling project that combines physical constraints with remote sensing imagery, meteorological time series, and socioeconomic features. The work explores urban climate adaptation scenarios and a spatially neutral evaluation benchmark, with physical consistency checks to assess generated results.

<span class="anchor" id="-publications"></span>

# 📝 Publications
{: #publications }

### Published papers

- **Jiyang Xia**, et al. [Optimized LCZ mapping with Automated Machine Learning Reveals Thermal Disparities during a Heatwave Event.](https://doi.org/10.1016/j.uclim.2026.103001) **Urban Climate**, 2026.
- **Jiyang Xia**, et al. [Learning Urban Climate Dynamics via Physics-Guided Urban Surface–Atmosphere Interactions.](https://proceedings.neurips.cc/paper_files/paper/2025/hash/b71cfefae46909178603b5bc6c11d3ae-Abstract-Conference.html) **NeurIPS**, 2025.
- **Jiyang Xia**, Yue Zhang*. [Where Are Potential Areas for Transit-Oriented Development (TOD)—Exploring the Demands for Built Environment for TOD Planning.](https://doi.org/10.3390/su14148364) **Sustainability**, 2022, 14, 8364.
- **Jiyang Xia**, Yue Zhang*. *Research on Spatial Spillover Effect of Highly Educated Migrants in Yangtze River Delta Urban Agglomerations Based on Urban Innovation.* **Areal Research and Development**, 2022, 1, 162–168.

### Manuscripts under review

- **Jiyang Xia**, et al. *When SQL Correctness is Not Enough: Verifying Contract-to-Delivery Conformance in Data Agents.* Submitted to ICLR 2027.
- Yu Zhang, **Jiyang Xia**, et al. *UrbanSurface-Agent: Physics-Gated Scientific Discovery for Urban Surface Parameterization.* Submitted to ICLR 2027.
- Yu Zhang, **Jiyang Xia**, et al. *LCZFormer: Learning Factorized Urban Surface–Climate Representations for Cross-City Urban Climate Emulation.* Submitted to KDD 2027.

<span class="anchor" id="-honors-and-awards"></span>

# 🎖 Honors and Awards
{: #honors-and-awards }

- *2026*: Gold Medal, Kaggle Hull Tactical – Market Prediction
- *2026*: Google Cloud Research Credits
- *2025*: NeurIPS Scholar Award
- *2025*: Doctoral Training and Development Support Fund, The University of Manchester
- *2024*: SoNS Research Training Support Grant, The University of Manchester
- *2023*: Excellent Postgraduate Students’ Award of Zhejiang Province (Top 1%)
- *2022*: Sophia Yang Scholarship, Zhejiang University (Top 1%)
- *2022*: Outstanding Postgraduate Award and “Triple-A” Student Award, Zhejiang University
- *2020*: Postgraduate Academic Scholarship, Zhejiang University
- *2018*: National “Outstanding Work” Award, National Urban Transportation Innovation Practice Competition

<span class="anchor" id="-educations"></span>

# 📖 Education
{: #education }

- *2024.01–2027.03 (expected)*: **The University of Manchester**, UK. Ph.D. candidate in **AI for Science**. Research interests: AI for climate science, representation learning, physics-guided deep learning, and scientific agents.
- *2020.09–2023.06*: **Zhejiang University**, China. M.Sc. in Urban Planning, with a focus on spatial big data analysis. **GPA: 3.88/4.0; rank: 1/31.**
- *2015.09–2020.06*: **Southwest Jiaotong University**, China. B.Eng. in Urban and Rural Planning.

<span class="anchor" id="-invited-talks"></span>

# 💬 Talks and Presentations
{: #talks }

- *2025.07*: [12th International Conference on Urban Climate](https://www.icuc12.eu/home.html), session on Digital Twins, AI/ML, and Open Data Science for Urban Climate, Rotterdam, Netherlands.
- *2024.08*: [NERC’s Digital Gathering 2024](https://www.digital-solutions.uk/dg24/schedule.html), Manchester, UK.
- *2022.07*: 16th International Association for China Planning (IACP) Annual Conference, session on Transit-Oriented Development, Wuhan, China.

<span class="anchor" id="-internships"></span>

# 💻 Experience
{: #experience }

### Tencent CSIG · Qingyun Program Intern
*2026.05–2026.09 · DataBuddy Agent Algorithms Team*

- Developed lightweight SQL verification and structured feedback to support automatic refinement within the agent loop, integrated into the DataBuddy production workflow.
- Designed asynchronous end-to-end verification to check whether an agent’s final delivery satisfies the user’s requirements, combining execution evidence, reconstructed contracts, deterministic checks, and LLM judgment.
- Built agentic trajectory datasets and feedback loops for SQL subagent post-training, using full supervised fine-tuning and LoRA with DeepSpeed.

### Shanghai AI Laboratory · Research Intern
*2024.03–2024.09 · AI for Earth*

- Developed a physics-guided Transformer for urban climate simulation, spanning problem formulation, data pipelines, model design, and experimental validation. This work led to a first-author NeurIPS 2025 paper.
- Contributed to urban climate agents that combine site characteristics, physical constraints, planning, tool use, and code execution for automated modeling experiments.

### China Southwest Architectural Design and Research Institute · Assistant City Planner
*2020.06–2020.08*
