---
title: "Polymer Composites 3D Printing for Aerospace: Carbon Fiber Blends and High-Performance Material Selection"
date: 2026-07-20T06:23:11-06:00
draft: false
description: "A technical guide to polymer composites 3D printing for aerospace carbon fiber applications, covering PEEK, PEKK, and composite AM platforms."
keywords: ["polymer composites 3D printing aerospace carbon fiber", "PEEK PEKK additive manufacturing", "continuous fiber reinforced thermoplastics aerospace"]
---
Aerospace parts ask a lot of a polymer: low density, strength, heat resistance and tolerance of aggressive fluids, all inside a certification framework. **Polymer composites 3D printing for aerospace carbon fiber** applications draws on a small group of high-temperature thermoplastics, on fiber reinforcement in short and continuous forms, and increasingly on printed tooling for conventional composite layup.

This piece covers the main material families, how fiber is introduced, and one recent platform launch.

---

## The Thermoplastic Families

Printing by extrusion needs a feedstock that can be melted and resolidified, which is what thermoplastics do. The families most relevant to aerospace are:

- **PAEK (polyaryletherketone)**: the umbrella class, which includes PEEK and PEKK
- **PEEK (polyether ether ketone)**: melts at about 343°C, with some grades having a useful operating temperature of up to 250°C. It keeps its mechanical and chemical resistance properties at high temperature and can be printed from filament by fused filament fabrication
- **PEKK (polyetherketoneketone)**: a semi-crystalline PAEK with a glass transition temperature of 162°C, noted for resistance to heat, chemicals and mechanical load. Hexcel (formerly Oxford Performance Materials) 3D prints PEKK parts, including components for Boeing's CST-100 Starliner
- **PEI (polyetherimide, sold as Ultem)**: similar in character to PEEK but cheaper, with lower impact strength and a tighter temperature range. Its glass transition temperature is 217°C

---

## Short Fiber vs. Continuous Fiber

Fused filament fabrication can use composite materials with a polymer matrix and short or long fibers. The two routes are visible in one product line. Markforged's Onyx, introduced in 2016, is a nylon filament filled with micro carbon fiber. The same company's Mark One, shown in 2014, was the first printer able to print continuous carbon fiber. It uses two nozzles: the primary nozzle lays down the base material that forms shells and infill, and a secondary nozzle deposits a reinforced filament with a core of continuous high-strength fibers, which can be oriented within the print plane.

In extrusion printing the bond between layers depends on print temperature and other process settings, so layer adhesion has to be treated as a design variable and not assumed from a datasheet.

---

## Massivit RapidWings: Printed Tooling for Composite Parts

Massivit took a different route: print the tool, then make the composite part conventionally. The company's Massivit 10000, launched in May 2022, was developed to make molds for composite end parts. It prints an outer shell and intermittently fills it with a thermoset epoxy casting material, forming an isotropic mold. The mold is then immersed in water so the shell crumbles away. Massivit says the machine produces industrial molds, plugs, tools, jigs and fixtures in a matter of days instead of weeks.

In June 2026 Massivit launched RapidWings, which it describes as a turnkey composite manufacturing platform built on its Cast-In-Motion (CIM) technology and aimed at defense and aerospace customers. RapidWings is a service network, not a single machine: regional partnerships and joint manufacturing alliances with certified Tier-2 composite manufacturers, delivering on-demand tooling and structural parts. The first alliance is with Comparts, an Israeli composites company, and the platform is operational in Israel. Massivit lists service centers in Barcelona, Spain and Portland, Oregon.

The company claims that composite tooling lead times are compressed into a matter of days and that partners have seen up to 70% cost savings against conventional metal and machinable-board tooling. These figures come from Massivit and were not independently measured in the coverage reviewed.

Massivit's earlier printers use Gel Dispensing Printing (GDP), in which an acrylic-based gel is deposited and cured into solid layers under ultraviolet light. The Massivit 5000 is the company's flagship GDP machine.

---

## Material Selection for Aerospace Parts

### 1. Thermal Environment
Compare the continuous operating temperature of the part with the material, not just peak excursions. PEEK grades reach up to 250°C; PEI has a tighter range at lower cost.

### 2. Chemical Resistance
PEEK is broadly resistant but is attacked by halogens and strong acids. PEI has good chemical resistance overall but is prone to stress cracking in chlorinated solvents.

### 3. Cabin Flammability Rules
In the United States, 14 CFR 25.853 ("Compartment interiors") requires materials in compartments occupied by crew or passengers to meet the flammability test criteria in Appendix F of Part 25, with additional tests for items such as ceiling and wall panels on airplanes with 20 or more passengers. Stratasys markets ULTEM 9085, a PEI resin, as flame retardant and meeting multiple aerospace standards for flame, smoke and toxicity, and as qualified for flight parts when printed on its F900 system in line with published NCAMP allowables.

### 4. Process and Property Together
The printed part's properties depend on the process as well as the resin. Design to the process, not the datasheet alone.

---

## Where Composite AM Fits

The verifiable picture is narrower than the marketing. High-temperature thermoplastics such as PEEK, PEKK and PEI are printable and in aerospace use, continuous carbon fiber can be placed by a printer, and printed tooling is being sold as a way to shorten composite lead times. Material selection remains the gate: temperature range, chemical exposure and flammability rules decide which resin is even eligible before printability is considered.

## Sources

- [Polyether ether ketone (Wikipedia)](https://en.wikipedia.org/wiki/Polyether_ether_ketone)
- [Polyetherketoneketone (Wikipedia)](https://en.wikipedia.org/wiki/Polyetherketoneketone)
- [Polyetherimide (Wikipedia)](https://en.wikipedia.org/wiki/Polyetherimide)
- [Fused filament fabrication (Wikipedia)](https://en.wikipedia.org/wiki/Fused_filament_fabrication)
- [Markforged (Wikipedia)](https://en.wikipedia.org/wiki/Markforged)
- [Massivit (Wikipedia)](https://en.wikipedia.org/wiki/Massivit)
- [Massivit: company site](https://www.massivit3d.com/)
- [Digital Engineering 24/7: Massivit Launches RapidWings Manufacturing Platform](https://www.digitalengineering247.com/article/massivit-launches-rapidwings-manufacturing-platform/Additive-Manufacturing)
- [TCT Magazine: Massivit targets defence with RapidWings composite manufacturing platform](https://www.tctmagazine.com/massivit-targets-defence-with-rapidwings-composite-manufacturing-platform/)
- [14 CFR 25.853 Compartment interiors (Cornell LII)](https://www.law.cornell.edu/cfr/text/14/25.853)
- [Stratasys: ULTEM 9085 resin](https://www.stratasys.com/en/materials/materials-catalog/fdm-materials/ultem-9085/)

Fact-checked 2026-11-21
