---
# ═══════════ RESOURCES ═══════════
# Pages live in static/demos/ and static/tutorials/; card images sit next to this file.
title: Resources
type: resources
eyebrow: Build on the research
lead: Interactive demos, course material, virtual labs and notes from the lab.
chips:
- name: Interactive demos
  url: '#demos'
- name: Physical Optics course
  url: '#course'
- name: Virtual labs & build guides
  url: '#labs'
- name: Notes & handbooks
  url: '#notes'
- name: Software & data
  url: '#software'
sections:
- id: demos
  title: Interactive demos
  label: Interactive demos
  columns: 3
  text: 'Explore the optics behind our papers in the browser: drag to rotate, step through the acquisition, change the parameters.'
  items:
  - title: Bessel-beam beating tomography
    subtitle: SRST · PS-OB³ TPFT
    image: bessel-beating-tomography.jpg
    text: How optical beating of two Bessel beams encodes depth in spatial frequency, and how an inverse FFT recovers the depth profile without z-scanning.
    links:
    - name: Open demo
      url: demos/bessel-beating-tomography.html
    - name: Paper (2024)
      url: publication/2024-ps-ob3-tpft/
    - name: Paper (2021)
      url: publication/2021-srs-tomography/
  - title: Bessel light bullets · B²-SRS
    subtitle: Time-of-flight optical sectioning
    image: bessel-light-bullet-b2srs.jpg
    text: Counter-propagating pump and Stokes Bessel light bullets with tunable group velocity meet inside the sample; the delay sets the depth.
    links:
    - name: Open demo
      url: demos/bessel-light-bullet-b2srs.html
    - name: Paper
      url: publication/2024-bessel-light-bullet-srs/
  - title: PHYSIQ-SRS optical path
    subtitle: Physics-paired I/Q detection · in Chinese
    image: physiq-optical-path.jpg
    text: A station-by-station 3D walk through the PHYSIQ-SRS setup, from the laser to dual-phase lock-in detection.
    links:
    - name: Open demo
      url: demos/physiq-optical-path.html
    - name: Paper
      url: publication/2026-physiq-srs/
- id: course
  title: Physical Optics course
  label: Course
  columns: 2
  text: 'An interactive physical-optics series: each episode pairs a 3D scene, a 2D field cross-section and the governing equations, with sliders that drive the simulation. In Chinese.'
  items:
  - title: EP01 · From electromagnetic waves to wavefronts
    subtitle: Wave equation · plane and spherical waves · interference
    image: tut-physical-optics-ep01.jpg
    text: Starts from the wave equation in vacuum and builds up wavefronts and interference patterns step by step.
    links:
    - name: Open
      url: tutorials/physical-optics-ep01.html
  - title: EP02 · Computer-generated holography and structured light
    subtitle: Holography · SLM phase patterns · structured beams
    image: tut-physical-optics-ep02.jpg
    text: From recording intensity on a plate to computing holograms and shaping structured light with phase masks.
    links:
    - name: Open
      url: tutorials/physical-optics-ep02.html
  - title: EP03 · Ultrafast light and spatiotemporal light fields
    subtitle: Pulses · dispersion · space–time coupling
    image: tut-physical-optics-ep03.jpg
    text: A pulse as a coherent sum of frequency components, and what happens when space and time are coupled.
    links:
    - name: Open
      url: tutorials/physical-optics-ep03.html
  - title: EP04 · Nonlinear optics and coherent Raman imaging
    subtitle: Anharmonic oscillator · SHG · CARS / SRS
    image: tut-physical-optics-ep04.jpg
    text: From the anharmonic Lorentz oscillator to second-harmonic generation and coherent Raman scattering microscopy.
    links:
    - name: Open
      url: tutorials/physical-optics-ep04.html
