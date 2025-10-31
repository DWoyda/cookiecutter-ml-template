# Cookiecutter ML Project Template


A simplified and lightweight cookiecutter template for structuring Machine Learning projects designed specifically for **solo data scientists** and small projects.  

This template was built as a **lean alternative** to the official [cookiecutter-data-science](https://cookiecutter-data-science.drivendata.org/) structure, which, while powerful, is often unnecessarily complex for individual or experimental work.  

The goal is to provide a **clear, minimal, and practical structure** that supports the full ML workflow, from raw data, through preprocessing and model training, to deployment or simple app demos without overwhelming architecture or unused layers.

---

## Quick Start
To generate a new project from this template:

```bash
cookiecutter https://github.com/DWoyda/cookiecutter-ml-project
```

Make sure you have Cookiecutter installed:

```bash
pip install cookiecutter
```

## Project Structure

```text
{{cookiecutter.project_slug}}/
│
├── data/
│   ├── raw/              # Raw input data (e.g. xlsx, csv)
│   ├── processed/        # Cleaned and transformed data
│   └── splits/           # Train/test splits
│
├── models/               # Saved models (e.g. .pkl files)
│
├── notebooks/            # EDA and experimentation notebooks
│   ├── 01_eda.ipynb
│   └── 02_model_dev.ipynb
│
├── reports/              # Visualizations, charts, metrics
│
├── src/                  # Source code
│   ├── __init__.py
│   ├── config.py         # Project-wide parameters
│   ├── etl.py            # Data loading and preprocessing
│   ├── features.py       # Feature engineering
│   ├── train_model.py    # Model training pipeline
│   ├── predict.py        # Prediction logic
│   ├── evaluate.py       # Model evaluation tools
│   └── utils.py          # Helper functions
│
├── app/
│   └── streamlit_app.py  # (Optional) Streamlit interface
│
├── requirements.txt      # Python dependencies
├── LICENSE
└── README.md            
```

<div align="center">
<img width="593" height="105" alt="image" src="https://github.com/user-attachments/assets/c209a4c6-ca9d-4f85-bf94-22f391fea03d" />
<br>
<img width="298" height="463" alt="image" src="https://github.com/user-attachments/assets/bd2da4bb-1a78-4a81-b1ca-78f7b9a657cf" />
</div>

## License
This project is licensed under the [MIT License](LICENSE).

## Credits
Created and maintained by [DWoyda](https://github.com/DWoyda).  
Inspired by the original [cookiecutter-data-science](https://cookiecutter-data-science.drivendata.org/) template. 
