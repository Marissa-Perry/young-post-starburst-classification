## Overview

This project was developed in Fall 2025 under the mentorship of Prof. Christy Tremonti and graduate student Marissa Perry. The goal of this project is to identify and investigate extremely young ($<50$ Myr) post-starburst (PSB) galaxies using the SDSS-IV/eBOSS survey.

## Structure
- `notebooks/`
    - `01_eBOSS_classification.ipynb`
    - `02_eBOSS_data_analysis.ipynb`
- `data/` - catalog of spectral measurements for eBOSS sources (not tracked in git)
- `classified_sample/` - catalog of candidate young PSBs in eBOSS
- `plots/` - visualizations (not tracked in git)

## Setup

A conda environment for this project can be set up by running:
```bash``       
conda env create -f desi_env.yml
```

Activate this environment with
```bash
conda activate desi_env
```

## Acknowledgements

This research used spectral measurements of eBOSS targets obtained by [Matthews Acuña et al. 2025](https://ui.adsabs.harvard.edu/abs/2025arXiv251218076M/abstract).

