---
title: "HIP vs. Stress Relief for DMLS Titanium: What Each One Does"
date: 2026-03-08
summary: "HIP and stress relief are both common post-processing steps for DMLS titanium, but they address different defects and are not interchangeable. This guide explains what each one does, with cycle parameters from a manufacturer datasheet and published papers."
tags: ["HIP", "post-processing", "DMLS", "Ti6Al4V", "aerospace", "fatigue"]
---

DMLS titanium parts carry two kinds of problem that post-processing must address:
residual stress (from layer-by-layer rapid solidification and cooling) and volumetric
defects (lack of fusion, gas-entrapped pores and keyhole pores). Stress relief
and HIP address these separately. Despite the "sintering" in the DMLS name, the
process fully melts the powder.

## Stress Relief: Removing Residual Stress

Residual stress in as-built laser-melted Ti-6Al-4V can be high. A synchrotron diffraction
study of as-built bridge specimens measured subsurface tensile stress maxima of about
600 MPa and 875 MPa, depending on scan speed, and earlier contour-method work found
tensile stresses near the yield stress towards the surfaces and edges of specimens.

Published cycles vary:

- The EOS datasheet for Titanium Ti64 Grade 5 on the EOS M 290 recommends 800°C (±10°C)
  for 120 minutes (±30 minutes) in vacuum, followed by slow cooling under vacuum or argon,
  to relieve stresses and increase ductility.
- The synchrotron study used 650°C for 3 hours under vacuum, which it cites as a common
  stress relief treatment applied before parts are separated from the baseplate. After
  that treatment the near-surface tensile stresses were fully relieved.

Heat treatment of this kind does not eliminate porosity.

## HIP: Closing Internal Porosity

Hot isostatic pressing (HIP) applies heat and gas pressure together to close internal
porosity. Argon is the most widely used pressurizing gas and 100 MPa the most common
pressure. A 2024 study by the University of Texas at El Paso and Quintus Technologies
used 900°C / 100 MPa / 2 hours as its standard HIP cycle for laser powder bed fusion
Ti-6Al-4V, alongside a low temperature, high pressure cycle of 815°C / 190 MPa / 2 hours.

HIP is recommended to improve the fatigue resistance of laser powder bed fusion parts.
It cannot completely remove porosity, but it reduces the defect population and its
average size, which lets HIPed material reach fatigue performance similar to wrought alloys.

There are trade-offs. A NIST paper notes that standard HIP treatment of Ti-6Al-4V
reduces internal porosity but results in decreased strength. In the UTEP study, the
annealed (non-HIP) group had the highest yield strength, ultimate tensile strength and
hardness, while the HIP groups had better ductility. In that study's 4-point bending
fatigue tests on machined specimens, the annealed group outperformed the HIP groups,
and the low temperature, high pressure cycle did best among the HIP cycles. HIP is
not automatically the better choice for every part and load case.

## Standards

ASTM F2924 is the standard specification for additively manufactured Ti-6Al-4V made by
powder bed fusion. ASTM F3301 specifies requirements for thermal post-processing of
powder bed fusion metal parts, including Ti-6Al-4V, and is intended to be referenced by
material and part specifications. Whether stress relief, HIP or both are required for a
given part is set by the specification and the customer contract, so check the current
edition of the applicable standard rather than relying on a rule of thumb.

## Sources

- [EOS: Titanium Ti64 Grade 5 material data sheet](https://www.eos.info/metal-solutions/metal-materials/data-sheets/mds-eos-titanium-ti64-grade-5)
- [Mishurova et al., An Assessment of Subsurface Residual Stress Analysis in SLM Ti-6Al-4V, Materials 2017 (PDF)](https://opus4.kobv.de/opus4-bam/files/39575/materials-10-00348.pdf)
- [Mishurova et al., Understanding the hot isostatic pressing effectiveness of laser powder bed fusion Ti-6Al-4V, Scientific Reports 2023 (PDF)](https://opus4.kobv.de/opus4-bam/files/58770/Mishurova_etall_HIP_Sci_REP.pdf)
- [Ariza et al., The Impact of Different HIP Treatment Cycles on Fatigue Behavior during 4-Point Bending of AM Ti-6Al-4V, Solid Freeform Fabrication Symposium 2024 (PDF)](https://utw10945.utweb.utexas.edu/sites/default/files/2024/57%20The%20Impact%20of%20Different%20HIP%20Treatment%20Cycles%20on.pdf)
- [NIST: Benzing et al., Hot isostatic pressing to achieve isotropic microstructure and retain as-built strength in AM Ti-6Al-4V (abstract)](https://www.nist.gov/node/1582151)
- [ASTM F2924-14(2021) listing](https://store.astm.org/f2924-14r21.html)
- [ASTM F3301-18a listing](https://store.astm.org/f3301-18a.html)
- [Wikipedia: Hot isostatic pressing](https://en.wikipedia.org/wiki/Hot_isostatic_pressing)
- [Wikipedia: Selective laser melting](https://en.wikipedia.org/wiki/Selective_laser_melting)

Fact-checked 2026-11-21
