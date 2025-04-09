# Parsons Problems

Cloned from https://github.com/barbarer/p3dnd/

## Setup

The contents of this repository are Parsons Problems implemented in reStructuredText for Runestone. Runestone currently requires Python 3.11.

See the `Old Documentation` section of the [PyPi page](https://pypi.org/project/runestone/).

1. First, install Python <= 3.9. Here, I will use `pyenv` to make this easy:

```sh
pyenv install 3.10
pyenv local 3.10
```

2. Create a virtual environment using the Python version from pyenv:

```sh
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
python --version
```

3. Install dependencies:

```sh
pip install -r requirements.txt
```

4. To build and serve the textbook:

```sh
runestone build
runestone serve
```
