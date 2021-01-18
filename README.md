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

### To start a new project:

1. Run

```
cookiecutter https://github.com/YKatser/ml-project-template
```
2. Create a GitLab Repo

Go to your GitLab account and create a new repository. Name it after your `{{cookiecutter.project_name}}`.

3.  Activate your GitLab repo

On your computer, enter your newly created project folder, where project folder is the project_name you entered when you ran cookiecutter, then activate your repository:

```
git init .
git add .
git commit -m "Initial skeleton."
git remote add origin your-gitlab-repo
git push -u origin master
```

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
