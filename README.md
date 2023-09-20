# README

This repository contains weights files for polygenic risk scoring by the eMERGE network, as reported in [Lennon et. al](https://www.medrxiv.org/content/10.1101/2023.05.25.23290535v1).

Weights files are named `*_weights.txt`.  The files named `*_sites_used_in_score.ids` indicate which sites from each condition were actually used for scoring the eMERGE dataset.  

## Other files

`ckd_apol1_risk_alleles.txt`: This file defines the APOL1 risk alleles used for the APOL1 risk adjustment applied to the CKD score.

`t1d_hla_interactions.tsv` and `t1d_hla_interactions_self_exclusive_sites.tsv`: These files define the HLA interaction terms included in the T1D score.
