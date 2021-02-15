# py-poetry-package-template

Template for a python package that bundles dependencies using poetry (https://python-poetry.org/)
In addition to the standard initial poetry project template, includes
* `/new_package/data` directory, which can be included in sdist and/or wheel using the `include` key in `pyproject.tml`

References:
* [Can not exclude package data file only for the wheel #3380](https://github.com/python-poetry/poetry/issues/3380)
* [example pyproject.toml](https://github.com/zoj613/htnorm/blob/main/pyproject.toml)

## quick start

install poetry

```
pip install poetry
```

clone and rename 

```
git clone https://github.com/JonThom/py-poetry-package-template.git
mv py-poetry-package-template new_package
cd new_package
```

on Github or Gitlab, set up a new empty repo
then set it as the remote

```
git remote set-url origin <https://github.com/user/new_git_repo>
```

from there on, follow the [poetry docs](https://python-poetry.org/docs/)

