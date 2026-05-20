---
title: ""
permalink: /work/
author_profile: true
---

**Experimental physics, spintronics, instrumentation, automation, data workflows, and technical project ownership.**

I use this page as an extended project portfolio: a place to show the practical work behind my CV — experiments I built, systems I operated, measurements I automated, data workflows I developed, collaborations I supported, and people I mentored.

My strongest work sits at the intersection of **experimental design, magnetic materials, cryogenic measurement, thin-film systems, software automation, data analysis, and research coordination**. I enjoy turning unclear technical problems into measurable experiments, reliable workflows, and clear technical outputs.

[Download CV](/files/Akashdeep_CV.pdf){: .btn .btn--primary}
[View Publications](/publications/){: .btn .btn--info}
[Contact](/contact/){: .btn}

---

## At a glance

| Area | What I bring |
|---|---|
| **Experimental platforms** | Built, operated, automated, and troubleshot complex spin/magnon transport and magnetotransport setups |
| **Measurement automation** | Developed LabVIEW workflows for cryostat and FMR-based measurements, including long unattended runs |
| **Thin-film systems** | Worked with PLD, sputtering, RHEED integration, vacuum transfer, device fabrication, and characterization |
| **Cryogenic transport** | Performed low-temperature, high-field electrical and magnetic measurements down to approximately 2–3 K |
| **Data workflows** | Built Python/HDF5 analysis pipelines for large experimental datasets, plotting, fitting, and signal classification |
| **Project coordination** | Coordinated users, tools, beamtime, collaborators, samples, metadata, and experimental milestones |
| **Communication & mentoring** | Supported students, visiting researchers, collaborators, internal seminars, talks, posters, and technical documentation |

---

## Featured projects

These are the projects I would highlight first to industry recruiters, R&D teams, experimental research groups, and technical hiring managers.

---

## 1. Automated cryogenic spin-transport and magnetotransport platform

**Type:** Experimental platform, measurement automation, data acquisition  
**Role:** Direct technical contributor / operator / workflow developer  
**Relevant for:** R&D scientist, experimental physicist, test engineer, measurement engineer, instrumentation scientist

### Summary

Designed, built, operated, and automated complex experimental platforms for spin and magnon transport measurements. The systems combined cryogenic environments, superconducting magnets, low-noise electronics, lock-in detection, multi-channel wiring, sample rotation, and automated data acquisition.

### Problem

Spintronic and magnetic thin-film devices often require long measurement runs across many parameters: magnetic field, temperature, angle, frequency, device geometry, and harmonic detection channel. Manual operation is slow, error-prone, and difficult to reproduce.

### My contribution

- Developed and used LabVIEW-based control and automation workflows for cryostat and FMR-based measurements
- Enabled multi-day measurement runs with automated field and temperature sweeps
- Integrated data logging, alarm handling, remote monitoring, and measurement stability checks
- Maintained device wiring maps, contact verification routines, lock-in configurations, and quality-control checks
- Performed first- and second-harmonic detection with simultaneous longitudinal and transverse readout

### Methods and tools

LabVIEW, lock-in amplifiers, superconducting magnets, cryostats, low-noise electronics, multi-channel wiring, field/temperature sweep protocols, harmonic detection, magnetotransport, FMR-based workflows.

### Deliverables and impact

- More reliable long-duration measurements
- Reduced manual intervention during cryogenic experiments
- Better reproducibility across devices and parameter sweeps
- Faster comparison between samples, geometries, and measurement conditions
- Measurement workflows that could be used and understood by other researchers

### Skills demonstrated

Experimental design, automation, instrumentation, troubleshooting, cryogenics, low-noise measurement, data quality control, technical documentation.

---

## 2. RuO₂/permalloy spin-current magnetoresistance project

**Type:** Spintronics research, magnetotransport, altermagnetic materials  
**Role:** Major direct research contribution / first-author project  
**Relevant for:** Spintronics R&D, magnetic materials research, semiconductor/materials characterization, experimental condensed matter roles

### Summary

Investigated angle-dependent magnetoresistance in RuO₂/permalloy heterostructures to understand whether observed transport signals originate from intrinsic altermagnetic effects, interface-generated spin currents, or measurement-geometry contributions.

### Problem

RuO₂ has attracted attention as an altermagnetic material, but transport measurements in heterostructures can contain multiple overlapping signals. A key challenge is separating intrinsic material behavior from interface effects and measurement artifacts.

### My contribution

- Planned and executed magnetotransport experiments on RuO₂-based heterostructures
- Used angle-dependent and symmetry-resolved measurement protocols
- Compared field-orientation, crystal-orientation, and device-geometry-dependent signals
- Interpreted competing contributions from bulk, interface, and measurement-mixing effects
- Contributed to manuscript preparation, figures, analysis, and scientific discussion

