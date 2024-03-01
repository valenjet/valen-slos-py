# SLOS in Python

[![PyPI](https://img.shields.io/pypi/v/valen-slos-py.svg)](https://pypi.org/project/valen-slos-py/)
[![Tests](https://github.com/valenjet/valen-slos-py/actions/workflows/test.yml/badge.svg)](https://github.com/valenjet/valen-slos-py/actions/workflows/test.yml)
[![Changelog](https://img.shields.io/github/v/release/valenjet/valen-slos-py?include_prereleases&label=changelog)](https://github.com/valenjet/valen-slos-py/releases)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/valenjet/valen-slos-py/blob/main/LICENSE)

The teaching project _Student Loan Origination System_ (SLOS) written in Python as a project for teaching the concepts of software development.

## Local Development

1. Clone the [valen-slos-py](https://github.com/valenjet/valen-slos-py) repository from GitHub.com to your local computer

Learn more here: [Cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

2. Create a new virtual environment:
```bash
cd valen-slos-py
python3 -m venv venv
source venv/bin/activate
```
Learn more here: [venv — Creation of virtual environments](https://docs.python.org/3/library/venv.html)

3. Now, your terminal prompt should look something like this:
```bash
(venv) $ 
```

See [How do I deactivate the virtual environment?](README.md#how-do-i-deactivate-the-virtual-environment)

## Local Installation

1. Navigate to the project folder, which is where you'll find the `pyproject.toml` file.

2. Now, install the dependencies and test dependencies:
```bash
(venv) $ pip install -e '.[test]'
```

3. Install this `slos` project locally in “editable” mode in this way:
```bash
(venv) $ pip install -e .
```

## Running Tests

Any time you want to run the tests, run `pytest`:
```bash
(venv) $ pytest
```

You should see `pytest` return:
```bash
================================== test session starts ===================================
platform darwin -- Python 3.11.7, pytest-8.0.2, pluggy-1.4.0
rootdir: /Users/sdr/training/valenjet/valen-slos-py
collected 1 item                                                                         

tests/test_slos.py .                                                               [100%]

=================================== 1 passed in 0.00s ====================================
```


## Usage

Usage instructions will eventually go here.


## FAQ

#### How do I deactivate the virtual environment?

Once you're done working in the virtual environment, you can deactivate it by running:

```bash
(venv) $ deactivate
```
