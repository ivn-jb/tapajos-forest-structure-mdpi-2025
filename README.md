# Data-Driven Analysis of Tree Structure Variation Across Forest Types in Tapajós National Forest, Brazil

Data-driven analysis of tree structural variations across primary, selectively logged, and secondary forests in Brazil's Tapajós National Forest. Uses Python and ellipsoidal geometric modeling to estimate tree-crown volume as a canopy proxy, supporting tropical forest monitoring and conservation management.

## Overview

As one of the major conservation areas in the Amazon, the **Tapajós National Forest** encompasses a wide variety of biomes, and its diverse forest composition has important implications for conservation management. Its dense forest composition—comprising **Primary Forests (PF)**, **Selectively Logged Forests (SLF)**, and **Secondary Forests (SF)**—provides a suitable setting for researching forest structure.

While existing studies in the Tapajós National Forest primarily emphasize carbon stock estimation due to its role as a major carbon sink, variations in individual tree architecture remain underexplored. Assessing this gap, this study investigates and compares variations in phenotypic tree traits across `PF`, `SLF`, and `SF` conditions, demonstrating how geometric modeling can estimate tree-crown volume as an effective proxy for canopy structure and spatial/ecological contrasts.

## Key Methodology & Findings

* **Forest Inventory & Trait Analysis:** Evaluates phenotypic and structural tree measurements across **30 permanent inventory plots** in Tapajós National Forest, contrasting Primary (`PF`), Selectively Logged (`SLF`), and Secondary (`SF`) forest stands using Diameter at Breast Height ($\text{DBH}$), Total Tree Height ($H$), and crown dimensions.
* **Ellipsoidal Tree-Crown Volume Modeling:** Applies 3D geometric modeling using directional crown radii to estimate individual tree-crown volume ($V_{\text{crown}}$) as a scalable proxy for canopy structure and health.
* **Plot-Level Clustering & Contrasts:** Examines how forest plots cluster when evaluated against key structural traits and engineered crown-volume features across forest disturbance types.

## Repository Contents

This repository contains the analysis notebook and conference poster presented at the 6th International Electronic Conference on Applied Sciences (ASEC 2025):

```text
├── *.ipynb                 # Jupyter Notebook containing data preprocessing, correlation analysis, plot clustering, and crown-volume modeling
├── *poster*.pdf            # Official ASEC 2025 conference poster (Introduction & Aim, Results & Discussion, Future Work & References)
└── README.md               # Project documentation
```

## Getting Started

To run the analysis notebook locally, clone the repository and install the core Python scientific computing libraries:

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
pip install numpy pandas scipy scikit-learn matplotlib seaborn jupyter
jupyter notebook
```

## Publication & Citation

This research was presented at **The 6th International Electronic Conference on Applied Sciences (ASEC 2025)**, hosted by MDPI:

* **Conference Event:** [sciforum.net/event/ASEC2025](https://sciforum.net/event/ASEC2025)

If you reference this work, notebook, or poster, please cite:

```bibtex
@inproceedings{boado2025tapajos,
  title     = {Data-Driven Analysis of Tree Structure Variation Across Forest Types in Tapaj{\'o}s National Forest, Brazil},
  author    = {Boado, Jorem Ivan and Jose, Franelyn Dale and Linghap, Sofia Andrea and Jao, Jazzie Rosales and Vallar, Edgar and Galvez, Maria Cecilia},
  booktitle = {The 6th International Electronic Conference on Applied Sciences (ASEC 2025)},
  year      = {2025},
  publisher = {MDPI},
  url       = {https://sciforum.net/event/ASEC2025}
}
```

## Authors & Affiliation

**De La Salle University – Manila, Philippines**
* Jorem Ivan Boado
* Franelyn Dale Jose
* Sofia Andrea Linghap
* Jazzie Rosales Jao
* Edgar Vallar
* Maria Cecilia Galvez