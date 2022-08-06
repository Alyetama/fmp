# fmp: (F)or(m)at(P)ython

A Python formatter that uses [yapf](https://github.com/google/yapf) and [autoflake](https://github.com/PyCQA/autoflake) to format python files, but ***with properly sorted import statements***.

[![Build](https://github.com/Alyetama/fmp/actions/workflows/poetry-build.yml/badge.svg)](https://github.com/Alyetama/fmp/actions/workflows/poetry-build.yml) [![PyPI version](https://badge.fury.io/py/fmp.svg)](https://badge.fury.io/py/fmp) [![Supported Python versions](https://img.shields.io/badge/Python-%3E=3.6-blue.svg?logo=python)](https://www.python.org/downloads/) [![PEP8](https://img.shields.io/badge/Code%20style-PEP%208-orange.svg?logo=python)](https://www.python.org/dev/peps/pep-0008/) [![GitHub License](https://img.shields.io/badge/License-MIT-red.svg)](https://github.com/Alyetama/Discord-Backup-Bot/blob/main/LICENSE)

## 🐍 Requirements

- [Python>=3.6](https://www.python.org/downloads/)

## ⬇️ Installation

```
pip install fmp
```

## ⌨️ Usage

```
usage: fmp [-h] [-s {pep8,google,yapf,facebook}] [-i] [-o] [-n] [-k] [-K]
           files [files ...]

positional arguments:
  files                 Files to format

options:
  -h, --help            show this help message and exit
  -s {pep8,google,yapf,facebook}, --style {pep8,google,yapf,facebook}
                        Formatting style
  -i, --in-place        Make changes in-place
  -o, --only-imports    Only return sorted import statements
  -n, --show-line-numbers
                        Render a column for line numbers
  -k, --keep-unused-imports
                        Keep the import statement of all unused modules
  -K, --keep-external-unused-imports
                        Keep the import statement of external unused modules
```

## 📕 Examples

[![Examples](static/examples.gif)](https://asciinema.org/a/x8UJrOu8PY7kvMV4UaYbHmrO9)
