---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p>
<a href="https://www.linkedin.com/in/ahmed-g-rahma-233993190/"><i class="fab fa-fw fa-linkedin"></i> LinkedIn</a> &nbsp;|&nbsp;
<a href="https://orcid.org/0000-0001-5950-3348"><i class="ai ai-orcid ai-fw"></i> ORCID</a> &nbsp;|&nbsp;
<a href="https://scholar.google.com/citations?hl=en&user=AJt6JkIAAAAJ"><i class="ai ai-google-scholar ai-fw"></i> Google Scholar</a> &nbsp;|&nbsp;
<a href="https://www.researchgate.net/profile/Ahmed-Rahma"><i class="fab fa-fw fa-researchgate"></i> ResearchGate</a> &nbsp;|&nbsp;
<a href="mailto:ahmedgrahma@outlook.com"><i class="fas fa-fw fa-envelope"></i> Email</a>
</p>

{% assign cvpdf = site.static_files | where: "path", "/files/Ahmed_Rahma_CV.pdf" %}
{% if cvpdf.size > 0 %}<p><a href="/files/Ahmed_Rahma_CV.pdf"><i class="fas fa-fw fa-file-pdf"></i> Download the CV as PDF</a></p>{% endif %}

Profile
======
Postdoctoral researcher in numerical and experimental thermo-fluid engineering (PhD, University of Strasbourg, defended 1 October 2026) with 7+ years of CFD experience across academia and industry. Specialist in CFD, conjugate heat transfer, two-phase flow, FSI and FEM thermal/structural co-simulation, with 12 peer-reviewed journal papers (8 first-author).

Experience spans industrial R&D (Hyperheat GmbH), short-term numerical modelling support for an industrial partner (Geolith), multi-partner projects (Interreg 2PhaseEx with 2CRSI, BDR Thermea, SOGEFI, Secon; EU MICRO-FLOTEC with the University of Padova) and academic collaborations in six countries.

Employment history
======
* Oct 2026 – present: **Postdoctoral Research Fellow**
  * University of Strasbourg, ICube, Strasbourg, France
  * Continuing research within the Interreg 2PhaseEx project on two-phase thermosiphon heat exchangers for heat recovery in data centers, in collaboration with industrial partners.

* Sep 2024 – Oct 2026: **Doctoral Researcher**
  * University of Strasbourg, ICube, Strasbourg, France
  * Developed and validated a high-fidelity numerical model of a closed two-phase heat exchanger operating on the thermosiphon principle, supported by experimental data.
  * Used the model to optimize exchanger performance, identify optimal operating conditions, and assess the robustness of these conditions.

* Jun – Jul 2025: **Visiting Doctoral Researcher**
  * University of Padova, Vicenza, Italy
  * Visiting position under the MICRO-FLOTEC project (GAN 101082394), supervised by Prof. Simone Mancin, on numerical and experimental studies of two-phase thermosiphon systems for electronics cooling.
  * Work included surface treatment design, parametric analysis and test rig development.

* Sep 2024 – Oct 2026: **Teaching Assistant**
  * University of Strasbourg and Icam Strasbourg, Strasbourg, France
  * 64 hours of instruction per year. University of Strasbourg (36 h/year): guided students in advanced computational fluid mechanics, including practical use of CFD software. Icam Strasbourg-Europe (28 h/year): supervised fluid mechanics laboratory sessions, helping students with experiments and data analysis.

* Jul 2023 – Jun 2024: **Thermal and CFD Engineer**
  * Hyperheat GmbH, Offenburg, Germany
  * Developed CFD models for diverse applications, with fluid flow and heat transfer analyses for heating elements and prototypes, plus mechanical and fluid-structure interaction simulations.
  * Drove system designs with coupled thermal-electrical-fluid-structural models (co-simulation or static data transfers), and validated and enhanced models through CFD and FEM analyses.
  * Analysed CFD results to give design recommendations that improved product designs and heating performance. Worked in a hybrid setup, remote and on-site.

* Jun – Jul 2023: **M1 Intern, Research Assistant**
  * ICube, Strasbourg, France
  * Developed a fluidic separator for calibrating contrast-enhanced ultrasound scanners, using Lagrangian particle tracking and passive scalar transport simulation in OpenFOAM.

* Mar 2021 – Mar 2023: **Researcher**
  * Faculty of Electronic Engineering in Menouf, Al Minufiyah, Egypt
  * Provided simulation support for research projects and conducted CFD studies for hemodynamics analysis of human blood flow.
  * Wrote scientific papers, technology disclosures and reports. Worked remotely from Aug 2022, alongside Master's studies in Strasbourg.

