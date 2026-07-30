# Cools Thin-Film III-V on SiC Platform

[한국어](README_KR.md) | [中文](README_ZH.md) | [Patent Portfolio](PATENT_PORTFOLIO.md) | [Public Notice](PUBLIC_NOTICE.md)

## III-V for photons. SiC for everything underneath.

**Use indium-phosphide-based III-V material only where optical functionality is required. Let silicon carbide carry the heat, stress, mechanics, alignment, and package.**

Cools proposes a general optical-semiconductor platform in which an indium-phosphide-based III-V optically functional thin-film layer is transferred and bonded onto a silicon-carbide-based support layer.

The expensive III-V crystal is no longer required to remain as the full mechanical substrate. It becomes a thin functional optical layer, while the SiC-based platform provides thermal spreading, mechanical support, coefficient-of-thermal-expansion matching, package rigidity, and—where required—optical alignment and vertical electrical/optical integration.

---

## 1. The conventional constraint

A conventional InP optical device uses a bulk InP wafer as all of the following at once:

- the epitaxial growth template,
- the optically active material platform,
- the mechanical handle,
- and the heat-conduction path.

This architecture wastes expensive III-V material and preserves the limitations of bulk InP:

- relatively low thermal conductivity,
- mechanical brittleness,
- limited large-diameter scalability,
- high material cost,
- and strategic-material supply-chain exposure.

Transferring III-V layers onto silicon does not fully solve the problem. Silicon and InP have a larger thermal-expansion mismatch than SiC and InP, and silicon does not provide the same thermal pathway as a high-conductivity SiC platform.

---

## 2. Cools architecture

```text
Optical device / electrode / waveguide
──────────────────────────────────────
InP-based III-V functional thin film
(InP / InGaAs / InGaAsP / InAlGaAs / MQW / APD / SPAD)
──────────────────────────────────────
Direct or ultra-thin bonding interface
──────────────────────────────────────
SiC-based thermal and mechanical platform
(single-crystal SiC / thin-film SiC / poly-SiC / RBSC)
```

The platform separates material functions:

| Layer | Primary function |
|---|---|
| InP-based III-V thin film | Light generation, modulation, detection, waveguiding, quantum-well functionality |
| Bonding interface | Low-temperature joining, low thermal resistance, optional electrical/interface control |
| SiC-based support | Heat spreading, mechanical support, CTE matching, package base, alignment reference, optional optical/electrical vias |

The InP-based layer may include InP, InGaAs, InGaAsP, InAlGaAs, multiple-quantum-well stacks, laser stacks, avalanche photodiodes, single-photon avalanche diodes, or combinations thereof.

---

## 3. Why SiC under InP

### Thermal extraction

InP has a thermal conductivity of approximately 68 W/m·K, while high-quality single-crystal SiC can reach approximately 490 W/m·K. The SiC support therefore removes heat from III-V lasers, modulators, and detectors through a short, low-resistance path.

### Thermal-expansion matching

The thermal-expansion coefficients of SiC and InP are close—approximately 4.0 and 4.6 ppm/K, respectively. This substantially reduces residual stress during bonding, cooling, and thermal cycling compared with an InP-on-Si combination.

### Mechanical and package functions

The SiC support may serve not only as a wafer handle, but also as:

- a rigid package base,
- a heat spreader,
- an optical-alignment reference plane,
- a vertical optical-interconnect platform,
- and a host for through-substrate electrical or optical vias.

---

## 4. Transfer instead of consuming the bulk wafer

A representative manufacturing route is:

```text
1. Prepare an InP-based III-V donor or epitaxial stack
2. Form a buried separation plane by H/He implantation
3. Bond the donor stack to the SiC-based support
4. Split along the separation plane
5. Finish the transferred III-V thin film
6. Form or complete the optical device
7. Reclaim and reuse the donor
```

Only a sub-micrometre-to-few-micrometre functional layer is consumed per cycle. The donor can be polished, restored, and reused repeatedly.

The disclosed architecture targets a reduction of InP raw-material consumption to approximately **1/100 to 1/300** of a bulk-substrate approach, depending on transferred thickness, donor recovery loss, and reuse count.

---

## 5. Bonding interface options

The platform is not limited to one bonding chemistry. The interface may include:

- hydrophilic direct bonding,
- plasma-activated bonding,
- an oxide or nitride intermediate layer,
- a metal bonding interface,
- benzocyclobutene bonding,
- or an amine-containing molecular interface such as a PEI/PEIE-derived layer.

The interface is designed to remain thin so that the thermal advantage of the SiC support is not lost in a thick adhesive or solder layer.

---

## 6. SiC support variants

The support can be selected according to optical, thermal, cost, and package requirements.

### Single-crystal SiC

Best suited to high thermal conductivity, crystalline quality, and rear-side optical access.

