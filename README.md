# Drug-Likeness Screening Using Lipinski's Rule of Five

## Overview

This project evaluates the drug-likeness of five amino acids using
Lipinski's Rule of Five and SwissADME.

## Compounds

- Leucine
- Alanine
- Valine
- Isoleucine
- Glutamic acid

## Methods

1. Compound information was obtained from PubChem.
2. Canonical SMILES were collected for each compound.
3. Drug-likeness was evaluated using SwissADME.
4. Lipinski's Rule of Five parameters were assessed.
5. Molecular structures were visualized using PyMOL.

## Results

All five compounds passed Lipinski's Rule of Five with zero violations.

| Compound | MW | HBD | HBA | LogP | Ro5 |
|---|---:|---:|---:|---:|---|
| Leucine | 131.17 | 2 | 3 | -1.52 | Pass |
| Alanine | 89.09 | 2 | 3 | -2.96 | Pass |
| Valine | 117.15 | 2 | 3 | -2.26 | Pass |
| Isoleucine | 131.17 | 2 | 3 | -1.72 | Pass |
| Glutamic acid | 147.13 | 3 | 5 | -3.69 | Pass |

## Conclusion

All five compounds met the criteria of Lipinski's Rule of Five,
with no violations observed.
