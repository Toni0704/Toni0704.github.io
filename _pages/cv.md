---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **B.Tech in Engineering and Computational Mechanics**, *Indian Institute of Technology Delhi*, 2022–2026 (expected)  
  CGPA: **9.03 / 10.00**  
  Relevant coursework: Machine Learning, Deep Learning, Data Structures & Algorithms, Numerical Methods, Thermofluids, Mechanics of Solids, Computational Fluid Dynamics, and Finite Element Methods.

---

Experience
======
* **Research Intern — IBM Research (Gurgaon, India)** — *May–Jul 2025*  
  - Developed a **Retrieval-Augmented Generation (RAG)** pipeline for Root Cause Analysis using Granite LLMs.  
  - Experimented with embedding strategies, semantic chunking, and evaluation workflows in LangGraph.  
  - Contributed to a scalable knowledge-retrieval backend for industrial diagnostics.

* **Undergraduate Research Intern — National University of Singapore (Prof. Gianmarco Mengaldo)** — *May–Jul 2024*  
  - Worked on **Explainable AI for seismology**, combining deep learning for time-series prediction with post-hoc interpretability methods.  
  - Designed reproducible pipelines for model attribution and visual explanation of fault patterns.

* **Research Intern — Siemens Energy Ltd. (Gurgaon, India)** — *Dec 2024–Jan 2025*  
  - Explored **surrogate modelling and ML integration in CFD** workflows for gas turbine auxiliary systems.  
  - Evaluated regression and Gaussian-process models for performance prediction under uncertainty.  

* **Research Project — IIT Delhi (Computational Mechanics Laboratory)** — *2024–present*  
  - Developing **RegDGCNN-based surrogate models** for aerodynamic coefficient prediction from 3D car geometries.  
  - Investigating **Physics-aware Design Generation (PaDGAN)** for inverse design tasks.

* **Independent Project — Edge AI for Waste Classification** — *2023*  
  - Trained a **binary CNN (VGG-based)** on TrashNet data to classify organic vs recyclable waste.  
  - Deployed the model on a **Raspberry Pi with TensorFlow Lite and OpenCV**, integrating real-time inference via a camera module.

---

Skills
======
* **Programming:** Python, MATLAB, C/C++, Bash  
* **ML/AI Frameworks:** PyTorch, TensorFlow, TensorFlow Lite, scikit-learn, OpenCV, LangChain, LangGraph, Weights & Biases  
* **Engineering Tools:** SolidWorks, ANSYS, CFD/FEA pre- and post-processing  
* **Other Tools:** Git, Docker, Linux, Jupyter, LaTeX  
* **Soft Skills:** Research communication, technical writing, mentoring, interdisciplinary problem solving

---

Publications
======
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

Talks
======
<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

---

Teaching & Mentorship
======
<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

Service & Leadership
======
* **Convener**, *Computational and Applied Interdisciplinary Club (CAIC)* — IIT Delhi  
  - Led academic and outreach initiatives within the department, coordinating student-faculty research forums.  
* **Captain**, *Table Tennis Team (Satpura Hostel, IIT Delhi)* — 2023–24  
  - Led the team to inter-hostel tournaments and managed fitness and strategy sessions.  
* **Hackathon participation:** Interested in hacky, reproducible engineering demos combining AI and physics.

---

Awards & Scholarships
======
* **Dean’s List (IIT Delhi)** — for outstanding academic performance.  
<!-- * **KVPY Scholar (AIR < 500)** — Government of India, Department of Science & Technology.   -->
* **JEE Advanced (AIR 2608)** — National entrance examination for IITs.

---

Last updated: {{ site.time | date: '%B %Y' }}
