---
# Display name
title: 高健皓

# Name pronunciation (optional)
name_pronunciation: Jianhao Gao

# Full name (for SEO)
first_name: Jianhao
last_name: Gao

# Status emoji
status:
  icon: 🏗️

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: PhD student with background in Civil Engineering and Construction Managmenet

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: University of Florida
    url: https://www.ufl.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: sparkles
    url: 'https://vibe-fem.com/'
    label: Want to play with FEM the easy way? Try Vibe-FEM!
  - icon: at-symbol
    url: 'mailto:jianhaogao2022@gmail.com'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/JHaoGao
  - icon: brands/wechat
    url: 'wechat://Clark_JhG'
    label: WeChat - Clark_JhG

education:
  - area: PhD in Construction Management
    institution: University of Florida
    date_start: 2022-08-01
    date_end: 2026-08-31
    summary: |
      Department: College of Design, Construction, and Planning

      Research Focus: Computational Mechanics, AI for Materials

      Core Courses:
      Finite Element Method, Computational Elastoplasticity, Partial Differential Equations, Computational Fluid Dynamics, Differential Geometry

      Research Areas:
      - Phase-field fracture theory
      - AI-driven design and optimization for cementitious materials

      Teaching Assistant:
      - Construction Mechanics
      - AI in Built Environment
  - area: MS in Structural Engineering
    institution: Northwestern University
    date_start: 2021-08-01
    date_end: 2022-06-30
    summary: |
      Department: Civil and Environmental Engineering

      Core Courses:
      - Continuum Mechanics, Theory of Elasticity, High Performance Computing, Structural Dynamics, Plate and Shell Structures, Structural Stability, Structural Optimization

      Capstone Project: Redesign of Noyes Station light rail station in Chicago
  - area: BE in Bridge Engineering
    institution: Hunan University
    date_start: 2017-09-01
    date_end: 2021-06-30
    summary: |
      Department: College of Civil Engineering

      Core Courses:
      - Theoretical/Material/Soil/Fluid/Elastic/Structural Mechanics, Steel Structure Design, Concrete Structure Design, Bridge Engineering and Design

      Capstone Project: Highway river-crossing bridge design and finite element analysis of concrete-filled steel tubular arch bridge
work:
  - position: Research Assistant
    company_name: University of Florida
    company_url: 'https://www.ufl.edu/'
    company_logo: ''
    date_start: 2022-08-01
    date_end: ''
    summary: |2-
      Key Research Projects:
      - **Sustainable Concrete Mix Design Optimization (Generative AI + Multi-objective Optimization)**: Published in *Journal of Building Engineering* (NSF-funded). Developed VAE generative model integrated with NSGA-II for multi-objective optimization of compressive strength, CO₂ emissions, and cost. DOI: 10.1016/j.jobe.2024.110618
      - **Data-Driven Modeling of 3D Printable Concrete Rheology**: Published in *Construction and Building Materials* (NSF-funded). Compiled 10-year literature database for 3D-printed concrete rheology, developed ML prediction framework with SHAP interpreter. DOI: 10.1016/j.conbuildmat.2024.137912
      - **Linear Helical Printing**: Published in *Engineering Structures* (NSF-funded). Pioneered linear helical 3D printing technique with experimental validation and Abaqus FEM simulation, achieving up to 97.3% improvement in flexural strength. DOI: 10.1016/j.engstruct.2025.120219
      - **Phase-Field Fracture Modeling with Anisotropic Degradation**: Developed multi-degradation variable phase-field model for direction-dependent damage and fracture in anisotropic materials. Presented at 2025 ASCE EMI Conference.
      - **Video-Based Seismic Fault Slip Time Series Extraction**: Preprint arXiv:2505.20494. Combined machine vision, geometric projection, and field surveys to extract surface displacement time series from surveillance video.
      - **Fine-Tuned LLM for Concrete Property Prediction**: Constructed cementitious materials dataset using RAG+LoRA fine-tuning strategy for mix-to-strength prediction with enhanced interpretability.
      - **Computational Tool Development**: Developed Vibe-FEM (web-based FEM solver using Rust+WebAssembly), Nano-FEM (custom FEM framework), PhaseFracturer (phase-field fracture simulation), and FoamSees (soil-water interaction framework based on OpenSees).

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Programming Languages
    items:
      - name: Python
        description: 'Advanced proficiency'
        percent: 95
        icon: devicon/python
      - name: MATLAB
        description: 'Advanced proficiency'
        percent: 95
        icon: devicon/matlab
      - name: C++
        description: 'Advanced proficiency'
        percent: 90
        icon: devicon/cplusplus
      - name: Fortran
        description: 'Proficient'
        percent: 75
        icon: code-bracket
      - name: Rust
        description: 'Web development'
        percent: 70
        icon: devicon/rust
  - name: Computational Tools
    items:
      - name: Abaqus
        description: 'FEM simulation (UMAT/VUMAT)'
        percent: 95
        icon: cube
      - name: FEniCSx
        description: 'Phase-field modeling'
        percent: 95
        icon: cube
      - name: OpenSees
        description: 'Structural analysis'
        percent: 90
        icon: cube
      - name: LS-DYNA
        description: 'Simulation'
        percent: 90
        icon: cube
      - name: Midas Civil
        description: 'Bridge design'
        percent: 90
        icon: cube
  - name: AI/ML Tools
    items:
      - name: PyTorch
        description: 'Deep learning framework'
        percent: 90
        icon: devicon/pytorch
      - name: TensorFlow
        description: 'Machine learning'
        percent: 85
        icon: devicon/tensorflow

