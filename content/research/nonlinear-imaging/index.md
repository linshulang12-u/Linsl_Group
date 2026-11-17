---
title: Label-free volumetric nonlinear imaging
weight: 20
summary: SRS and two-photon tomography that reaches deeper and resolves finer, without mechanical z-scanning.
question: Can we read out 3D chemistry deep in scattering tissue without labels and without moving anything?
focus:
  - Stimulated Raman scattering (SRS) tomography with Bessel-beam optical beating
  - Time-of-flight resolved SRS with counter-propagating Bessel light bullets (B²-SRS)
  - Super-resolution two-photon fluorescence tomography (PS-OB³ TPFT)
  - Super-resolution coherent Raman imaging (SRS, CARS)
  - Applications to cells and tissue, e.g. lipid-droplet dynamics and tumour metabolism
image_caption: 'Epi-detected PS-OB³ two-photon fluorescence tomography (from Lin *et al.*, *Laser Photonics Rev.* 2024, CC BY-NC-ND 4.0).'
demos:
  - {name: 'Beating tomography', url: demos/bessel-beating-tomography.html}
---

Bessel beams penetrate scattering tissue better than a tightly focused Gaussian
beam, but a plain Bessel scan only gives a projection: depth is lost. We recover
it optically. Depth can be encoded in **spatial frequency** (optical beating
tomography, recovered by an inverse FFT) or in **time of flight**
(counter-propagating light bullets).

B²-SRS and PS-OB³ two-photon tomography each reported more than a twofold gain in imaging
depth in porcine brain tissue compared with conventional point-scanning, and,
for two-photon tomography, about 1.3× lateral and 2× axial resolution
improvement.
