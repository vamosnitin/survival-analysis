# Survival Analysis Project

This project demonstrates basic survival analysis using a public dataset. The analysis is performed in Python using the `lifelines` library.

## Dataset

We use the classic "lung cancer" dataset, which is publicly available and commonly used for survival analysis demonstrations. The dataset contains survival times and event indicators for patients with advanced lung cancer, along with clinical features.

## Features
- Load and explore the lung cancer dataset
- Fit and visualize Kaplan-Meier survival curves
- Perform log-rank tests to compare groups

## Requirements
- Python 3.9+
- lifelines
- matplotlib
- pandas
- jupyterlab (optional, for interactive exploration)

Install dependencies with:
```bash
pip install -r requirements.txt
```

## Usage
1. Run the notebook `survival_analysis.ipynb` for a step-by-step analysis.
2. Or, run the Python script for a quick demonstration.

## References
- [lifelines documentation](https://lifelines.readthedocs.io/en/latest/)
- [Original lung dataset](https://vincentarelbundock.github.io/Rdatasets/datasets.html)

## License
This project is for educational purposes and uses only public data.
