# Project Structure

## Directory Overview

```
.
├── data/                      # Dataset directory
│   ├── raw/                   # Original, immutable data
│   └── processed/             # Cleaned and transformed data
├── notebooks/                 # Jupyter notebooks for exploration
├── src/                       # Source code
│   ├── models/                # Model definitions and implementations
│   ├── utils/                 # Utility functions and helpers
│   └── preprocessing/         # Data preprocessing scripts
├── models/                    # Trained model files and checkpoints
├── results/                   # Output directory
│   ├── predictions/           # Model predictions and outputs
│   └── visualizations/        # Plots, charts, and figures
├── tests/                     # Unit tests and integration tests
├── config/                    # Configuration files (YAML, JSON, etc.)
├── docs/                      # Documentation
├── .github/workflows/         # GitHub Actions CI/CD workflows
├── requirements.txt           # Python dependencies
├── .gitignore                 # Git ignore rules
└── README.md                  # Project README
```

## Directory Descriptions

### `data/`
- **raw/**: Store original datasets here. Never modify files in this directory.
- **processed/**: Store cleaned, transformed, and preprocessed data ready for modeling.

### `notebooks/`
Use Jupyter notebooks for:
- Exploratory Data Analysis (EDA)
- Feature engineering experiments
- Model prototyping
- Results visualization

Naming convention: `YYYY-MM-DD_description.ipynb` (e.g., `2024-01-15_eda.ipynb`)

### `src/`
- **models/**: Model architecture definitions, training loops, and inference code
- **utils/**: Helper functions for logging, metrics, data loading, etc.
- **preprocessing/**: Data cleaning, feature extraction, and transformation pipelines

### `models/`
Store trained models and model checkpoints here. Use descriptive names with versioning.

### `results/`
- **predictions/**: Save model predictions and inference outputs
- **visualizations/**: Store generated plots and figures

### `tests/`
Unit tests and integration tests for your code. Follow pytest conventions.

### `config/`
Configuration files for hyperparameters, file paths, and environment settings.

### `docs/`
Documentation files including setup instructions, API docs, and project notes.

### `.github/workflows/`
CI/CD workflows for automated testing and deployment.

## Getting Started

1. **Set up virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Add your data** to `data/raw/`

4. **Create notebooks** in `notebooks/` for exploration

5. **Develop code** in `src/` modules

6. **Add tests** in `tests/`

## Best Practices

- ✅ Keep `data/raw/` read-only
- ✅ Use version control for code, not data or models
- ✅ Document your preprocessing steps
- ✅ Write reusable functions in `src/`
- ✅ Add unit tests for critical functions
- ✅ Use configuration files instead of hardcoded values
- ✅ Document your findings and results