### Methods and tools

Angle-dependent magnetoresistance, spin Hall magnetoresistance, Hall measurements, field-angle protocols, temperature-dependent transport, crystallographic-orientation analysis, RuO₂/permalloy thin-film heterostructures.

### Deliverables and impact

- Clarified the importance of interface-generated spin currents in RuO₂/ferromagnet heterostructures
- Provided a careful experimental framework for separating interface-driven and bulk material contributions
- Strengthened my experience in rigorous transport analysis and mechanism separation

### Related output

First-author publication in *Physical Review Applied*.

### Skills demonstrated

Spintronics, magnetotransport, symmetry analysis, experimental design, data interpretation, scientific writing, mechanism separation.

---

## 3. Thin-film growth, PLD/RHEED integration, and shared-tool ownership

**Type:** Instrumentation, thin-film growth, vacuum systems, user support  
**Role:** Local tool owner / operator / user-support lead  
**Relevant for:** Process engineer, thin-film R&D, lab engineer, research infrastructure, semiconductor/materials roles

### Summary

Served as a main operator and local tool owner for high-value thin-film deposition infrastructure, including PLD, magnetron sputtering, oxygen ion etching, RHEED integration, and vacuum-transfer workflows.

### Problem

Advanced magnetic thin-film research depends on reliable growth infrastructure, clean process flows, trained users, stable tool access, and careful coordination between deposition, patterning, and measurement steps.

### My contribution

- Operated excimer-laser PLD infrastructure and magnetron sputtering systems
- Helped assemble and commission a 4-gun magnetron sputtering system
- Integrated RHEED with a PLD chamber, including alignment, calibration, validation, and user procedures
- Designed and tested a vacuum suitcase transfer workflow between PLD and sputtering systems
- Coordinated tool scheduling, user onboarding, process support, safety guidance, and troubleshooting
- Managed expensive consumables such as targets, process gases, and excimer gases
- Supported cleanroom and deposition users across thin-film growth, patterning, and device workflows

### Methods and tools

PLD, DC/RF magnetron sputtering, reactive sputtering, RHEED, oxygen ion etching, vacuum suitcase transfer, UHV systems, target exchange, substrate heating, process gases, tool scheduling, SOPs.

### Deliverables and impact

- Improved usability and reliability of shared experimental infrastructure
- Supported multiple users and research projects through tool access, training, and troubleshooting
- Created practical operating procedures, safety routines, and process guidance
- Helped connect thin-film growth workflows to downstream characterization and device fabrication

### Skills demonstrated

Instrumentation, vacuum systems, thin-film processing, user training, technical ownership, safety awareness, process coordination, troubleshooting.

---

## 4. Python/HDF5 experimental data workflows

**Type:** Data analysis, reproducible research, automation  
**Role:** Direct developer / analysis workflow builder  
**Relevant for:** Data scientist in R&D, scientific software, measurement automation, experimental data analysis

### Summary

Developed Python- and HDF5-based workflows for processing large experimental datasets from magnetotransport, FMR, spin transport, and magnon-transport measurements.

### Problem

Modern experimental projects generate large datasets across many parameters: magnetic field, temperature, angle, frequency, sample batch, device geometry, and measurement channel. Without standardized workflows, analysis becomes slow, inconsistent, and difficult to reproduce.

### My contribution

- Built batch-processing workflows for field-, temperature-, angle-, and frequency-dependent datasets
- Designed HDF5-based data structures with metadata handling and standardized naming conventions
- Used Python tools for feature extraction, plotting, fitting, comparison across samples, and reproducible figure generation
- Applied basic machine-learning and statistical methods for pattern detection, signal classification, and artifact recognition
- Shared scripts and analysis workflows with collaborators for reproducible interpretation

### Methods and tools

Python, pandas, NumPy, matplotlib, HDF5, OriginPro, reproducible plotting, batch processing, metadata schemas, feature extraction, regression, classification, signal analysis.

### Deliverables and impact

- Faster and more consistent analysis of large parameter-sweep datasets
- Reusable plotting and fitting routines for papers, presentations, and internal reports
- Better metadata organization for collaboration and reproducibility
- Improved ability to compare samples, devices, and measurement conditions

### Skills demonstrated

Scientific programming, data engineering, reproducible analysis, automation, visualization, statistical thinking, communication through figures.

---

## 5. Large-scale facility experiments: synchrotron, PEEM, and low-energy muon spectroscopy

