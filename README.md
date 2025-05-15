# FIAM-Hackathon

## Project Overview
This repository contains the work done for the FIAM Hackathon, including data analysis, modeling, and presentations.

## Repository Structure
```
FIAM-Hackathon/
├── data/                      # Data files
│   ├── raw/                   # Original, immutable data
│   │   ├── data_hackathon_3_with_semi_filtered.csv
│   │   ├── hackathon_sample_v2.csv
│   │   ├── eps_actual_first_try_all_data_1Q.csv
│   │   ├── eps_actual_final_data.csv
│   │   ├── factor_char_list.csv
│   │   └── OECD_Macro.csv
│   └── processed/             # Cleaned and processed data
│
├── notebooks/                 # Jupyter notebooks
│   ├── HMM_again.ipynb
│   ├── backtest_regime_version.ipynb
│   ├── Untitled-1.ipynb
│   └── Untitled-2.ipynb
│
├── presentations/            # Presentation files
│   ├── FIAM.pptx
│   └── FIAM-2.pptx
│
├── docs/                     # Documentation
│   └── Document1.docx
│
├── assets/                   # Images and static files
│   └── The_team.jpg
│
└── README.md                 # This file
```

## Data Files
- `data_hackathon_3_with_semi_filtered.csv`: Main dataset for the hackathon
- `hackathon_sample_v2.csv`: Sample dataset
- `eps_actual_first_try_all_data_1Q.csv`: EPS data for first quarter
- `eps_actual_final_data.csv`: Final EPS dataset
- `factor_char_list.csv`: Factor characteristics list
- `OECD_Macro.csv`: OECD macroeconomic data

## Large Data Files
Some data files in this repository are too large to be stored directly on GitHub (>100MB):
- `data_hackathon_3_with_semi_filtered.csv` (1019MB)
- `hackathon_sample_v2.csv` (481MB)

These files are excluded from the repository using `.gitignore`. To work with these files:

1. **Option 1: Use Git LFS**
   ```bash
   # Install Git LFS
   git lfs install
   
   # Track large files
   git lfs track "data/raw/data_hackathon_3_with_semi_filtered.csv"
   git lfs track "data/raw/hackathon_sample_v2.csv"
   ```

2. **Option 2: Download from External Source**
   - Contact the project maintainers for access to the large data files
   - Files are available upon request

## Analysis Notebooks
- `HMM_again.ipynb`: Hidden Markov Model analysis
- `backtest_regime_version.ipynb`: Backtesting regime analysis
- Additional analysis notebooks in the notebooks directory

## Presentations
- `FIAM.pptx`: Initial presentation
- `FIAM-2.pptx`: Updated presentation

## Getting Started
1. Clone this repository
2. Navigate to the notebooks directory to view the analysis
3. Check the presentations directory for project overview and results
4. For large data files, follow the instructions in the "Large Data Files" section

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Python packages (to be listed)

