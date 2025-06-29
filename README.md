## Ramp Up Predictive Model
### 📌Overview:
This model forecasts ramp-up events in the UK Power Market using real-time and historical market signals.  A ramp-up(/down) or 'trip' is defined as a significant increase (or decrease) in the level of output of a company's products or services. The objective is to anticipate volatility in demand/supply to aid algorithmic trading decisions.

### 🧠 Key Concepts used within this project:
- Machine Learning forecasting
- Time-series regression
- Energy demand modelling

### ⚒️ Tech Stack:
- Python, SQL, Git, Databricks
- Libraries: pandas,  sckit-learn, matplotlib

### 📂 Repository Structure:

- Below is the repository structure that outlines the core details of this project.
- Raw data is obtained from the Modo Energy API: for the context of this project I used the data containing [FPN](https://developers.modoenergy.com/reference/physical-notifications) and [MEL](https://developers.modoenergy.com/reference/maximum-export-limit) information.

```

Ramp-Up-Predictive-Model/
│
├── data/
│ ├── raw/ # Unprocessed market data
│ └── processed/ # Cleaned & ready for modeling
│
├── notebooks/
│ └── exploratory.ipynb # Initial EDA, visualisations, ideas
│
├── src/
│ ├── __init__.py
│ ├── data_prep.py # Functions to load/clean/transform
│ ├── features.py # Feature engineering steps
│ ├── model.py # Model training and evaluation
│ └── predict.py # Live or test prediction pipeline
│
├── outputs/
│ ├── figures/ # Any charts or visuals generated
│ └── model_results/ # Metrics, confusion matrices etc.
│
├── README.md

### Requirements

- Python 3.9+
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib / seaborn
- jupyter
- pyyaml


### How to run
Run all the notebook's in VSCode or copy and paste the raw Python code found within this repository and their corresponding folders.




