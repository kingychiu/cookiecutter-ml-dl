dependency:
	pyenv install {{ cookiecutter.python_version }} -s
	pyenv local {{ cookiecutter.python_version }}
	poetry run python -m pip install --upgrade pip
	poetry install --no-root

python-shell:
	poetry run python

jupyter-lab:
	poetry run jupyter-lab

lint:
	# Support jupyter notebook as well
	poetry run isort .
	poetry run black .