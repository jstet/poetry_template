# Python project template 
Template I use to jumpstart python projects

## Contents:
- Python packages: black, ruff, pre-commit and pytest
- black and ruff config in pyproject.toml
- pre-commit configuration file for black and ruff
- .gitignore for python 

## Dependencies:
- Poetry
- Github Client

## Usage
```
gh repo create <repo name> --public --template=https://github.com/jstet/poetry_template
git clone git@github.com:<repo name>.git 
cd <repo name>
mv poetry_template/ <repo name>/ 
sed -i 's/poetry-template/<repo name>/g; s/poetry_template/<repo name>/g' pyproject.toml
poetry install --all-extras
poetry run pre-commit install
```
