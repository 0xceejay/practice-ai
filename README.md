# Practice AI

A small, notebook-based practice repo for building up Python data skills used in AI and robotics work. The exercises start with NumPy and Pandas basics, then move into simple data-cleaning workflows using CSV datasets.

## What is inside

```text
.
├── datasets/
│   ├── Iris_dataset.csv
│   └── messy_dataset_50.csv
├── src/
│   ├── data_cleaning/
│   │   └── first.ipynb
│   └── intro_to_packages/
│       ├── numpy_intro.ipynb
│       └── pandas_intro.ipynb
├── requirements.txt
└── README.md
```

## Notebooks

| Notebook | Focus |
| --- | --- |
| `src/intro_to_packages/numpy_intro.ipynb` | NumPy arrays, dimensions, indexing, slicing, reshaping, aggregation, statistics, and random data. |
| `src/intro_to_packages/pandas_intro.ipynb` | Pandas Series and DataFrames, basic tabular data handling, and working with structured data. |
| `src/data_cleaning/first.ipynb` | Cleaning a messy CSV with missing values, inconsistent text, invalid fields, and formatted numeric values. |

## Datasets

| Dataset | Description |
| --- | --- |
| `datasets/Iris_dataset.csv` | Classic Iris flower measurements with species labels. Useful for Pandas practice and beginner ML experiments. |
| `datasets/messy_dataset_50.csv` | A deliberately messy employee-style dataset for practicing cleaning, type conversion, validation, and normalization. |

## Getting started

### 1. Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows PowerShell:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebooks

If you use VS Code, open the repo folder and select the `.venv` Python interpreter as the notebook kernel.

You can also launch Jupyter manually:

```bash
jupyter notebook
```

Then open any notebook under `src/`.

## Suggested learning order

1. Start with `src/intro_to_packages/numpy_intro.ipynb`.
2. Move to `src/intro_to_packages/pandas_intro.ipynb`.
3. Practice real-world cleanup in `src/data_cleaning/first.ipynb`.
4. Revisit `datasets/Iris_dataset.csv` and try your own summaries, charts, or model experiments.

## Common workflow

Use notebooks for experiments, notes, and outputs. Keep reusable datasets in `datasets/`, and add new topic notebooks under `src/` using a clear folder name.

Before adding new dependencies, install them in the virtual environment and update `requirements.txt`:

```bash
pip freeze > requirements.txt
```

## Notes

- The project is designed for practice and exploration, not production deployment.
- Notebook outputs may vary depending on execution order.
- Keep dataset paths relative to the repo root so the notebooks work on other machines.
