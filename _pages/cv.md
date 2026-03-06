---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download a more complete PDF here](http://mrhheffernan.github.io/files/Heffernan_Matthew_CV.pdf)

Professional Experience 
======
* **AI Verification Engineer (Data Scientist + Software Engineer)** - *Zoox* (2022-Present)
  * Conducted applied research on a methods team, developing and deploying novel black-box safety quantification techniques for the AI driving stack. Built tools, automated processes, and data products using Python, Databricks, and PySpark to support autonomous driving evaluation, contributing to 9 patent applications (2 granted)
  * Designed a data-collection strategy, developed fleet simulations, and built a test asset orchestration system that enabled scaling and release of the Zoox service to the public. Drove continuous improvements resulting in over 99% uptime
  * Decomposed complex problems into known statistical problems, developed prototypes, and deployed tooling to orchestrate the test vehicle fleet and deliver $25M+ of log data for safety validation and AI development

Education
=====
* Ph.D. in Physics - *McGill University* (2022)  
  * Thesis: "Quantification of the Quark-Gluon Plasma with Statistical Learning"
* M.Sc. in Physics - *McGill University* (2018)
* B.Sc.(Hons.) in Physics, German Studies minor - *The College of William & Mary* (2016)

Research Experience
======
* **Graduate Research Assistant** - *McGill University* (2016-2022)  
  * Trained, validated, and deployed models for dimensionality reduction, regression, and statistical inference on several hundred gigabytes of high-dimensional data
  * Improved computational study design performance by over 50% for model prediction, sensitivity analysis, and uncertainty quantification using advanced statistical algorithms for design spaces robust to inactive dimensions
  * Executed and managed 1,000,000+ simulations and 500+ CPU years of computing resources valued at over $70,000 at national High Performance Computing facilities
  * Developed, validated, and automated C++ and Python scientific-computing tools for data analysis, streamlining the workflow and reducing manual job orchestration
  * Contributed to developing and validating statistical analysis for the most advanced C++ framework of a sophisticated nuclear physics environment (jetscape.org)

* **Undergraduate Student Researcher** - *The College of William & Mary* (2013-2016)  
  * Undergraduate honors thesis using computational methods (Python, Fortran) to probe Big Bang Nucleosynthesis for limits on Beyond Standard Model physics. This work was performed under the direction of [Andre Walker-Loud](http://ntc0.lbl.gov/~walkloud/).

* **Stirling Cycle Analyst for Nuclear Space Power Applications** - *NASA Glenn Research Center* (2015)  
  * LERCIP Intern with the Thermal Energy Conversion Branch working to improve model fidelity and performing simulations for the Test Demonstration Unit (TDU) for the pre-testing Test Readiness Review. Additional work was done to optimize Stirling engines to map power density-efficiency space and customize the piston-displacer waveform. Future applications of this work include deep space and space exploration applications as passive power units

* **REU Student** - *Texas A&M University and Cyclotron Institute* (2014)  
  * National Science Foundation (US)-funded studentship under Ralf Rapp studying hot and dense hadronic matter, resulting in a state-of-the-art parametrization of thermal photon production in hadronic matter.

Skills
=====
* **Probability & Statistics**  
  * Bayesian inference, Uncertainty quantification, Experimental design, Sensitivity analysis
* **Research**  
  * Design of Experiments, Statistical modeling, Data Science, Data visualization, Scientific computing
* **Programming**  
  * Python, Bash, Linux/Unix
  * Developing: SQL, Rust  
  * Author of the open source [maxpro](https://github.com/mrhheffernan/maxpro) [Rust crate](https://crates.io/crates/maxpro) and [Python package](https://pypi.org/project/maxpro/)
  * Other: Code review, Software testing, LaTeX, Markdown
* **Tools**  
  * Data Science
    * Databricks, PySpark
    * scikit-learn, Pandas, NumPy, SciPy, Matplotlib, Seaborn, SQLAlchemy, SALib
    * MCMC
  * Software
    * Git, GitHub, GitHub Actions
    * Jupyter, Bazel, Airflow, Slurm
    * PyO3, Rayon
    * Wolfram Mathematica
    * Flask, FastAPI
* **Teaching**
  ** Teaching
    * Pedagogical development for flipping a premier introductory physics course at McGill
    * Lab report and exam marking
    * Preparing tutorials
    * Leading student help sessions

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Organizing Committee Member, McGill Physics Hackathon (2018-2022)
* VP Communications, McGill Graduate Association of Physics Students (2017-2019)
