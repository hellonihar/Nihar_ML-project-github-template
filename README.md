# Machine Learning Project Template

A standard folder structure for Data Science and Machine Learning projects.

## Project Structure

```text
├── config/             # Configuration files (YAML, JSON, etc.)
├── data/               # Data files
│   ├── external/       # Data from third party sources
│   ├── interim/        # Intermediate data that has been transformed
│   ├── processed/      # The final, canonical data sets for modeling
│   └── raw/            # The original, immutable data dump
├── docs/               # Project documentation
├── logs/               # Log files generated during training/inference
├── models/             # Trained and serialized models, model predictions, or model summaries
├── notebooks/          # Jupyter notebooks. Naming convention is a number (for ordering),
│                       # the creator's initials, and a short `-` delimited description, e.g.
│                       # `1.0-jqp-initial-data-exploration`.
├── reports/            # Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures/        # Generated graphics and figures to be used in reporting
├── src/                # Source code for use in this project
│   ├── __init__.py     # Makes src a Python module
│   ├── data/           # Scripts to download or generate data
│   ├── features/       # Scripts to turn raw data into features for modeling
│   ├── models/         # Scripts to train models and then use trained models to make predictions
│   └── visualization/  # Scripts to create exploratory and results oriented visualizations
├── tests/              # Unit tests
├── .gitignore          # Files to ignore in git
├── requirements.txt    # The requirements file for reproducing the analysis environment
└── README.md           # The top-level README for developers using this project.
```

## Getting Started

1. Install dependencies: `pip install -r requirements.txt`
2. Configure project settings in `config/`
3. Run notebooks or scripts in `src/`
