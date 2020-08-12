# cookie_classic
classic cookie
## structure
```properties
{{ cookiecutter.project_name }}
├───.github
│   ├───ISSUE_TEMPLATE
│   │   ├─── bug_report.md
│   │   ├─── config.yml
│   │   ├─── feature_request.md
│   │   └─── question.md
│   ├─── .stale.yml
│   ├─── PULL_REQUEST_TEMPLATE.md
│   └─── release-drafter.yml
│   │
├───config
│   └─── __init__.py
│
├───{{ cookiecutter.project_slug }}
│   ├─── __init__.py
│   ├─── __main__.py
│   └─── py.typed
│
├───docs
│   ├───examples
│   │   └─── example.py
│   └─── doc.md
│
├───tests
│   └─── test_{{ cookiecutter.project_slug }}.py
│
├─── .pre-commit-config.yaml
├─── pyproject.toml
│
├─── .gitignore
├─── .editorconfig
├─── makefile
│
├─── LICENSE
├─── CONTRIBUTING.md
└─── README.md 
```

## Download
install cookiecutter:
```sh
$ pip install cookiecutter
```
install this project:
```sh
$ cookiecutter https://github.com/peach-lasagna/cookie_classic.git
```

or

```sh
$ cookiecutter cookie_classic
```
