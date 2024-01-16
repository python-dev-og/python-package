![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)
[![PyPI version](https://badge.fury.io/py/your-package-name.svg)](https://badge.fury.io/py/your-package-name)

## Instructions for python application package PyPI
Ones your package is ready for upload to PyPi

```commandline
python setup.py sdist
```

```commandline
pip install twine
```

Create an Account on PyPi website and generate API Token  

```commandline
twine upload --skip-existing dist/*
```

follow the prompt 
`username` : `__token__`
`password` : `pypi-Agksnfbkncdsk.......`
