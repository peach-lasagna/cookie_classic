# {{ cookiecutter.project_name }}

## Description

{{ cookiecutter.description }}

## Download

Python {{ cookiecutter.py_ver }}

```bash
$ git clone {{ cookiecutter.hub }}.git
$ cd {{ cookiecutter.project_name }}
```
make venv in project:
```bash
$ poetry config virtualenvs.in-project true --local
```
Update dependies:
```bash
$ poetry update toml
```
Install dependies:
```bash
$ poetry install
```
