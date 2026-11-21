# PIK3CA H1047R Structure Analysis
Date: 2026-11-21

## Aim
To inspect a PIK3CA-related protein structure and explore its amino acid
composition and nearby protein-ligand atoms using Python.

## Method
1. Downloaded PDB structure 8V8H.
2. Parsed the structure using Biopython.
3. Extracted a protein-chain sequence.
4. Generated an amino acid composition plot.
5. Examined protein-ligand atom distances, where available.

## Results
The generated graph and contact CSV are included only if they existed
in the Colab working directory when this package was created.

## Limitations
PDB residue numbering must be mapped to the UniProt reference sequence
before confirming the H1047R mutation position. Protein chain identity
and ligand identity must also be verified. A 5 Å contact is a geometric
observation, not proof of biological activity or binding affinity.

## Conclusion
This project demonstrates a basic computational workflow for protein
structure inspection. Further validation is required before making
mutation-specific or drug-discovery conclusions.

## Data source
RCSB PDB: https://www.rcsb.org/structure/8V8H
