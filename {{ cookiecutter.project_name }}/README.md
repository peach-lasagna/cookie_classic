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
Install and update dependies:
```bash
$ poetry update
```

Run module:
```bash
$ poetry run python {{ cookiecutter.project_slug }}
```