* Jun 2020 – Mar 2021: **Mechanical Tender Engineer**
  * Brilliant Engineering Co., Giza, Egypt

* Jul 2019 – Jan 2021: **Teaching Assistant**
  * Misr University for Science and Technology, Giza, Egypt

Education
======
* Sep 2024 – Oct 2026: **Doctor of Philosophy (PhD)**
  * University of Strasbourg, Strasbourg, France
  * Thesis: Numerical Simulation of Two-Phase Closed Thermosiphon Systems for Cooling and Heat Recovery in Data Centers. Defended 1 October 2026.
  * Specialty: Fluid Mechanics (Doctoral School MSII, ICube).
  * Supervisors: Prof. Denis Funfschilling (CNRS, University of Strasbourg) and Prof. Abdellah Ghenaim (INSA Strasbourg); co-supervisor Dr. Abderahmane Marouf (University of Strasbourg).
  * Jury: reviewers Prof. Eric Goncalves (ISAE-ENSMA) and Prof. Nicolas Rimbert (University of Lorraine); examiners Prof. Yannick Hoarau (University of Strasbourg), Dr. Cécile Lemaitre and Dr. Rainier Hreiz (both University of Lorraine).

* Aug 2022 – Jun 2024: **Master's Degree in Computational Engineering**
  * University of Strasbourg, Strasbourg, France
  * Ranked first in class, while working (remote research position in Egypt, then hybrid CFD engineer at Hyperheat in Germany).

* Sep 2014 – Jul 2019: **Bachelor of Science in Mechanical Power Engineering**
  * Misr University for Science & Technology, Giza, Egypt
  * Top 5% in class. Final grade: 3.8/4 (87.34%).

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

International projects
======
* Sep 2024 – Aug 2027: **2PhaseEx** (PhD candidate and postdoctoral researcher)
  * Turning unused heat produced by data centers into a resource. Development of a closed-loop, two-phase heat exchanger based on the thermosiphon principle, using environmentally friendly fluids for thermal energy recovery. Industrial partners include 2CRSI, BDR Thermea, SOGEFI and Secon. Funding: Interreg Rhin Supérieur.
* Jun 2025 – Aug 2025: **MICRO-FLOTEC** (Visiting PhD researcher)
  * Microscale-Enabled Advanced Flow and Heat Transfer Technologies Featuring High Performance and Low Power Consumption. Hosted by the University of Padova. Funding: European Union, GAN 101082394.
* Mar 2021 – Mar 2023: **High-Performance Computing for Hemodynamics** (Research assistant)
  * High-Performance Computing Algorithms and Software Development for Hemodynamics Analysis of Human Blood Flow. Funding: 1 million EGP, Science and Technology Development Fund (STDF) of Egypt, No. 39385.

International collaboration
======
**Industrial**
* France: 2CRSI, BDR Thermea Groupe, SOGEFI Air Cooling, Quiri Groupe, Ziemex S.A.S., Wolfberger Cave Vinicole d'Eguisheim, Geolith
* Germany: Secon GmbH, Hyperheat GmbH

**Academic**
* France: University of Strasbourg, INSA Strasbourg, Université Paris-Saclay
* China: Harbin Institute of Technology, Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences, Southwest Jiaotong University, Southwest Petroleum University
* Germany: HKA, Hochschule Karlsruhe
* Italy: University of Milan, University of Padova
* United Arab Emirates: Khalifa University of Science and Technology
* Egypt: Menoufia University

Conferences and presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Skills
======
* Simulation: Ansys Workbench, Ansys Fluent, Ansys Thermal, Ansys APDL, STAR-CCM+, OpenFOAM, COMSOL
* Geometry and meshing: Pointwise, SpaceClaim, SolidWorks, AutoCAD
* Post-processing: Tecplot 360, ParaView, OriginLab
* Programming and computing: C++, Python, MATLAB and Octave, HPC, Linux
* Other: Microsoft Office

Reviewer
======
* Journals: Applied Thermal Engineering; International Communications in Heat and Mass Transfer; Energy; Scientific Reports; Physics of Fluids; Journal of Engineering and Applied Science; Adsorption; Discover Mechanical Engineering; BMC Musculoskeletal Disorders
* Conferences: The 7th International Conference on Biological Information and Biomedical Engineering (BIBE 2024)

Honours and awards
======
* Sep 2024: **Fully funded PhD position at ICube Laboratory, Université de Strasbourg**
  * Awarding institution: ICube Laboratory, Université de Strasbourg.
* Sep 2014: **Scholarship for Talented Students, Misr University for Science and Technology**
  * Awarding institution: Misr University for Science and Technology.

Languages
======
* English: C1
* Arabic: Native speaker
* French: A1
