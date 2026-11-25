# Machine Learning — Learning & Experiments

Personal repository for studying machine learning concepts and documenting practical experiments.

## Purpose

This repository is a learning and experimentation space, separate from production applications. Its goal is to make the work reproducible and understandable: each experiment should explain the question, data, method, evaluation and limitations.

## Suggested structure

As the repository grows, organize work by topic or experiment rather than placing unrelated notebooks in the root:

```text
.
├── datasets/          # Small, public or synthetic datasets only
├── notebooks/         # Exploratory analysis and experiments
├── src/               # Reusable code when an experiment matures
├── reports/           # Findings, figures and conclusions
├── requirements.txt   # Or a project-specific lock/configuration
└── README.md
```

Only add directories when there is real content to put in them.

## Experiment checklist

For each substantial experiment, document:

1. **Question:** What are you trying to understand or predict?
2. **Dataset:** Source, license, target variable and relevant limitations.
3. **Preparation:** Missing values, encoding, scaling and leakage prevention.
4. **Baseline:** A simple reference model before more complex approaches.
5. **Evaluation:** Appropriate metrics, validation strategy and class balance.
6. **Results:** What the experiment actually showed.
7. **Limitations:** What cannot be concluded from this dataset or experiment.

## Reproducibility and responsible use

- Record the Python and library versions used.
- Set random seeds where applicable.
- Keep raw datasets, credentials and personal or clinical information out of Git.
- Do not present experimental models as clinically validated or suitable for patient care.
- Prefer public, properly licensed or synthetic datasets.

## Status

This is a study repository. The README describes the intended organization and documentation standard; it does not imply that every suggested directory or experiment already exists.