- id: labs
  title: Virtual labs & build guides
  label: Virtual labs
  columns: 3
  text: Interactive instruments to learn how a system is built and aligned, and what each component does. In Chinese.
  items:
  - title: Multimodal microscopy virtual lab
    subtitle: TPF · SHG · SRS on one microscope
    image: tut-multimodal-microscopy-virtual-lab.jpg
    text: Pull components out of the optical path and watch the signal, noise spectrum and reconstructed image respond. Includes guided lessons and a free-exploration mode.
    links:
    - name: Open
      url: tutorials/multimodal-microscopy-virtual-lab.html
  - title: DIY two-photon scanning microscope (3D)
    subtitle: Upright · resonant-galvo scanning · non-descanned detection
    image: tut-diy-two-photon-microscope-3d.jpg
    text: A 3D model of a home-built two-photon microscope with 32 labelled parts, beam paths and a scanning animation.
    links:
    - name: Open
      url: tutorials/diy-two-photon-microscope-3d.html
  - title: 'D-FFOCT: build and alignment from scratch'
    subtitle: Dynamic full-field OCT · Linnik interferometer
    image: dffoct-build-alignment.jpg
    text: A step-by-step 3D guide to building and aligning a dynamic full-field OCT microscope.
    links:
    - name: Open
      url: demos/dffoct-build-alignment.html
  - title: TGV 3D light-field fabrication system
    subtitle: Through-glass vias · programmable axial light fields
    image: tut-tgv-3d-light-field-fabrication.jpg
    text: 'The experimental system and principles: axially programmable needle beams, deposition-driven inverse design and z-periodic light fields.'
    links:
    - name: Open
      url: tutorials/tgv-3d-light-field-fabrication.html
  - title: 'Axicon pair: 3D interactive bench'
    subtitle: Ring and Bessel-beam generation
    image: axicon-pair-3d-lab.jpg
    text: Change cone angles, spacing and misalignment of an axicon pair and see the resulting intensity distribution.
    links:
    - name: Open
      url: demos/axicon-pair-3d-lab.html
- id: notes
  title: Notes & handbooks
  label: Notes
  columns: 2
  text: Reading maps and study notes with interactive figures. In Chinese.
  items:
  - title: Super-resolution imaging handbook
    subtitle: Diffraction limit · SIM · STED · single-molecule localization
    image: tut-super-resolution-imaging-handbook.jpg
    text: An interactive study handbook on fluorescence nanoscopy, with method comparisons, practical tips and self-tests.
    links:
    - name: Open
      url: tutorials/super-resolution-imaging-handbook.html
  - title: Super-resolution frontiers
    subtitle: Frontier dossiers, 2017–2026
    image: tut-super-resolution-frontiers.jpg
    text: Molecular-scale localization, expansion microscopy, live-cell SIM, and single-frame, label-free and computational approaches, with side-by-side comparison and sources.
    links:
    - name: Open
      url: tutorials/super-resolution-frontiers.html
  - title: Optical computing notes
    subtitle: 4f systems · MZI meshes · diffractive networks
    image: tut-optical-computing-notes.jpg
    text: Why compute with light, and how lenses, interferometer meshes, wavelength multiplexing and diffractive networks do it.
    links:
    - name: Open
      url: tutorials/optical-computing-notes.html
  - title: OCT learning map
    subtitle: Optical coherence tomography · 84 chapters
    image: tut-oct-learning-map.jpg
    text: A chapter-by-chapter learning map with progress tracking, following Drexler & Fujimoto, Optical Coherence Tomography (2nd ed., Springer, 2015).
    links:
    - name: Open
      url: tutorials/oct-learning-map.html
- id: software
  title: Software & data
  label: Software & data
  text: Code and datasets released with our publications will be listed here.
  items: []
next:
- title: Publications
  text: The papers these resources belong to.
  url: publication/
- title: Research
  text: The questions behind them.
  url: research/
- title: Join / Collaborate
  text: Ask about using or extending a resource.
  url: contact/
---
