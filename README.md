# Pseudomonas Phage Comparative Genomics

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)

## 🎯 Project Overview
Comparative genomic analysis of *Pseudomonas aeruginosa* phages isolated in Africa to identify genomic features enabling effective combat against multidrug-resistant (MDR) strains.

## 🎯 Objectives
1. **Genome Analysis**: Retrieve and compare whole genome sequences from African *P. aeruginosa* phages
2. **Protein Characterization**: Perform in silico analysis of tail fiber and tail spike proteins
3. **Host Range Prediction**: Predict host specificity based on structural and functional features

## 📁 Project Structure
# Pseudomonas Phage Comparative Genomics

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)

## 🎯 Project Overview
Comparative genomic analysis of *Pseudomonas aeruginosa* phages isolated in Africa to identify genomic features enabling effective combat against multidrug-resistant (MDR) strains.

## 🎯 Objectives
1. **Genome Analysis**: Retrieve and compare whole genome sequences from African *P. aeruginosa* phages
2. **Protein Characterization**: Perform in silico analysis of tail fiber and tail spike proteins
3. **Host Range Prediction**: Predict host specificity based on structural and functional features

## 📁 Project Structurepseudomonas-phage-genomics/
├── data/
│   ├── raw/                    # Original genome sequences
│   ├── processed/              # Cleaned and formatted data
│   ├── reference/              # Reference genomes and annotations
│   └── metadata/               # Sample information and metadata
├── scripts/
│   ├── 01_data_retrieval/      # Genome download scripts
│   ├── 02_annotation/          # Pharokka and annotation tools
│   ├── 03_comparative/         # Roary, MAFFT, phylogeny
│   └── 04_visualization/       # Plotting and figure generation
├── notebooks/
│   ├── 01-data-retrieval.ipynb
│   ├── 02-genome-annotation.ipynb
│   ├── 03-comparative-analysis.ipynb
│   └── 04-host-prediction.ipynb
├── results/
│   ├── figures/                # Publication-ready figures
│   ├── tables/                 # Summary tables and statistics
│   └── phylogeny/              # Tree files and alignments
├── docs/                       # Documentation and protocols
└── tests/                      # Unit tests for scripts
## ⚡ Quick Start
```bash
# 1. Clone repository
git clone https://github.com/yourusername/pseudomonas-phage-genomics.git
cd pseudomonas-phage-genomics

# 2. Set up conda environment
conda env create -f environment.yml
conda activate phage-genomics

# 3. Install additional tools
pip install pharokka

# 4. Start analysis
jupyter lab notebooks/01-data-retrieval.ipynb
