# Hatch
[Following the tutorial](https://hatch.pypa.io/latest/intro/)
```
hatch new "Hatch Module YoraiLevi"
```
## Tests
```
pytest
```

## Building
```
hatch build
python -m build
```

## Publishing from cli
```
hatch publish

hatch publish -r test
twine upload dist/* -r testpypi
```

## Install
### from pypi/test.pypi
```
pip install hatch-module-yorailevi
pip install -i https://test.pypi.org/simple/ hatch-module-yorailevi
```

### from github url
```
python -m pip install "git+https://github.com/YoraiLevi/pip_installable_module/#subdirectory=hatch/hatch-module-yorailevi"
```
### Locally, editable
```
pip install -e .
```