**Type:** Facility science, proposal writing, collaborative experiments  
**Role:** Proposal contributor / local coordinator / experimental support  
**Relevant for:** Research scientist, facility user, project coordinator, experimental R&D roles

### Summary

Led and supported large-scale facility experiments involving synchrotron-based XMLD/XMCD-PEEM, X-ray measurements, and low-energy muon spectroscopy on magnetic thin-film systems.

### Problem

Facility experiments are time-limited, technically demanding, and coordination-heavy. Success depends on strong preparation: proposals, sample readiness, logistics, priority planning, measurement strategy, fallback plans, and quick interpretation during beamtime.

### My contribution

- Contributed to competitive beamtime proposals and experimental planning
- Supported sample preparation, shipment, beamtime logistics, on-site alignment, data acquisition, and quick-look analysis
- Helped coordinate sample histories, metadata, measurement priorities, and reporting to collaborators
- Participated in facility experiments connected to RuO₂ magnetic order and altermagnetic thin films

### Methods and tools

XMLD/XMCD-PEEM, synchrotron X-ray measurements, low-energy muon spectroscopy, beamtime planning, proposal writing, sample logistics, quick-look analysis, collaborative reporting.

### Deliverables and impact

- Supported peer-reviewed large-scale facility access
- Contributed to experimental evidence for magnetic order in advanced thin-film systems
- Strengthened experience in time-sensitive, high-pressure, multi-partner research environments

### Skills demonstrated

Proposal writing, facility coordination, experimental preparation, collaboration, data interpretation, communication under time pressure.

---

## 6. Cryogenic magnetotransport and device-measurement workflow

**Type:** Measurement workflow, device characterization, cryogenics  
**Role:** Direct operator / workflow developer  
**Relevant for:** Test engineer, device characterization, low-temperature measurement, materials R&D

### Summary

Set up and used low-temperature, high-field electrical and magnetotransport measurement workflows for thin films and microstructured devices.

### Problem

Device-level measurements require reliable contacting, sample mounting, wiring verification, geometry-aware data acquisition, and careful interpretation of longitudinal and transverse voltage signals.

### My contribution

- Performed DC and low-frequency transport measurements on thin films and microstructured devices
- Measured four-probe resistance, longitudinal resistance, transverse/Hall resistance, and field-dependent transport
- Used cryostat-based setups with superconducting magnets for temperature, field, and angular sweeps
- Prepared devices through layout selection, electrical contacting, wire bonding, and continuity verification
- Developed contact maps, sweep protocols, and data-quality checks

### Methods and tools

Cryogenic transport, Hall-bar geometries, four-probe measurements, lock-in detection, wire bonding, lithography, superconducting magnets, low-temperature stabilization, multi-contact wiring.

### Deliverables and impact

- Reliable device-level measurement workflows
- Better separation of longitudinal/transverse signals and measurement artifacts
- Improved sample readiness for long cryogenic experiments
- Practical experience translating material systems into measurable devices

### Skills demonstrated

Device characterization, cryogenics, low-noise electronics, sample preparation, measurement planning, troubleshooting.

---

## 7. Heusler alloy thin films for spintronic device applications

**Type:** Master’s / research assistant project, thin-film materials, transport  
**Role:** Direct research contributor  
**Relevant for:** Materials R&D, thin-film processing, magnetic devices, semiconductor-adjacent roles

### Summary

Grew and characterized sputtered Heusler alloy thin films for non-volatile memory and spintronic device applications, linking growth conditions to structural, magnetic, and electrical properties.

### Problem

Spintronic materials require controlled growth and reproducible characterization. Deposition parameters can strongly affect anisotropy, transport behavior, switching, stability, and device-relevant performance.

### My contribution

- Grew Heusler alloy thin films by magnetron sputtering
- Optimized deposition conditions and linked process parameters to material properties
- Performed structural, magnetic, and magnetotransport characterization
- Designed and built a custom electrical transport insert/rod for cryostat-based measurements
- Developed LabVIEW-based control and calibration routines to validate measurement reliability
- Created Origin/Python tools for endurance, retention, and failure-distribution analysis

### Methods and tools

Magnetron sputtering, temperature-dependent electrical transport, magnetic anisotropy measurements, longitudinal/transverse MOKE, cryostat insert design, LabVIEW, Python, OriginPro.

### Deliverables and impact

- Improved understanding of growth–structure–property relationships
- Built custom measurement hardware for cryostat-based transport
- Developed reproducible analysis routines for sample comparison and device-relevant stability studies
- Contributed to thesis documentation, technical reports, and presentations

### Skills demonstrated

Thin-film growth, process optimization, custom instrumentation, transport measurement, magnetic characterization, technical reporting.