languages:
  - name: Chinese
    percent: 100
  - name: English
    percent: 95

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Mix design of sustainable concrete using generative models
    url: https://doi.org/10.1016/j.jobe.2024.110618
    date: '2024-09-01'
    awarder: Journal of Building Engineering
    icon: academic-cap
    summary: |
      Developed VAE generative model integrated with NSGA-II for multi-objective optimization of compressive strength, CO₂ emissions, and cost in sustainable concrete mix design. NSF-funded research.

      DOI: 10.1016/j.jobe.2024.110618
  - title: Data-driven rheological model for 3D printable concrete
    url: https://doi.org/10.1016/j.conbuildmat.2024.137912
    date: '2024-10-01'
    awarder: Construction and Building Materials
    icon: academic-cap
    summary: |
      Compiled comprehensive database from 10 years of literature on 3D-printed concrete rheology and developed machine learning prediction framework with SHAP interpreter for interpretability. NSF-funded research.

      DOI: 10.1016/j.conbuildmat.2024.137912
  - title: 'Linear helical printing: A novel approach to 3D printing concrete structures with enhanced integrity'
    url: https://doi.org/10.1016/j.engstruct.2025.120219
    date: '2025-01-01'
    awarder: Engineering Structures
    icon: academic-cap
    summary: |
      Pioneered linear helical 3D printing technique for concrete structures, validated through experiments and Abaqus FEM simulation, achieving up to 97.3% improvement in flexural strength compared to traditional methods. NSF-funded research.

      DOI: 10.1016/j.engstruct.2025.120219
  - title: Video-based Direct Time Series Measurement of Along-Strike Slip on the Coseismic Surface Rupture During the 2025 Mw7.7 Myanmar Earthquake
    url: https://arxiv.org/abs/2505.20494
    date: '2025-05-01'
    awarder: arXiv preprint
    icon: academic-cap
    summary: |
      Combined machine vision, geometric projection, and field surveys to extract surface displacement time series from surveillance video of the 2025 Myanmar earthquake coseismic fault rupture.

      arXiv:2505.20494
---

I am a PhD student in the School of Design, Construction and Planning at the University of Florida, specializing in computational mechanics and AI for materials. My research focuses on structural failure analysis and AI-driven design and optimization methods for cementitious materials. I develop computational tools and frameworks to advance sustainable construction materials and structural engineering.
