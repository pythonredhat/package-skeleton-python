### Real Python: Python Packaging 
```bash
https://realpython.com/pypi-publish-python-package/
```

### Python Packaging Authority
```bash
https://packaging.python.org/guides/distributing-packages-using-setuptools/#distributing-packages
```

### Build Python Package
```bash
python setup.py sdist bdist_wheel
```

### Run all unit tests in test folder
```bash
python -m unittest discover
```

### Upload Python Package
```bash
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
```

### Pip Install Package
```bash
pip install your-package-name
pip install hello_world_app
```

### Run Python Package
```bash
#from root directory
python -m hello_world_app
```

### Bump version of Python Package
```bash
#minor bump
bumpversion --current-version 1.0.0 minor setup.py hello_world_app/__init__.py
bumpversion --current-version 1.1.0 major setup.py hello_world_app/__init__.py
```




