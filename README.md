# Cookiecutter PyPackage

Cookiecutter template for a Python package, built with popular develop tools and
conform to best practice.

[![CI Status](https://github.com/william-cass-wright/cookiecutter-pypackage/actions/workflows/dev.yml/badge.svg)](https://github.com/william-cass-wright/cookiecutter-pypackage/actions/workflows/dev.yml)
[![License](https://img.shields.io/pypi/l/ppw)](https://opensource.org/licenses/BSD-2-Clause)
[![codecov.io](https://codecov.io/github/william-cass-wright/badges/coverage.svg?branch=main)](https://codecov.io/github/william-cass-wright/badges?branch=main)


[![Build Status][build-button]][build]
[![Coverage Status][codecov-button]][codecov]
[![Latest Version][mdversion-button]][md-pypi]
[![Python Versions][pyversion-button]][md-pypi]
[![BSD License][bsdlicense-button]][bsdlicense]
[![Code of Conduct][codeofconduct-button]][Code of Conduct]

[build-button]: https://github.com/william-cass-wright/markdown/workflows/CI/badge.svg?event=push
[build]: https://github.com/william-cass-wright/markdown/actions?query=workflow%3ACI+event%3Apush
[codecov-button]: https://codecov.io/gh/william-cass-wright/markdown/branch/master/graph/badge.svg
[codecov]: https://codecov.io/gh/william-cass-wright/markdown
[mdversion-button]: https://img.shields.io/pypi/v/Markdown.svg
[md-pypi]: https://pypi.org/project/Markdown/
[pyversion-button]: https://img.shields.io/pypi/pyversions/Markdown.svg
[bsdlicense-button]: https://img.shields.io/badge/license-BSD-yellow.svg
[bsdlicense]: https://opensource.org/licenses/BSD-3-Clause
[codeofconduct-button]: https://img.shields.io/badge/code%20of%20conduct-contributor%20covenant-green.svg?style=flat-square
[Code of Conduct]: https://github.com/william-cass-wright/markdown/blob/master/CODE_OF_CONDUCT.md

- modeling badges after: https://github.com/Python-Markdown/markdown/blob/master/README.md

~* Documentation: <https://william-cass-wright.github.io/cookiecutter-pypackage>~

## Features

This tool will create Python project with the following features:

* [Poetry](https://python-poetry.org/): Manage dependency, build and release
* [Mkdocs](https://www.mkdocs.org): Writing your docs in markdown style
* Testing with [Pytest](https://pytest.org) (unittest is still supported out of the box)
* Code coverage report and endorsed by [Codecov](https://codecov.io)
* [Tox](https://tox.readthedocs.io): Test your code against environment matrix, lint and artifact check
* Format with [Black](https://github.com/psf/black) and [Isort](https://github.com/PyCQA/isort)
* Lint code with [Flake8](https://flake8.pycqa.org) and [Flake8-docstrings](https://pypi.org/project/flake8-docstrings/)
* Check static type with [Mypy](http://mypy-lang.org/) (optional)
* [Pre-commit hooks](https://pre-commit.com/): Formatting/linting anytime when commit your code
* [Mkdocstrings](https://mkdocstrings.github.io/): Auto API doc generation
* Command line interface using [Click](https://click.palletsprojects.com/en/8.0.x/) (optional)
* [bump2version](https://github.com/c4urself/bump2version): Pre-configured version bumping with a single command
* Continuous Integration/Deployment by [GitHub actions](https://github.com/features/actions), includes:
    - publish dev build/official release to TestPyPI/PyPI automatically when CI success
    - publish documents automatically when CI success
    - extract changelog from CHANGELOG and integrate with release notes automatically
* Host your documentation from [GitHub Pages](https://pages.github.com) with zero-config

## Quickstart

Install the latest Cookiecutter if you haven't installed it yet (this requires Cookiecutter 1.4.0 or higher):

```
pip install -U cookiecutter
```

Generate a Python package project:

```
cookiecutter https://github.com/william-cass-wright/cookiecutter-pypackage.git
```

Then follow **[Tutorial](docs/tutorial.md)** to finish other configurations.

# Credits

This repo is forked from [zillionare/python-project-wizard](https://github.com/zillionare/python-project-wizard), which originally forked from [audreyfeldroy/cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage)


## Other Projects Evaluated

| full_name | created_at | updated_at  | size | stargazers_count |
|-------------------------------------------------------|---------------------------------------------------------------------------------|----|------------------|----|-------------|
| [TezRomacH/python-package-template](https//api.github.com/repos/TezRomacH/python-package-template)            |2020-04-15 14         | 53 | 29 2022-07-17 4  | 12 | 04 1318    763 |
| [audreyfeldroy/cookiecutter-pypackage](https//api.github.com/repos/audreyfeldroy/cookiecutter-pypackage)      |2013-07-14 18      | 52 | 05    2022-07-17 2  | 31 | 21 557 3539 |
| [boromir674/cookiecutter-python-package](https//api.github.com/repos/boromir674/cookiecutter-python-package)  |2022-04-21 1     | 33 | 49  2022-07-04 11 | 48 | 59 451 3    |
| [simonw/click-app-template-repository](https//api.github.com/repos/simonw/click-app-template-repository)      |2021-08-30 1       | 03 | 34    2022-07-17 2  | 01 | 39 12  8     |
| [timhughes/cookiecutter-poetry](https//api.github.com/repos/timhughes/cookiecutter-poetry)                    |2020-09-22 15             | 08 | 49 2022-07-04 8  | 11 | 05 117 5    |
| [waynerv/cookiecutter-pypackage](https//api.github.com/repos/waynerv/cookiecutter-pypackage)                  |2021-05-19 9             | 43 | 34  2022-07-16 3  | 21 | 52 984 44   |
| [zillionare/python-project-wizard](https//api.github.com/repos/zillionare/python-project-wizard)              |2021-04-10 14          | 46 | 32    2022-06-28 9  | 15 | 24 946 55   |
| [william-cass-wright/cookiecutter-click-app](https//api.github.com/repos/william-cass-wright/cookiecutter-click-app)    |2022-06-20 6 | 53 | 50  2022-07-17 5  | 58 | 45 37  0     |
| [william-cass-wright/cookiecutter-pypackage](https//api.github.com/repos/william-cass-wright/cookiecutter-pypackage)    |2022-07-14 8 | 45 | 28  2022-07-17 5  | 52 | 53 984 0    |
