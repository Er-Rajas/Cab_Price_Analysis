# Project Instructions

## Python
- Use Python 3.12+.
- Use type hints for functions.
- Follow PEP 8.
- Prefer clear, readable code over clever code.

## Architecture
- Keep project-specific logic inside src/project_name/.
- Reuse existing functions before creating duplicates.
- Do not create abstractions without a reason.
- Keep modules focused on one responsibility.

## Data Science
- Never modify raw data.
- Keep exploratory work in notebooks.
- Move reusable logic from notebooks into src/.
- Separate preprocessing, training, and evaluation.

## Machine Learning
- Prevent data leakage.
- Keep preprocessing reproducible.
- Save trained models in models/.
- Record important experiment parameters and metrics.

## GenAI / LLM
- Never hard-code API keys.
- Load secrets from environment variables.
- Keep prompts separate from application logic.
- Validate structured LLM output.
- Log/evaluate model behavior where appropriate.

## Dependencies
- Prefer existing project dependencies.
- Do not add a package without checking whether the standard library
  or an existing dependency already solves the problem.

## Code generation
- Before creating a new helper, search the project for existing functionality.
- Do not duplicate existing functions.
- Explain potentially destructive or high-impact changes before implementing them.
