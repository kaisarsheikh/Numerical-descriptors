# Protein Residue Environment Analyzer

This tool processes PDB files to generate chemical environment descriptors for every amino acid residue. It calculates the Center of Mass (COM) for each residue and counts neighboring residues within multiple distance thresholds (5Å to 25Å) based on chemical properties.

## Features
- Calculates true Center of Mass (COM) for residues.
- Uses KDTree for fast spatial neighbor searching.
- Generates 48 descriptors per residue (8 chemical categories × 6 distance scales).
- Outputs a clean CSV ready for Machine Learning.

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/kaisarsheikh/Numerical-descriptors/.git
   cd protein-env-analysis
