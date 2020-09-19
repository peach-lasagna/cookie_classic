# cookie_classic
classic cookie
## structure
```properties
{{ cookiecutter.project_name }}
  |-.editorconfig
  |-.env
  |-.env.example
  |-.github
  |  |-.stale.yml
  |  |-ISSUE_TEMPLATE
  |  |  |-bug_report.md
  |  |  |-config.yml
  |  |  |-feature_request.md
  |  |  |-question.md
  |  |-PULL_REQUEST_TEMPLATE.md
  |  |-release-drafter.yml
  |  |-workflows
  |  |  |-main.yaml
  |-.gitignore
  |-.pre-commit-config.yaml
  |-app
  |  |-__main__.py
  |  |-{{ cookiecutter.project_slug }}
  |  |  |-__init__.py
  |-CONTRIBUTING.md
  |-docs
  |  |-doc.md
  |  |-examples
  |  |  |-example.py
  |-LICENSE
  |-pyproject.toml
  |-README.md
  |-tests
  |  |-test_{{ cookiecutter.project_slug }}.py
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
