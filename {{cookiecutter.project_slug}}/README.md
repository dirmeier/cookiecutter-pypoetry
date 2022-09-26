# {{ cookiecutter.project_slug }}

[![status](http://www.repostatus.org/badges/latest/concept.svg)](http://www.repostatus.org/#concept)
[![ci](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_short_description }}/actions/workflows/ci.yaml/badge.svg)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_short_description }}/actions/workflows/ci.yaml)
[![codecov](https://codecov.io/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.project_short_description }}/branch/main/graph/badge.svg)](https://codecov.io/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.project_short_description }})
[![codacy]()]()
[![documentation](https://readthedocs.org/projects/{{ cookiecutter.project_slug }}/badge/?version=latest)](https://{{ cookiecutter.project_slug }}.readthedocs.io/en/latest/?badge=latest)
[![version](https://img.shields.io/pypi/v/{{ cookiecutter.project_slug }}.svg?colorB=black&style=flat)](https://pypi.org/project/{{ cookiecutter.project_slug }}/)

> {{ cookiecutter.project_short_description }}

## About

TODO

## Example usage

TODO

## Installation


To install the latest GitHub <RELEASE>, just call the following on the
command line:

```bash
pip install git+https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_short_description }}@<RELEASE>
```

## Contributing

In order to contribute:

1) Fork and download the repository,
2) create a branch with the name of your new feature (something like `issue/fix-bug-related-to-something` or `feature/implement-new-bound`),
3) install `{{ cookiecutter.project_slug }}` and dev dependencies via `poetry install` (you might need to create a new `conda` or `venv` environment, to not break other dependencies),
4) develop code, commit changes and push it to your branch,
5) create a PR

