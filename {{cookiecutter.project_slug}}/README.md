# {{ cookiecutter.project_name }}

[![status](http://www.repostatus.org/badges/latest/concept.svg)](http://www.repostatus.org/#concept)
[![ci](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/actions/workflows/ci.yaml/badge.svg)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/actions/workflows/ci.yaml)
[![codacy]()]()
[![codacy]()]()
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
pip install git+https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}@<RELEASE>
```

## Contributing

In order to contribute:

1) Fork and download the repository,
2) create a branch with the name of your new feature (something like `issue/fix-bug-related-to-something` or `feature/implement-new-feature`),
3) install `{{ cookiecutter.project_slug }}` and dev dependencies via `poetry install` (you might need to create a new `conda` or `venv` environment, to not break other dependencies),
4) develop code, commit changes and push it to your branch,
5) create a PR

## Author

{{cookiecutter.full_name}} <a href="mailto:{{cookiecutter.email}}">{{cookiecutter.email}}</a>
