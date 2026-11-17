---
# ═══════════ RESOURCES ═══════════
# Each section has a list of items. Remove `draft: true` once an item is real.
title: Resources
type: resources            # selects layouts/resources/single.html — do not change
eyebrow: 'Build on the research'
lead: 'Software, data and teaching material released by the lab.'
chips:
  - {name: Interactive demos, url: '#demos'}
  - {name: Software & Tools, url: '#software'}
  - {name: Data & Benchmarks, url: '#data'}
  - {name: Teaching & Tutorials, url: '#teaching'}

sections:
  - id: demos
    title: Interactive demos
    columns: 3
    text: 'Explore the optics behind our papers in the browser — drag to rotate, step through the acquisition, change the parameters.'
    items:
      - title: Bessel-beam beating tomography
        subtitle: 'SRST · PS-OB³ TPFT'
        image: bessel-beating-tomography.jpg
        text: 'How optical beating of two Bessel beams encodes depth in spatial frequency, and how an inverse FFT recovers the depth profile without z-scanning.'
        links:
          - {name: Open demo, url: demos/bessel-beating-tomography.html}
          - {name: 'Paper (2024)', url: publication/2024-ps-ob3-tpft/}
          - {name: 'Paper (2021)', url: publication/2021-srs-tomography/}
      - title: Bessel light bullets · B²-SRS
        subtitle: 'Time-of-flight optical sectioning'
        image: bessel-light-bullet-b2srs.jpg
        text: 'Counter-propagating pump and Stokes Bessel light bullets with tunable group velocity meet inside the sample; the delay sets the depth.'
        links:
          - {name: Open demo, url: demos/bessel-light-bullet-b2srs.html}
          - {name: Paper, url: publication/2024-bessel-light-bullet-srs/}
      - title: PHYSIQ-SRS optical path
        subtitle: 'Physics-paired I/Q detection · interface in Chinese'
        image: physiq-optical-path.jpg
        text: 'A station-by-station 3D walk through the PHYSIQ-SRS setup, from the laser to dual-phase lock-in detection.'
        links:
          - {name: Open demo, url: demos/physiq-optical-path.html}
          - {name: Paper, url: publication/2026-physiq-srs/}
  - id: software
    title: Software & Tools
    text: 'Code that accompanies our papers and tools we use in the lab.'
    items:
      - title: Tool or code name
        subtitle: One-line description
        text: 'What it does, which paper it belongs to, and what it needs to run.'
        draft: true
        links:
          - {name: Code, url: 'https://github.com/'}
  - id: data
    title: Data & Benchmarks
    text: 'Datasets released with our publications.'
    items:
      - title: Dataset name
        subtitle: One-line description
        text: 'What was measured, format and size, and how to cite it.'
        draft: true
        links:
          - {name: Download, url: 'https://zenodo.org/'}
  - id: teaching
    title: Teaching & Tutorials
    text: 'Build guides and interactive benches for learning optical alignment.'
    items:
      - title: 'D-FFOCT: build and alignment from scratch'
        subtitle: 'Dynamic full-field OCT · Linnik interferometer · in Chinese'
        image: dffoct-build-alignment.jpg
        text: 'A step-by-step 3D guide to building and aligning a dynamic full-field OCT microscope.'
        links:
          - {name: Open tutorial, url: demos/dffoct-build-alignment.html}
      - title: 'Axicon pair: 3D interactive bench'
        subtitle: 'Ring and Bessel-beam generation · in Chinese'
        image: axicon-pair-3d-lab.jpg
        text: 'Change cone angles, spacing and misalignment of an axicon pair and see the resulting intensity distribution.'
        links:
          - {name: Open tutorial, url: demos/axicon-pair-3d-lab.html}

next:
  - {title: Publications, text: 'The papers these resources belong to.', url: publication/}
  - {title: Research, text: 'The questions behind them.', url: research/}
  - {title: Join / Collaborate, text: 'Ask about using or extending a resource.', url: contact/}
---
