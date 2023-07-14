dependency:
	poetry env use {{ cookiecutter.python_version }}
	poetry run python -m pip install --upgrade pip
	poetry install

python-shell:
	poetry run python

jupyter-lab:
	poetry run jupyter-lab

lint:
	# Support jupyter notebook as well
	poetry run ruff .
	poetry run black .