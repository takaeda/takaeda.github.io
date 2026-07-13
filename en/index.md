---
title: Yoshio Takaeda | Portfolio
description: Data Engineer / Researcher / High-Dimensional Time Series Analysis & Manufacturing Technology
lang: en
---

# Yoshio Takaeda
**Data Engineer / Researcher / Lecturer**  
Working with manufacturing data to develop predictive maintenance and stability control systems.

> Let AI organize the chaos; humans courageously add dimensions.

- [日本語版はこちら](/)

---

## Overview

With over 30 years of experience in manufacturing process design, data engineering, and analytics infrastructure development. From chemical plant design to genome analysis engines, polymer material databases, and current high-dimensional time series analysis—consistently pursuing data-driven problem solving.

Currently serving as a lecturer at Sophia University Graduate School, teaching "Practical High-Dimensional Data Analysis" and bridging theory with implementation.

---

## Experience

### Education
**Kyoto University Graduate School of Engineering** / Ph.D. (Engineering)  
Polymer Chemistry, Polymer Molecular Theory Laboratory (1995)

### Professional Experience

**Sophia University Graduate School, Applied Data Science Program** / Lecturer  
September 2023 - Present
- Teaching "Practical High-Dimensional Data Analysis"
- Integrated education from theory to implementation with practical case studies

**toor Inc.** / Founder & Chief Research Officer  
January 2012 - Present
- Research and development of high-dimensional time series analysis technology (toorPIA)
- Proof-of-concept studies for manufacturing data infrastructure and predictive maintenance systems
- Open source project development

**Public Tech Company** / Chief Technology Officer  
August 2006 - January 2012
- Technical development of intellectual property management systems and data infrastructure design
- Led technology strategy and operational optimization as CTO/COO

**Mitsubishi Research Institute** / Senior Research Scientist  
July 1998 - July 2006
- **International Human Genome Project**: Development of genome homology search engine
- **Polymer Materials Database**: Design, development, and implementation
- Industrial data analysis and simulation technology R&D

**TonenGeneral Sekiyu Chemical** / Research Engineer  
April 1995 - June 1998
- Design and implementation of PP/PE polymer manufacturing plants
- Process data engineering and analysis
- Chemical process optimization and quality control

---

## Technical Expertise

### Core Skills

**30+ Years of Data Engineering in Manufacturing**  
From chemical plant design to genome analysis, polymer material databases, and manufacturing equipment predictive maintenance—consistently pursuing data-driven solutions

**High-Dimensional Time Series Analysis**  
Handling hundreds to thousands of manufacturing process parameters as multidimensional vectors, enabling seamless (continuous) visualization of complex system state transitions across optimal time scales for dynamic characterization and predictive maintenance

**Acoustic Signal-Based Predictive Maintenance**  
High-quality audio data acquisition using DSP processing with Raspberry Pi + ADC + PreAmp + piezoelectric sensors to detect anomalies in rotating machinery and other manufacturing equipment

**Data Infrastructure Design**  
SQLite3 for rapid POC validation, PostgreSQL/TimescaleDB for production-scale time series data processing. Emphasis on appropriate technology selection

**Algorithm Development**  
Homology search (genomics), material property prediction (polymers), anomaly detection (manufacturing processes and acoustic signals)

### Technology Stack

- **Analysis & AI**: Python (NumPy/Pandas/scikit-learn/librosa), machine learning model implementation
- **Signal Processing**: DSP, FFT, wavelet transforms, acoustic feature extraction
- **Backend**: Node.js (API/real-time processing), Ruby on Rails (web applications), Go, C/C++ (high-performance processing, numerical computation, control systems)
- **Frontend**: JavaScript/TypeScript, React/Next.js
- **Data Infrastructure**: SQLite3 (POC/edge), PostgreSQL/TimescaleDB (production), Docker/Kubernetes
- **Edge Computing**: Raspberry Pi, high-precision ADC & PreAmp selection, piezoelectric sensor selection
- **Parallel Processing**: OpenMP, Go concurrency

---

## Research Projects

### 🧭 toorPIA (High-Dimensional Time Series Analysis Engine)
Research project for real-time analysis of manufacturing equipment parameters, automatic anomaly detection, and root cause identification.

**Research Focus**
- Predictive Maintenance: Early detection of anomalies using statistical methods
- Root Cause Analysis: Automatic identification of causal sensors and parameters
- Adjustment Recommendations: Generation of control parameter optimization proposals
- Implementation Validation: Proof-of-concept studies with CSV integration, GUI, and lightweight scripts

**Technology Stack**  
Python API (signal processing & analysis), BFF (Node.js + React/Next.js), PostgreSQL + TimescaleDB, Docker/Kubernetes

