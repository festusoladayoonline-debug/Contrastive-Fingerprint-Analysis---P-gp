# Contrastive Fingerprint Analysis of P‑gp Inhibitors

## Overview
This notebook implements a contrastive learning approach to identify substructures enriched in potent P‑glycoprotein (P‑gp) inhibitors and screens DrugBank for repurposing candidates.

## Requirements
- Python 3.8+
- RDKit
- scikit-learn
- pandas, numpy, matplotlib, seaborn
- chembl_webresource_client

## Data
- ChEMBL: P-gp IC50 data (human ABCB1)
- DrugBank: ~12,000 drug-like compounds

## Results
- Identified substructures associated with P-gp inhibition
- Top 100 candidate drugs ranked by contrast score
- AUC 0.93 for Random Forest classifier

## Files
- `top100_candidates.csv` – Ranked list
- `top10_candidates.png` – Structures of top 10 candidates
- Various plots in notebook outputs
