
# Machine Learning / Deep Learning Template (cookiecutter)


## Features
- Virtual Environment managed by `poetry`
- Command Line Code Formatting by  `black` & `isort`
- Jupyter Lab Code Formatting by `jupyterlab-code-formatter`
- Include popular ML/DL packages, including `pytorch`, `scikit-learn`, `xgboost` etc, the
  full package list can be seen in the `{{ cookiecutter.project_slug }}/pyproject.toml` file.

---

## Usage

1 Install [poetry](https://python-poetry.org/docs/#installation)

2 Install [cookiecutter](https://cookiecutter.readthedocs.io/en/stable/installation.html): 

```pip install cookiecutter```

3 Create a new project with this template:

```cookiecutter https://github.com/openpolis/django-project-template.git```

4 Dependency Setup

```make dependency```

If you cannot run the `make` command, you can run the commands listed in the `Makefile`.

5.1 Start Jupyter Lab

```make jupyter-lab```

You can then check if pytorch is installed via `test_notebook.ipynb`, for code formatting in Jupyter Lab, check the page https://ryantam626.github.io/jupyterlab_code_formatter/

5.2 Run Python Shell

```make python-shell```

6 Run Linters

```make lint```