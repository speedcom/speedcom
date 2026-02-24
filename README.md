<div align="center">

<img src="assets/network_cascade.gif" alt="Automation cascade spreading through a 10,000-firm network" width="100%"/>

<br/>

# Hi, I'm Maciej

**Quantitative finance & complexity economics**

Building agent-based models of AI-driven labor market transitions — where statistical physics meets macroeconomic policy.

</div>

---

## Boom Bust Group

**A quantitative investment firm built by scientists and engineers**

> "We trade global markets through precision, speed, and deep data insights."

---

*(Feel free to visit our website &rarr; [boombustgroup.com](https://www.boombustgroup.com/))*

---

## Complexity Economics Research

[![complexity-econ](https://img.shields.io/badge/GitHub_Org-complexity--econ-181717?logo=github)](https://github.com/complexity-econ)

A stock-flow consistent agent-based model (SFC-ABM) with **10,000 heterogeneous firms** across **6 sectors**, calibrated to the Polish economy (GUS 2024). Five published papers and **40,000+ Monte Carlo simulations** exploring how universal basic income, monetary regimes, and network topology interact to produce **phase transitions in automation adoption**.

<div align="center">

<img src="assets/fig01_phase_diagram.png" alt="Phase diagram: PLN vs EUR adoption heatmaps" width="85%"/>

<sub><b>Phase diagram of AI adoption.</b> Left: PLN regime shows reentrant transition — adoption peaks at BDP ~500 PLN then declines as inflation triggers NBP rate hikes. Right: EUR + SGP constraint confines adoption to a narrow island (BDP 1000–3000, low &sigma;).</sub>

</div>

### Published Papers

| # | Title | Sims | DOI | |
|:-:|-------|-----:|-----|:-:|
| 1 | **The Acceleration Paradox** | 6,300 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18727928.svg)](https://doi.org/10.5281/zenodo.18727928) | [PDF](https://github.com/complexity-econ/paper-01-acceleration-paradox/blob/main/latex/paper_en.pdf) |
| 2 | **PLN vs EUR with SGP Constraint** | 1,260 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18740933.svg)](https://doi.org/10.5281/zenodo.18740933) | [PDF](https://github.com/complexity-econ/paper-02-monetary-regimes/blob/main/latex/paper_en.pdf) |
| 3 | **Empirical CES &sigma; Estimation** | 120 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18743780.svg)](https://doi.org/10.5281/zenodo.18743780) | [PDF](https://github.com/complexity-econ/paper-03-empirical-sigma/blob/main/latex/paper_en.pdf) |
| 4 | **Phase Diagram & Universality** | 18,540 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18751083.svg)](https://doi.org/10.5281/zenodo.18751083) | [PDF](https://github.com/complexity-econ/paper-04-phase-diagram/blob/main/latex/paper_en.pdf) |
| 5 | **Endogenous Technology & Network Dynamics** | 10,080 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18758365.svg)](https://doi.org/10.5281/zenodo.18758365) | [PDF](https://github.com/complexity-econ/paper-05-endogenous/blob/main/latex/paper_en.pdf) |

**Engine**: [`core`](https://github.com/complexity-econ/core) &mdash; reusable Scala 3 SFC-ABM engine

### Key Findings

- **Acceleration paradox** &mdash; moderate UBI *causes* automation rather than responding to it; bimodal adoption at the critical point (Hartigan dip *p* = 1.7 &times; 10<sup>-5</sup>)
- **Monetary sovereignty matters** &mdash; PLN float permits the transition; EUR + Stability & Growth Pact kills it (SGP caps effective UBI at ~10 PLN by month 120)
- **&sigma; calibration doesn't** &mdash; 5&ndash;9&times; change in CES elasticity shifts adoption by only 1.5 pp; monetary regime dominates (&Delta; 6 pp)
- **Topology universality** &mdash; BDP<sub>c</sub> = 500 PLN across all four network topologies (WS, ER, BA, lattice); mean-field critical exponent &gamma; &approx; 1.0
- **Endogenization preserves universality** &mdash; Arthur-style learning + preferential rewiring keep the reentrant shape; BDP<sub>c</sub> shifts by at most 250 PLN

<div align="center">

<img src="assets/animated_bifurcation.gif" alt="Animated bifurcation: PLN reentrant peak vs EUR SGP constraint" width="75%"/>

<sub><b>Bifurcation dynamics.</b> PLN regime (left) exhibits a reentrant peak — adoption rises then falls as fiscal stimulus triggers monetary tightening. EUR regime (right) is capped by Maastricht fiscal rules.</sub>

</div>

---

### Tech Stack

![Scala](https://img.shields.io/badge/Scala_3-DC322F?logo=scala&logoColor=white)
![Python](https://img.shields.io/badge/Python_3-3776AB?logo=python&logoColor=white)
![LaTeX](https://img.shields.io/badge/XeLaTeX-008080?logo=latex&logoColor=white)
![sbt](https://img.shields.io/badge/sbt-1.10-blue)
