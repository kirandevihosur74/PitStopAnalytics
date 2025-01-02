# PitStopAnalytics(F1 Championship Predictor Project)
Machine Learning project to predict the future of formula one championships

## Project Overview
This project aims to predict future Formula 1 (F1) driver and constructor championships using historical race data. By employing machine learning techniques such as Clustering and Principal Component Analysis (PCA), we analyze patterns and dynamics from past seasons to forecast upcoming championship outcomes. This repository contains datasets, analysis notebooks, and predictive models essential for understanding the complexities of F1 racing performances.

## Data Source
The data utilized in this project is sourced from the Ergast F1 API, which provides comprehensive details on races, drivers, lap times, pit stops, and more, spanning the history of F1 championships. This rich dataset enables an in-depth exploration of factors influencing F1 success.

## Installation
Clone this repository to your local machine using:
```bash
git clone https://github.com/yourusername/f1-championship-predictor.git
```
Ensure you have Python installed and proceed to install the required libraries:
```bash
pip install -r requirements.txt
```

## Usage
Navigate to the `notebooks` directory to access the Jupyter notebooks:
```bash
cd f1-championship-predictor/notebooks
```
Run Jupyter Notebook or Jupyter Lab:
```bash
jupyter notebook
# or
jupyter lab
```
Open the `Data_Preprocessing.ipynb` to start with data cleaning and preprocessing. Follow the sequence of notebooks for a structured approach to the analysis.

## Structure
- `data/`: Contains raw and processed datasets.
- `notebooks/`: Jupyter notebooks for data preprocessing, EDA, clustering, PCA, and predictive modeling.
- `src/`: Python scripts for custom functions and utilities.
- `models/`: Saved models and scaler objects.
- `requirements.txt`: Required Python packages for project replication.

## Contact
For any queries or contributions, please contact Kiran Devihosur at kirandevihosur74@gmail.com

## Acknowledgments
- Ergast Developer API for providing the F1 data.
- Python and the data science community for the invaluable tools and libraries.

---
