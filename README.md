# Python project template 
Template I use to jumpstart python projects

## Contents:
- Python packages: black, ruff, pre-commit and pytest
- black and ruff config in pyproject.toml
- pre-commit configuration file for black and ruff
- .gitignore for python 

## Usage
```
gh repo create <repo name> --public --template=https://github.com/jstet/poetry_template
git clone git@github.com:<repo name>.git 
cd <repo name>
poetry install --all-extras
```