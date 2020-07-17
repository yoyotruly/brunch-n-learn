brunch-n-learn
==============================

A short description of the project.

<details><summary>Project Organization</summary>

    ├── .env               <- Environment variable that can be parsed by `python-dotenv` package.
    ├── .gitignore         <- Files you DO NOT want to put into source control.
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── environment.yml    <- A declarative way to reproduce or set up Conda python environment.
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── scripts            <- All other helper Bash or PowerShell scripts
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    |   ├── mssql          <- Any SQL Stored Procedures, Queries files
    |   |   |
    |   |   └── sample.sql
    │   │
    |   ├── tests          <- Any Unit Test, Mock Test and Test configuration files
    |   |   |
    |   |   ├── conftest.py
    |   |   ├── mock_test.py
    |   |   └── unit_test.py
    |   | 
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── config.ini            <- Config file to store SQL connection strings

</details>


<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