---

# Collaborative research contributions

The following projects involved larger collaborations. I include them because they show my ability to contribute to multi-institutional research, connect theory and experiment, and work across different techniques and material systems.

---

## 8. Altermagnetism in RuO₂, hematite, and related materials

**Type:** Collaborative research, magnetic symmetry, advanced characterization  
**Role:** Experimental contributor / collaborator depending on project  
**Relevant for:** Research collaboration, materials science, spintronics, quantum materials

### Summary

Contributed to collaborative research on altermagnetic and compensated magnetic systems, including RuO₂, hematite, and related oxide materials.

### Focus areas

- Time-reversal symmetry breaking in RuO₂
- Magnetic circular dichroism in RuO₂ films
- XMCD imaging and anomalous Hall transport in hematite
- Optical excitation of spin polarization in d-wave altermagnets
- Separating intrinsic magnetic responses from interface, surface, and measurement-geometry effects

### Methods and concepts

Spin-resolved and X-ray-based characterization, XMLD/XMCD, MCD-XPS, PEEM, anomalous Hall transport, symmetry arguments, crystal-orientation dependence, altermagnetic spin splitting, theory–experiment comparison.

### What this shows

- Ability to work in fast-moving research areas
- Experience connecting theoretical predictions to experimental observables
- Collaboration across materials growth, spectroscopy, transport, theory, and data interpretation
- Comfort communicating complex physics to mixed technical audiences

### Related outputs

Coauthored publications and manuscripts on RuO₂, hematite, and d-wave altermagnetic systems.

---

## 9. Magnon transport and ferrimagnetic garnet systems

**Type:** Spin dynamics, magnonics, ferrimagnetic systems  
**Role:** Research contributor / collaborator  
**Relevant for:** Spintronics, magnonics, magnetic device concepts, experimental R&D

### Summary

Worked on spin and magnon transport in garnet-based systems, including Y₃Fe₅O₁₂, Gd₃Fe₅O₁₂, and Tb₃Fe₅O₁₂.

### Focus areas

- Electrically and thermally generated magnon currents
- Local and nonlocal magnon transport geometries
- Magnon diffusion and separation-dependent signal analysis
- Damping, relaxation, compensation, and magnetic anisotropy
- Coupled ferrimagnetic modes in YIG/GdIG/Pt trilayers
- Topological Hall-like responses in rare-earth iron garnet systems

### Methods and concepts

FMR, broadband VNA-FMR, spin pumping, spin Seebeck effect, inverse spin Hall detection, nonlocal transport, background subtraction, thermal-artifact checks, magnetic anisotropy analysis.

### What this shows

- Strong domain knowledge in magnon-based spintronics
- Ability to interpret temperature-dependent and geometry-dependent signals
- Experience with complex ferrimagnetic material systems and compensation-related effects

### Related outputs

Coauthored work on YIG/GdIG/Pt trilayers, TbIG/Pt systems, and altermagnetic magnon transport.

---

# Project coordination, mentoring, and leadership

Technical work is not only about measurements. Many successful experiments depend on coordination, documentation, communication, and the ability to support other people.

---

## 10. Shared-tool user management and research coordination

**Type:** Technical project management, user support, shared infrastructure  
**Role:** Local system owner / coordinator  
**Relevant for:** R&D project coordination, lab management, process engineering, team-based technical roles

### Summary

Managed shared experimental infrastructure and coordinated users, tools, schedules, consumables, and process flows across multiple research projects.

### My contribution

- Maintained booking calendars and resolved scheduling conflicts
- Prioritized tool access between PhD projects, urgent experiments, visiting users, beamtime preparation, and publication deadlines
- Created practical usage rules, onboarding procedures, safe-operation checklists, handover expectations, and escalation routes
- Coordinated targets, substrates, chemicals, gases, consumables, delivery timelines, and experimental schedules
- Helped align material availability with growth runs, fabrication, cryogenic measurements, and beamtime deadlines

### What this shows

- Ownership of complex shared systems
- Ability to balance technical, operational, and people-related constraints
- Practical leadership without relying on formal authority
- Strong organization under real experimental pressure

---

## 11. Mentoring students and visiting researchers

**Type:** Teaching, mentoring, technical supervision  
**Role:** Mentor / supervisor / host  
**Relevant for:** Team-based R&D, academic research, technical training, leadership development

### Summary

Mentored and supported B.Sc. and M.Sc. students, visiting PhD researchers, and early-stage researchers in experimental spintronics and magnetic materials projects.

### My contribution

