# Beyond Credit Scores: Discovering Borrower Risk Profiles and Early Warning Patterns for Loan Default

DSAI 4102 Applied Data Mining · Group 1

| Part | Owner | Notebook |
|---|---|---|
| 1 · Data preparation | Jamal Ejaz (60301792) | `01_data_preparation.ipynb` |
| 1b · Early-warning rules | Jamal Ejaz (60301792) | `01b_early_warning_rules.ipynb` |
| 2 · Borrower profiles (K-Means) | Kelvin Sergio (60106790) | `02_kmeans_profiles.ipynb` |
| 3 · Robustness and alternative methods | Lolwa Alboinin (60106354) | `03_robustness_alternatives.ipynb` |
| 4 · Risk drivers and lender actions | Amal Haji (60100554) | `04_risk_drivers.ipynb` |

## Setup

```
pip install -r requirements.txt
```

Dataset: `accepted_2007_to_2018Q4.csv` from Kaggle
(https://www.kaggle.com/datasets/wordsforthewise/lending-club). It is only needed to run Part 1:
put it in `data/raw/`. Parts 1b to 4 start from the clean files in `data/processed/`.

## Run order

Run each notebook top to bottom, in order: 01 → 01b → 02 → 03 → 04.
Every notebook reads its inputs from `data/processed/` and saves figures to `figures/`.

## Folders

```
data/raw/          Kaggle file (Part 1 only, not shared)
data/processed/    clean data and results shared between parts
figures/           every figure, named by part (01_, 01b_, 02_, ...)
notebooks/         one notebook per part
```

## AI assistance

Parts of the code were drafted with the help of an AI assistant (Claude, Anthropic) and reviewed by the group.
This is cited in the report, as the course guidelines require.
