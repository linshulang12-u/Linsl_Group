---
title: Physics-enabled computational imaging
weight: 30
summary: Letting the measurement physics supply the training data — self-supervised restoration at the shot-noise limit.
question: When there is no clean ground truth, can the detection physics itself provide what a network needs to learn?
focus:
  - Physics-paired acquisition (PHYSIQ) — in-phase and quadrature SRS channels with independent shot noise
  - Self-supervised denoising without clean targets or temporal averaging
  - High-speed volumetric imaging and 3D tracking in live cells
  - Reconstruction for encoded acquisitions (optical beating, Fourier ptychography)
image_caption: 'PHYSIQ: physics-paired I/Q detection and self-supervised denoising for SRS.'
demos:
  - {name: 'PHYSIQ-SRS optical path', url: demos/physiq-optical-path.html}
---

High-speed volumetric SRS imaging is limited by the trade-off between imaging
speed and signal-to-noise ratio. PHYSIQ-SRS acquires two co-registered
measurements — in-phase and quadrature — that carry matching Raman contrast but
independent shot noise. That pair is exactly what a Noise2Noise-style network
needs, so restoration can be trained without clean targets.

The published study reports approximately 12.5 dB SNR improvement and
label-free three-dimensional tracking of lipid droplets in live cells.
