# {{ cookiecutter.project_name }}

## Description

{{ cookiecutter.description }}

## Download

Python {{ cookiecutter.py_ver }}

```bash
$ git clone https://github.com/{{ cookiecutter.github_name }}/{{ cookiecutter.project_name }}.git
$ cd {{ cookiecutter.project_name }}
```
make venv in project:
```bash
$ poetry config virtualenvs.in-project true --local
```

Install dependies:
```bash
$ poetry install
```