[→ GitHub: toorpia/toorpia](https://github.com/toorpia/toorpia)

### 🔊 Acoustic-Based Predictive Maintenance System
Research project for acquiring audio data from rotating machinery and other manufacturing equipment to detect anomalies.

**Technical Architecture**
- **Hardware**: Raspberry Pi + high-precision ADC + PreAmp + piezoelectric sensors
- **Signal Processing**: DSP, FFT, STFT, Wavelet, spectrogram analysis
- **Data Management**: SQLite3 (edge) → PostgreSQL (aggregation)
- **Analysis**: Detection of deviations from normal sound patterns, tracking time-series changes in frequency features

**Proof-of-Concept Results**
- Early detection of bearing degradation
- Classification of motor abnormal sounds
- Visualization and anomaly detection of vibration patterns

### 🪶 Local LLM Analysis
Experimental research project analyzing internal representations of local large language models to visualize proposition distances and bias structures.

[→ GitHub: toorpia-labs/local-llm-analysis](https://github.com/toorpia-labs/local-llm-analysis)

---

## Research Chronology

### 2012-Present: Manufacturing Predictive Maintenance (toor)
Consolidating 30 years of experience to develop technology that keeps manufacturing sites running. Dual approach using both process parameters and acoustic signals.

### 2006-2012: IP Management Systems (Venture Company)
Solving the complexity of intellectual property management through data infrastructure. Integration of technology and business.

### 1998-2006: Genomics & Materials DB (Mitsubishi Research Institute)
Large-scale data processing in the International Human Genome Project, structured data design for polymer materials database.

### 1995-1998: Chemical Plants (TonenGeneral)
Process design and data analysis for PP/PE polymer manufacturing plants. The foundation of manufacturing data engineering.

---

## Patents & Publications

### Patents (United States)

**Multidimensional Correlated Data Extracting Device and Method**  
US Patent 10,353,892 (2019)  
Method for extracting correlated subsets and identifying featured elements in multidimensional space

**State Determining Device and Method**  
US Patent 10,621,028 (2020)  
Time-series combination of device data and similarity-based state analysis

**Data Analysis Apparatus and Method**  
US Patent Application 20160109355  
Segment analysis using similarity indices based on frequency spectrum

**Document Retrieving Apparatus and Method**  
US Patent 8,818,979 (2014)  
Interactive document retrieval and query vector combination on 2D maps

**Analyzer, Analysis System, and Analysis Method**  
US Patent Application 20210232567  
Method for plotting new data on reference maps

**Information Display Method and Device**  
US Patent Application 20170213249  
Advertisement display clarifying relevance in search services

### Academic Publications

**Genome Analysis**
- DIGIT: a novel gene finding program by combining gene-finders. T. Yada, T. Takagi, Y. Totoki, Y. Sakaki, Y. Takaeda. *Pacific Symposium on Biocomputing*, 2003

**Polymer Solution Light Scattering & Nuclear Magnetic Relaxation Studies (1993-1997)**
- Dynamic depolarized light scattering and nuclear magnetic relaxation studies of isotactic oligo- and poly(methyl methacrylate)s in dilute solution. *Macromolecules*, 1997, 30(9), 2751-2758
- Dynamic depolarized light scattering and nuclear magnetic relaxation studies of oligo- and poly(methyl methacrylate)s in dilute solution. *Macromolecules*, 1995, 28(3), 682-693
- Mean-square optical anisotropy of isotactic oligo- and poly(methyl methacrylate)s in dilute solution. *Macromolecules*, 1995, 28(12), 4167-4172
- Dynamic depolarized light scattering and nuclear magnetic relaxation studies of oligo- and polystyrenes in dilute solutions. *Macromolecules*, 1994, 27(15), 4248-4258
- On the correlation between the negative intrinsic viscosity and the rotatory relaxation time of solvent molecules in dilute polymer solutions. *Macromolecules*, 1993, 26(25), 6891-6896
- Mean-square optical anisotropy of oligo- and poly(methyl methacrylate)s in dilute solutions. *Macromolecules*, 1993, 26(15), 3742-3749

---

## Research Philosophy

**Field-Oriented Approach**  
Pursuing structures that "continue to operate" rather than just theory. Always staying grounded in the field—from chemical plants to genome analysis to manufacturing equipment.

**Appropriate Technology Selection**  
Avoiding over-engineering. Start small and iterate quickly.

**Critical Thinking**  
Incorporating opposing viewpoints to surface risks early. An attitude learned from 30 years of failures and successes.

**Learning Cycle**  
Taking technology back to the field and learning from the field again. Mutually reinforcing education, practice, and research—emphasizing the trinity of these three elements.

**Public Individual Statement**
I believe that individual engineers should not be consumed by corporate structures, but instead deliver their value directly to the fields that truly need them.

---

## Contact

**GitHub**: [github.com/takaeda](https://github.com/takaeda)  
**ORCID**: [0009-0005-4968-9456](https://orcid.org/0009-0005-4968-9456)  
**arXiv**: takaeda (cs.LG)  
**Email**: [takaeda@gmail.com](mailto:takaeda@gmail.com)  
**Location**: Japan

*This site showcases personal research and educational activities and is non-commercial.*

---

<small>© 2025 Yoshio Takaeda | Personal Research Portfolio</small>
