# ML project template

Cookiecutter template for ML projects

Inspired by:
- [drivendata template](https://github.com/drivendata/cookiecutter-data-science)
- [gazprom-neft template](https://github.com/gazprom-neft/ml_project_template)

### Requirements to use the cookiecutter template:
 - Python 3.5+
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```

### To start a new project, run:

`cookiecutter https://github.com/YKatser/ml-project-template`

### The resulting directory structure

The directory structure of your new project looks like this:

```
├── README.md          <- The top-level README for developers using this project.
│
├── data
│   ├── raw            <- The original, immutable data dump.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── external       <- Data from third party sources.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is task name SHKPA-XX (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `SHKPA-67-mms-test-LSTM-model-on-all-electrolyses`.
│
├── docs               <- Questions and some other related documentation
│
├── results            <- Intermediate analysis as HTML, PDF, LaTeX, etc.
│
├── .gitignore         <- Avoids uploading data, credentials, outputs, system files etc
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
|
└── src                <- Source code for use in this project.
```
