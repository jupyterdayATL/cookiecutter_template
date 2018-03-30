Creates a template Offline Analytic with the following directory structure

Project Organization
------------

    │
    ├── data/               <- Directory of data files
    │   |-- raw/            <- The original immutable data dump.
    │   |-- processed/      <-  cleaned data sets and modelling ready data sets.
    │
    ├── figures/            <- Figures saved by scripts or notebooks.
    │
    ├── deliver/            <- Final deliverable analytic artifacts. Naming convention is a short `-` delimited
    │                          number for ordering, Project Description, Process description, and the creator's initials,
    │                          e.g. `01_CoalAnalysis_DataCleaning`.
    │
    ├── dev/                <- Scratch notebook space, useful for experiments.
    │
    ├── models/             <- Serialized or pickled machine learning models
    │
    ├── src/                <- Python module with source code of this project.
    │
    ├── environment.yml     <- conda virtual environment definition file.
    │
    ├── LICENSE
    │
    ├── README.md           <- The top-level README for developers using this project.

--------

<p><small>Project based on the <a target="_blank" href="https://github.build.ge.com/FleetServicesOfflineAnalytics/sample_offline_template">cookiecutter data science project template</a>.</p>

Usage
------------
1. Install cookiecutter package
    If using public Anaconda repository

    `conda install -c conda-forge cookiecutter `

    If using pip

   `pip install --user cookiecutter --proxy <http://your_proxy_address>`

2. Create an offline analytic Using this template:

    `cookiecutter https://github.com/patanijo/jupyterdayATL_2018_template`

        a. You'll be prompted to enter values for a series of question.
        b. Then it'll create your data science project in the current working directory based on those values.

What does this template do?
----------------------------
* Create a new project based on this template including the following
    * templated Jupyter Notebooks
    * Source code required to create a REST API to a machine learning model.
    * Boilerplate files used for deployment of your machine learning model.
* Create a local virtual environment (conda), with standard dependencies.
* Initialize a local git repository