- Supported students from project definition to sample preparation, measurement, analysis, and documentation
- Guided hands-on workflows including cleanroom processing, electrical contacting, cryostat measurements, data-quality checks, and Python-based analysis
- Helped students prepare theses, figures, posters, presentations, and explanations of limitations or uncertainties
- Hosted and supported visiting researchers from international groups, including lab introductions, safety orientation, logistics, tool access, and integration into ongoing workflows

### What this shows

- Ability to explain complex technical topics clearly
- Patience and structure in mentoring
- Cross-cultural communication
- Practical support for project execution and learning

---

## 12. Scientific communication and technical storytelling

**Type:** Communication, presentations, reporting  
**Role:** Presenter / manuscript contributor / technical communicator  
**Relevant for:** R&D communication, stakeholder updates, technical documentation, collaboration-facing roles

### Summary

Presented research progress and technical results to professors, collaborators, students, senior researchers, and visiting industry partners.

### Communication examples

- Conference talks and posters on magnetism, spintronics, RuO₂-based systems, magnon transport, magnetoresistance, and Hall effects
- Internal seminars and subgroup updates explaining new results, measurement artifacts, theory–experiment links, and follow-up plans
- Beamtime updates, technical reports, figures, and manuscripts
- Documentation for tools, workflows, and user-facing procedures

### What this shows

- Ability to translate complex measurements into clear messages
- Comfort communicating across different levels of expertise
- Experience preparing publication-quality figures and structured technical explanations
- Ability to identify uncertainty, limitations, and next steps

---

# Technical skill map

## Experimental methods

- Magnetotransport and electrical characterization
- Four-probe, longitudinal, transverse, and Hall measurements
- Angle-dependent magnetoresistance and spin Hall magnetoresistance
- First- and second-harmonic lock-in detection
- Nonlocal magnon transport geometries
- Cryogenic measurements down to approximately 2–3 K
- Magnetic-field, temperature, angle, and frequency sweeps
- Ferromagnetic resonance, spin pumping, and spin Seebeck measurements
- MOKE, XMCD/XMLD-PEEM, MCD-XPS exposure, low-energy muon spectroscopy

## Thin-film growth and fabrication

- Pulsed laser deposition
- DC/RF magnetron sputtering
- Reactive sputtering
- Thermal evaporation
- Chemical/spin coating exposure
- RHEED integration and thin-film process monitoring
- Optical and e-beam lithography
- Ion etching, lift-off, annealing, wire bonding
- Cleanroom workflows and device preparation

## Instrumentation and systems

- High-vacuum and ultra-high-vacuum systems
- Excimer-laser PLD infrastructure
- 4-gun magnetron sputtering system
- Oxygen ion etching capability
- Vacuum suitcase transfer between deposition tools
- Cryostats and superconducting magnets
- Low-noise electronics, lock-in amplifiers, multi-channel wiring
- SOPs, checklists, manuals, and user training material

## Data, software, and analysis

- Python, pandas, NumPy, matplotlib
- HDF5 data structures and metadata workflows
- Batch processing and reproducible plotting
- Feature extraction, fitting, regression, and basic classification
- LabVIEW experiment control and automation
- OriginPro, LaTeX, Inkscape
- SolidWorks and K-layout exposure
- Version-controlled and collaborator-readable analysis workflows

## Collaboration and project execution

- Facility proposal preparation
- Beamtime logistics and quick-look analysis
- Multi-institutional collaboration across Europe, Asia, and the USA
- Sample, metadata, and data exchange
- Tool scheduling and user management
- Mentoring, training, speaker coordination, and journal-club organization

---

# How I work

I like technical problems that require both depth and structure. My approach is usually:

1. **Clarify the question**  
   What exactly needs to be measured, compared, or ruled out?

2. **Build a reliable workflow**  
   What setup, protocol, wiring, automation, calibration, and data structure are needed?

3. **Check the signal carefully**  
   What could be an artifact? What depends on geometry, temperature, field, angle, or device history?

4. **Make the result usable**  
   Can the workflow be repeated? Can the data be understood by collaborators? Can the conclusion be explained clearly?

5. **Support the team around the work**  
   Document procedures, train users, coordinate tasks, and communicate limitations honestly.

---

# What this portfolio shows

Across these projects, I want to show more than a list of academic outputs. The common thread is practical technical ownership:

- Building and operating complex experimental systems
- Automating measurements and improving reliability
- Turning large experimental datasets into interpretable results
- Connecting material systems, devices, instruments, and data
- Coordinating people, tools, samples, and timelines
- Communicating complex physics clearly to different audiences

For a formal publication list, see [Publications](/publications/). For a concise PDF summary, download my [CV](/files/Akashdeep_CV.pdf).