### Thin-film SiC on another carrier

Useful for monolithic integration with CMOS readout circuits, vertical optical interconnects, or composite optical stacks.

### Polycrystalline SiC

Provides a high-stiffness and thermally conductive handle without requiring a full single-crystal wafer.

### Reaction-bonded SiC (RBSC)

Provides a large-area, low-cost, high-rigidity thermal handle. Because RBSC includes residual silicon, pores, and multiple phases, it is treated primarily as a thermal/mechanical platform rather than a uniformly transparent rear-illumination medium. Optical access can instead be provided through an opening, a local single-crystal SiC window, an optical via, side illumination, or front illumination.

---

## 7. Optional self-aligned optical post-processing

Optical treatment is an optional extension—not a required limitation of the core platform.

Light may enter from the front, rear, side, an optical via, or a transparent window. A selected absorption region within the transferred III-V layer can absorb the incident light more strongly than the surrounding material and create a localized thermal peak.

Possible targets include:

- multiple-quantum-well regions,
- doped regions,
- free-carrier absorption regions,
- implantation-damaged regions,
- defect-level regions,
- buried metal absorbers,
- interface reaction layers,
- and dedicated optical absorber layers.

Potential uses include defect recovery, dopant activation, wavelength trimming, and local quantum-well intermixing while limiting the heat-affected zone.

---

## 8. Application platform

### Automotive LiDAR

A 1,500–1,600 nm III-V laser and detector can be integrated on the same SiC thermal platform. The architecture supports time-of-flight, frequency-modulated continuous-wave, coherent detection, and optical-phased-array implementations.

### Co-packaged optics

The SiC platform can serve as a thermal handle, optical alignment reference, rigid optical-engine base, and low-expansion package platform adjacent to a switch ASIC.

### SWIR imaging

An InGaAs/InP detector stack can be transferred through a thin SiC intermediate layer onto a silicon CMOS readout integrated circuit, enabling fine-pixel monolithic or near-monolithic SWIR arrays.

### Quantum photonics and QKD

III-V single-photon sources, single-photon avalanche detectors, and optional graphene functions can be integrated on a thermally stable SiC platform.

### Space multi-junction photovoltaics

A transferred III-V multi-junction stack may be supported by SiC instead of a thick germanium substrate. Graphene, an ultrathin metal mesh, or another transparent conductive layer may replace or reduce dependence on indium-tin oxide.

---

## 9. What is fundamentally different

This is not merely an InP device mounted on a conventional submount.

The core transformation is:

```text
Bulk III-V substrate as structure
                ↓
Reusable III-V donor as source of functional films
                +
SiC as the permanent thermal/mechanical/package platform
```

The platform therefore changes both the device stack and the material-consumption model.

---

## 10. Relationship to other Cools platforms

This repository covers the **active III-V optical-semiconductor layer on SiC**.

It can be combined with:

- [Cools Thermally Active Photonic Substrate](https://github.com/jhcho9494/Cools_Thermally_Active_Photonic_Substrate) — alumina-based buried insulators and thermally active handlers,
- [Cools CPO Zero Thermal Budget Bonding](https://github.com/jhcho9494/Cools_CPO_Zero_Thermal_Budget_Bonding) — low-thermal-budget heterogeneous integration,
- [Cools Transmissive Self-Aligned Annealing](https://github.com/jhcho9494/Cools_Transmissive_Self_Aligned_Annealing) — localized optical processing through a low-absorption path,
- and [Cools Package-Substrate-Less SystemBoard](https://github.com/jhcho9494/Cools_Package_Substrate_Less_SystemBoard) — transferred fine-line routing and package-substrate elimination.

A combined stack may integrate:

```text
InP-based active optical layer
+ alumina-based optical/thermal BOX
+ SiC/RBSC thermally active handler
+ transferred electrical/optical redistribution overlay
```

---

## 11. Development and collaboration scope

Cools is open to technical evaluation and joint development in:

- InP donor preparation and reuse,
- ion-cut and alternative thin-film separation,
- low-temperature III-V/SiC bonding,
- CTE and interface-reliability evaluation,
- LiDAR and CPO optical-engine integration,
- SWIR detector-to-CMOS integration,
- quantum-photonic integration,
- and space photovoltaic stacks.

This repository provides a public architectural disclosure. Detailed recipes, interface-treatment conditions, donor-recovery parameters, device layouts, and qualification data remain subject to separate technical and intellectual-property arrangements.

---

## Inventor and contact

**Jinhyun Cho**  
Cools  
Republic of Korea

For joint development, licensing discussion, or technical evaluation, please contact Cools through the repository owner profile.

---

© 2026 Cools. Patent rights reserved. See [PUBLIC_NOTICE.md](PUBLIC_NOTICE.md).