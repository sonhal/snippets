

#### bygge dist
 - pip install --user --upgrade setuptools wheel
 - python setup.py sdist bdist_wheel

#### publisere til PyPI



#### publisere til Test PyPI

 - pip install twine
 - twine upload --repository-url https://test.pypi.org/legacy/ dist/*
