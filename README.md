### PiPI test

`python setup.py register -r pypitest`

`python setup.py sdist upload -r pypitest`

### PiPI live

`python setup.py register -r pypi`

`python setup.py sdist upload -r pypi`

### pip install pipi test

`pip install -i https://testpypi.python.org/pypi <package name>`
