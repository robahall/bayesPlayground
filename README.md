README: Bayes Playground. 

Goal: Interested in learning the inner workings of Bayesian Stats include:
*   Generative Models
*   Bayesian regressions
*   Time Series

Packages Explored:
*   pymc3
*   pyro


Dir Structure:
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data               <- Hidden from git/github due to size requirements
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- Data dictionaries, manuals, and all other explanatory materials.
│
├── exps                <- Results of experiments and serialized models, model predictions, or model summaries
│
├── nbs                <- Jupyter notebooks. Naming convention is a date (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `200318_initial_EDA`.
│
├── setup.py           <- Make this project pip installable with `pip install -e`
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   ├── visualization  <- Scripts to create exploratory and results oriented visualizations
│   │   └── visualize.py
│   │
│   └── test  <- Scripts test src files
│       └── test.py
│
└── environment.yml   <- Conda env packages
