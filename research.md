---
layout: single
title: Research Interests
permalink: /research/
classes_: wide
toc: false
toc_sticky: true
toc_icon: scroll
author_profile: true
---

## Two-dimensional moiré materials and exotic electronic structure

When two monolayers of crystalline patterns are stacked with a small misalignment, their interference creates a moir´e superlattice with long wave- length. This allows the long-range Coulomb interaction to dominate when a dilute gas of carriers is doped into the bilayer. I use computational algorithms, such as Hartree-Fock (HF), density functional theory (DFT), quantum Monte Carlo (QMC) to explore and predict the properties of these exotic electronic phases.

<!-- honeycomb moire -->
<details>
<summary>
Ferromagnetic semimetal and charge-density wave phases of interacting electrons in a honeycomb moiré potential
</summary>
  
  <div class="notice--info"><p>
<b>Yubo Yang</b>, Miguel A. Morales, Shiwei Zhang<br /><br />

The exploration of quantum phases in moir´e systems has drawn intense experimental and theo-
retical efforts. The realization of honeycomb symmetry has been a recent focus. The combination of
strong interaction and honeycomb symmetry can lead to exotic electronic states such as fractional
Chern insulator, unconventional superconductor, and quantum spin liquid. Accurate computations
in such systems, with reliable treatment of strong long-ranged Coulomb interaction and approaching
the large system sizes to extract thermodynamic phases, are mostly missing. We study the two-
dimensional electron gas on a honeycomb moir´e lattice at quarter filling, using fixed-phase diffusion
Monte Carlo. The ground state phases of this important model are determined in the parameter
regime relevant to current experiments. With increasing moir´e potential, the systems transitions
from a paramagnetic metal to an itinerant ferromagnetic semimetal and then a charge-density-wave
insulator.
</p></div>
</details>

