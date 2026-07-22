# Rain Forecasting in Australia with R

An end-to-end exploratory machine-learning study of the Australian weather dataset. The notebook combines unsupervised learning with a supervised decision-tree model to investigate weather patterns and predict rainfall.

## What this project demonstrates

- Data cleaning and feature preparation in R
- Exploratory analysis and dimensionality reduction with PCA
- Clustering with k-means, DBSCAN, and OPTICS
- Statistical significance testing and interpretation
- Decision-tree training, rule extraction, and validation
- Discussion of model and dataset limitations

## Project file

| File | Description |
| --- | --- |
| [`rain-aus-clusters-decisiontree.ipynb`](rain-aus-clusters-decisiontree.ipynb) | Complete R notebook, including narrative, code, charts, and saved outputs |

The notebook was previously stored with an `.r` extension even though it is a Jupyter notebook. It now uses the correct `.ipynb` extension so GitHub and notebook tools can render it properly.

## View the analysis

GitHub can render the notebook directly. A published version is also available on [Kaggle](https://www.kaggle.com/code/youlikecode/rain-aus-clusters-decisiontree).

## Reproduce the work

1. Install R and Jupyter with an R kernel.
2. Download the Australian weather dataset used by the notebook from Kaggle.
3. Open the notebook and update the dataset path if necessary.
4. Run the cells from top to bottom.

The notebook records the package calls and transformations used in the analysis. Package versions were not locked when the original study was created, so small differences may appear with newer R releases.

## Limitations

This is an analytical case study rather than a deployed forecasting service. Results depend on the historical dataset, its missing-value treatment, and the selected features. A production version would add time-aware validation, reproducible dependency locking, automated tests, experiment tracking, and a prediction API.

## Suggested portfolio use

This project is a good example of analytical reasoning and model interpretation. For a production-oriented portfolio piece, pair it with the MLOps drift-detection pipeline in this profile.
