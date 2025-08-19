# Pareto Cube (Pareto³)
A Recursive Methodology for Strategic Analysis

![alt text](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)

![alt text](https://zenodo.org/badge/DOI/10.5281/zenodo.16899115.svg)

![alt text](https://img.shields.io/badge/Arweave-Permanent%20Archive-green.svg)

![alt text](https://img.shields.io/badge/SSRN-View%20Preprint-blue.svg)

"Don't look for more answers. Look for the better question." — Adrian (Adi) STAN

"By repeating 'why' five times, the nature of the problem, as well as its solution, becomes clear." — Taiichi Ohno, Toyota Motor Corporation

Abstract
This document introduces the Pareto Cube (Pareto³), a "cascade" methodology for solving complex problems, which integrates the Pareto Principle (80/20) with the "5 Whys" root cause analysis technique. The methodology recursively applies the Pareto principle to progressively distill the essential causes: from the Pareto Square (Pareto²), where ~4% of causes generate ~64% of the effects, to the Pareto Cube (Pareto³), where under 1% of causes can explain the majority of the impact (>51%). Two operating modes are presented: Strategic ("Light"), optimized for speed, and Systemic ("Complex"), optimized for deep understanding.

The Core Idea: From the Vital Few to the Actionable Core
Pareto³ is a structured thinking architecture that recursively applies the 80/20 rule to cut through complexity and identify the singular point of maximum leverage.
Pareto¹ (The Principle): 20% of causes generate ~80% of effects.
Pareto² (The Square): Within that 20%, another 80/20 rule applies. This means ~4% of the initial causes generate ~64% of the total effects. These are the strategic levers.
Pareto³ (The Cube): Applying the principle one last time reveals the core. ~0.8% of the initial causes generate ~51% of the total effects. This is the actionable core—the single most important point to address for maximum impact.


Mermaid:
<code>
graph TD
A@{ shape: "rounded", label: "Complete Problem: 100% of Causes" } -->|Pareto¹| B(Vital Few: 20% of Causes);
B("Vital Few: 20% of Causes") -->|Pareto²| C(Strategic Levers: 4% of Causes);
C("Strategic Levers: 4% of Causes") -->|Pareto³| D("Actionable Core: ~0.8% of Causes");
style D fill:#c9ffc9,stroke:#2a7e2a,stroke-width:4px
style A fill:#FFFFFF,stroke:#FF3131,stroke-width:4px
</code>

Operating Modes
The methodology can be used in two distinct ways:

Mode 1: Strategic ("Light")
Goal: Speed and direct action.
Process: Quickly cascades through Pareto¹, ², and ³ to find the single Actionable Core (~0.8%), then applies a single "5 Whys" analysis to find its root cause. Ideal for urgent, well-defined problems.

Mode 2: Systemic ("Complex")
Goal: Deep understanding and creating a causality map.
Process: Uses an adaptive mechanism that adjusts the number of "Whys?" at each Pareto step, based on the problem's complexity and the concentration of causes. Ideal for complex, systemic problems with non-obvious causes.

How to Use with an AI

This methodology is designed to be used with advanced AI systems. The process is simple:
Download the appropriate prompt file:
For fast, direct problem-solving: Strategic Mode Prompt
For in-depth, systemic analysis: Systemic Mode Prompt
Upload the .md file into your AI platform of choice.
Formulate your problem clearly.
Specify the operating mode at the end of your prompt if you wish to use the Systemic mode by adding [systemic analysis]. The Strategic mode is the default.

Invitation to Contribute & Community
Pareto³ is an open-source thinking architecture. It is offered to the world not as a final answer, but as a better question and a tool to build clarity.
You are invited to test, validate, and refine this methodology.
For general feedback, ideas, and sharing case studies, please join the conversation on our Discussions page.
To report issues with the documents or suggest specific improvements, please open an Issue.

How to Cite this Work
If you use this methodology in your research, please cite it as follows:
STAN, Adrian (Adi). (2025). Pareto Cube (Pareto³): A Recursive Methodology for Strategic Analysis (Version 1.1). Zenodo. https://doi.org/10.5281/zenodo.16899115

BibTeX:
<code>
@software{stan_2025_16899115,
  author       = {STAN, Adrian (Adi)},
  title        = {{Pareto Cube (Pareto³): A Recursive Methodology for Strategic Analysis}},
  month        = aug,
  year         = 2025,
  publisher    = {Zenodo},
  version      = {1.1},
  doi          = {10.5281/zenodo.16899115},
  url          = {https://doi.org/10.5281/zenodo.16899115}
}
</code>

License
This work is licensed under a Creative Commons Attribution 4.0 International License.

