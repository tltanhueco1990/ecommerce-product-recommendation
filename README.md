# eCommerce Product Recommendation System

A capstone project exploring product recommendations from historical customer purchase patterns using the UCI Online Retail dataset.

## Project overview

This project investigates how historical customer-product purchase interactions can support an eCommerce product recommendation system. The work covers data understanding, preprocessing, exploratory data analysis, feature engineering, model implementation and comparison, and evaluation of ethical and practical limitations.

The recommendation task is based on historical purchase behavior (implicit feedback). The dataset does not contain explicit product ratings.

## Dataset

The project uses the **Online Retail** dataset from the UCI Machine Learning Repository.

- **Dataset:** Online Retail
- **Repository:** https://archive.ics.uci.edu/dataset/352/online+retail
- **DOI:** https://doi.org/10.24432/C5BW33
- **Citation:** Chen, D. (2015). *Online Retail* [Dataset]. UCI Machine Learning Repository.

The dataset will be obtained from its official source. Raw data files are not committed to this repository at this stage.

## Repository structure

```text
.
├── data/
├── notebooks/
├── src/
├── models/
├── reports/
├── presentations/
├── README.md
├── requirements.txt
└── .gitignore
```

## Project status

**In progress.** Dataset understanding and initial preprocessing have been documented. Applied exploratory data analysis is the next planned stage. Modeling, final reporting, and presentations will be added as the project progresses.

## Environment setup

1. Create and activate a Python virtual environment.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Follow `data/README.md` to obtain and place the dataset locally.
4. Open the notebooks in `notebooks/`.

Dependency versions will be pinned after the project environment is finalized.

## Reproducibility and data handling

- The notebook and reusable source code will document the project workflow.
- Raw datasets and local environment files should not be committed.
- Dataset provenance and preprocessing decisions will be documented.
- Model artifacts and evaluation results will be added after model development.

## License

A repository license has not yet been selected. The dataset remains subject to the terms provided by its official source.
