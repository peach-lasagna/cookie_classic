.PHONY: init test lint pretty precommit_install bump_major bump_minor bump_patch

BIN = .venv/bin/
CODE = {{ cookiecutter.project_slug }}

init:
	poetry config virtualenvs.in-project false --local
	poetry install

.PHONY: clean_build
clean:
	rm -rf build/
