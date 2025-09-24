# Pseudomonas Phage Comparative Genomics

## Overview
This project conducts comparative genomic analysis of Pseudomonas aeruginosa phages isolated in Africa to understand genomic features that enable effective combat against multidrug-resistant (MDR) strains.

## Objectives
1. Retrieve and compare whole genome sequences from African P. aeruginosa phages
2. Perform in silico proteomic characterization of tail fiber and tail spike proteins
3. Predict host range specificity based on structural and functional features

## Project Structure
pseudomonas-phage-genomics/
├── data/                   # Raw and processed genome sequences
├── scripts/               # Analysis scripts (Python/R/bash)
├── results/               # Analysis outputs, figures, tables
├── docs/                  # Documentation, methods, references
├── notebooks/             # Jupyter notebooks for exploration
├── environment.yml        # Conda environment specification
└── README.md             # This file

## Quick Start
1. Clone this repository
2. Set up the conda environment: `conda env create -f environment.yml`
3. Activate environment: `conda activate phage-genomics`
4. Follow analysis notebooks in order: `01-data-retrieval.ipynb` → `02-annotation.ipynb` → etc.

## Methods
- **Genome Retrieval:** NCBI GenBank, Virus-Host DB, IMG/VR
- **Annotation:** Pharokka
- **Comparative Analysis:** Progressive Mauve, MUMmer, Roary
- **Protein Modeling:** AlphaFold, Phyre2
- **Host Prediction:** RaFAH, GSPHI, HoPhage, vHULK

## Expected Outcomes
- Curated dataset of African P. aeruginosa phages
- Structural characterization of host-specificity determinants
- Host range predictions for therapeutic applications

## Contributing
Please read [CONTRIBUTING.md](docs/CONTRIBUTING.md) for guidelines on contributing to this project.

## License
This project is licensed under the MIT License - see [LICENSE](LICENSE) file.
