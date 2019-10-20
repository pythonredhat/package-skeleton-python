### Real Python: Python Packaging 
```bash
https://realpython.com/pypi-publish-python-package/
```

### Python Packaging Authority
```bash
https://packaging.python.org/guides/distributing-packages-using-setuptools/#distributing-packages
```

### Pipenv Setup
```bash
#build virtual enviornment
pipenv --three
pipenv --python 3.6

#enter virtual enviornment
pipenv shell
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
pip install bumpversion
#first ensure git working directory is clean or bump will fail
#patch bump
bumpversion --current-version 1.1.0 patch setup.py hello_world_app/__init__.py
#minor bump
bumpversion --current-version 1.0.0 minor setup.py hello_world_app/__init__.py
#major bump
bumpversion --current-version 1.1.1 major setup.py hello_world_app/__init__.py
```

### Add logging
```bash
https://www.digitalocean.com/community/tutorials/how-to-use-logging-in-python-3
```