[arXiv:2406.01715](https://arxiv.org/abs/2406.01715){: .btn .btn--success}
<img src="{{ "/assets/research/arxiv-2406-01715-fig1-phases.png" | absolute_url }}" style="width:20em" class="align-center"/>

<!-- 2DEG intermediate phase -->
<details>
<summary>
Observation of an electronic microemulsion phase emerging from a quantum crystal-to-liquid transition
</summary>
  
  <div class="notice--info"><p>
Jiho Sung, Jue Wang, Ilya Esterlis, Pavel A. Volkov, Giovanni Scuri, You Zhou, Elise Brutschea, Takashi Taniguchi, Kenji Watanabe, <b>Yubo Yang</b>, Miguel A. Morales, Shiwei Zhang, Andrew J. Millis, Mikhail D. Lukin, Philip Kim, Eugene Demler, Hongkun Park<br /><br />

Strongly interacting electronic systems possess rich phase diagrams resulting from the competition between different quantum ground states. A general mechanism that relieves this frustration is the emergence of microemulsion phases, where regions of different phase self-organize across multiple length scales. The experimental characterization of these phases often poses significant challenges, as the long-range Coulomb interaction microscopically mingles the competing states. Here, we use cryogenic reflectance and magneto-optical spectroscopy to observe the signatures of the mixed state between an electronic Wigner crystal and an electron liquid in a MoSe2 monolayer. We find that the transit into this 'microemulsion' state is marked by anomalies in exciton reflectance, spin susceptibility, and Umklapp scattering, establishing it as a distinct phase of electronic matter. Our study of the two-dimensional electronic microemulsion phase elucidates the physics of novel correlated electron states with strong Coulomb interactions.
</p></div>
</details>

[arXiv:2311.18069](https://arxiv.org/abs/2311.18069){: .btn .btn--success}
<img src="{{ "/assets/research/arxiv-2311-18069-fig4.png" | absolute_url }}" style="width:20em" class="align-center"/>

<!-- triangular moire -->
<details>
<summary>
Metal-insulator transition in transition metal dichalcogenide heterobilayer: accurate treatment of interaction
</summary>
  
  <div class="notice--info"><p>
<b>Yubo Yang</b>, Miguel A. Morales, Shiwei Zhang<br /><br />

Transition metal dichalcogenide superlattices provide an exciting new platform for exploring and understanding a variety of phases of matter. The moiré continuum Hamiltonian, of two-dimensional jellium in a modulating potential, provides a fundamental model for such systems. Accurate computations with this model are essential for interpreting experimental observations and making predictions for future explorations. In this work, we combine two complementary quantum Monte Carlo (QMC) methods, phaseless auxiliary field quantum Monte Carlo and fixed-phase diffusion Monte Carlo, to study the ground state of this Hamiltonian. We observe a metal-insulator transition between a paramagnetic and a 120∘ Néel ordered state as the moiré potential depth and the interaction strength are varied. We find significant differences from existing results by Hartree-Fock and exact diagonalization studies. In addition, we benchmark density-functional theory, and suggest an optimal hybrid functional which best approximates our QMC results.
</p></div>
</details>

[arXiv:2306.14954](https://arxiv.org/abs/2306.14954){: .btn .btn--success}
<img src="{{ "/assets/research/arxiv-2306-14954-fig1.png" | absolute_url }}" style="width:20em" class="align-center"/>

## Quantum Monte Carlo (QMC) and "Neural Quantum States" (NQS)

The wavefunction of a correlated many-body system is a map from the high-dimensional configurations space of all N quantum particles to a complex-valued "wavefunction amplitute". The complexity and high-dimensional nature of this wavefunction precludes simple analytical treatment, typically built on a non-interacting approximation.
Quantum Monte Carlo (QMC) is a computational method that efficiently sample the high-dimensional space to directly work with accurate wavefunctions to compute properties.


<!-- 2DEG NSCL -->
<details>
<summary>
Ground state phases of the two-dimension electron gas with a unified variational approach
</summary>
  
  <div class="notice--info"><p>
Conor Smith, Yixiao Chen, Ryan Levy, <b>Yubo Yang</b>, Miguel A. Morales, Shiwei Zhang
<br/><br/>
The two-dimensional electron gas (2DEG) is a fundamental model, which is drawing increasing interest because of recent advances in experimental and theoretical studies of 2D materials. Current understanding of the ground state of the 2DEG relies on quantum Monte Carlo calculations, based on variational comparisons of different ansatze for different phases. We use a single variational ansatz, a general backflow-type wave function using a message-passing neural quantum state architecture, for a unified description across the entire density range. The variational optimization consistently leads to lower ground-state energies than previous best results. Transition into a Wigner crystal (WC) phase occurs automatically at rs = 37 +/- 1, a density lower than currently believed. Between the liquid and WC phases, the same ansatz and variational search strongly suggest the existence of intermediate states in a broad range of densities, with enhanced short-range nematic spin correlations.
</p></div>
</details>

[arXiv:2405.19397](https://arxiv.org/abs/2405.19397){: .btn .btn--success}
<img src="{{ "/assets/research/arxiv-2405-19397-fig23.png" | absolute_url }}" style="width:25em" class="align-center"/>

## Machine learning interatomic potential for high-pressure hydrogen

<!-- nequip -->
<details>
<summary>
The liquid-liquid phase transition of hydrogen and its critical point: Analysis from ab initio simulation and a machine-learned potential
</summary>

  <div class="notice--info"><p>
Mathieu Istas, Scott Jensen, <b>Yubo Yang</b>, Markus Holzmann, Carlo Pierleoni, David M. Ceperley
<br/><br/>
We simulate high-pressure hydrogen in its liquid phase close to molecular dissociation using a machine-learned interatomic potential. The model is trained with density functional theory (DFT) forces and energies, with the Perdew-Burke-Ernzerhof (PBE) exchange-correlation functional. We show that an accurate NequIP model, an E(3)-equivariant neural network potential, accurately reproduces the phase transition present in PBE. Moreover, the computational efficiency of this model allows for substantially longer molecular dynamics trajectories, enabling us to perform a finite-size scaling (FSS) analysis to distinguish between a crossover and a true first-order phase transition. We locate the critical point of this transition, the liquid-liquid phase transition (LLPT), at 1200-1300 K and 155-160 GPa, a temperature lower than most previous estimates and close to the melting transition.
</p></div>
</details>

[arXiv:2412.14953](https://arxiv.org/abs/2412.14953){: .btn .btn--success}
<img src="{{ "/assets/research/arxiv-2412-14953-fig1.png" | absolute_url }}" style="width:25em" class="align-center"/>

<!-- mace -->
<details>
<summary>
High temperature melting of dense molecular hydrogen from machine-learning interatomic potentials trained on quantum Monte Carlo
</summary>

  <div class="notice--info"><p>
Shubhang Goswami, Scott Jensen, <b>Yubo Yang</b>, Markus Holzmann, Carlo Pierleoni, David M. Ceperley
<br/><br/>
We present results and discuss methods for computing the melting temperature of dense molecular hydrogen using a machine learned model trained on quantum Monte Carlo data. In this newly trained model, we emphasize the importance of accurate total energies in the training. We integrate a two phase method for estimating the melting temperature with estimates from the Clausius-Clapeyron relation to provide a more accurate melting curve from the model. We make detailed predictions of the melting temperature, solid and liquid volumes, latent heat and internal energy from 50 GPa to 180 GPa for both classical hydrogen and quantum hydrogen. At pressures of roughly 173 GPa and 1635K, we observe molecular dissociation in the liquid phase. We compare with previous simulations and experimental measurements.
</p></div>
</details>

[arXiv:2411.15665](https://arxiv.org/abs/2411.15665){: .btn .btn--success}
<img src="{{ "/assets/research/arxiv-2411-15665-fig7.png" | absolute_url }}" style="width:25em" class="align-center"/>
