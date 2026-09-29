# Project Name

> Short description of the project.

## Overview

Briefly describe what this project does, the problem it solves, and its main objective.

## Project Status

**Status:** 🚧 In Development

- [ ] Project setup
- [ ] Data collection
- [ ] Data cleaning
- [ ] Exploratory data analysis
- [ ] Feature engineering
- [ ] Model / application development
- [ ] Evaluation
- [ ] Deployment
- [ ] Documentation

## Features

- Feature / capability 1
- Feature / capability 2
- Feature / capability 3

## Tech Stack

- **Language:** Python
- **Environment / Package Manager:** uv
- **Data Analysis:** pandas, NumPy
- **Visualization:** Matplotlib
- **Machine Learning:** scikit-learn
- **Deep Learning:** PyTorch
- **GenAI / LLM:** Add as required
- **Testing:** pytest
- **Linting / Formatting:** Ruff

> Remove technologies that are not used and add project-specific dependencies.

## Project Structure

```text
project_name/
│
├── src/
│   └── project_name/
│       ├── __init__.py
│       ├── config.py
│       └── utils/
│
├── tests/
├── notebooks/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── models/
├── scripts/
├── docs/
│
├── .env.example
├── .gitignore
├── AGENTS.md
├── pyproject.toml
└── README.md
```

## Setup

### 1. Clone the repository

```bash
git clone <repository-url>
cd <project-name>
```

### 2. Install dependencies

```bash
uv sync
```

### 3. Configure environment variables

Copy the example environment file:

```bash
cp .env.example .env
```

Then add the required configuration values to `.env`.

**Never commit `.env` or API keys to Git.**

## Usage

Describe how to run the project.

Example:

```bash
uv run python scripts/main.py
```

For a notebook-based workflow:

```bash
uv run jupyter notebook
```

## Data

### Data Source

**Source:** `<DATA_SOURCE>`

Describe where the data comes from.

### Data Organization

Raw, untouched data:

```text
data/raw/
```

Processed data:

```text
data/processed/
```

External/reference data:

```text
data/external/
```

### Important Variables

| Variable | Description | Type |
|---|---|---|
| `<feature_1>` | Description | Numeric |
| `<feature_2>` | Description | Categorical |
| `<target>` | Target variable | — |

## Machine Learning

> Remove this section if the project does not use machine learning.

### Problem Type

`<Classification / Regression / Clustering / Time Series / Other>`

### Target

`<TARGET_VARIABLE>`

### Features

`<FEATURES>`

### Model

`<MODEL_NAME>`

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- `<Other metric>`

## GenAI / LLM

> Remove this section if the project does not use GenAI or LLMs.

### Model

`<MODEL_NAME>`

### Provider / Runtime

`<Ollama / OpenAI / Hugging Face / Other>`

### Use Case

Describe what the LLM is responsible for.

### Prompt / System Instructions

Keep reusable prompts and system instructions in the appropriate source module rather than hard-coding them throughout the application.

## Results

Document important findings, model performance, or application results here.

| Metric | Value |
|---|---:|
| `<Metric 1>` | — |
| `<Metric 2>` | — |
| `<Metric 3>` | — |

## Experiments

| Experiment | Change | Result | Decision |
|---|---|---|---|
| 001 | `<Change>` | `<Result>` | `<Decision>` |
| 002 | `<Change>` | `<Result>` | `<Decision>` |

## Testing

Run the test suite:

```bash
uv run pytest
```

Run with verbose output:

```bash
uv run pytest -v
```

## Code Quality

Check the code:

```bash
uv run ruff check .
```

Format the code:

```bash
uv run ruff format .
```

## Reproducibility

Record information required to reproduce results:

- Python version
- Dependency lock file
- Dataset version / source
- Random seeds
- Model version
- Training parameters
- Hardware, when relevant

## Documentation

Additional documentation belongs in:

```text
docs/
```

## Future Improvements

- [ ] Improvement 1
- [ ] Improvement 2
- [ ] Improvement 3

## Known Issues

Document known bugs, limitations, data-quality problems, or model limitations.

- Issue / limitation 1
- Issue / limitation 2

## License

`<LICENSE>`

## Author

**<YOUR_NAME>**

GitHub: `<YOUR_GITHUB_PROFILE>`
