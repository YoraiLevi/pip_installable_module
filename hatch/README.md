# Hatch
[Following the tutorial](https://hatch.pypa.io/latest/intro/)
```
hatch new "Hatch Module YoraiLevi"
```
Tests?
```
```
Building
```
hatch build
```
Publishing
```
```

Credentials
```
~/.pypirc
[pypi]
    repository = https://upload.pypi.org/legacy/
    username = __token__
    password = pypi-*********
```
from pypi/test.pypi
```
pip install hatch-module-yorailevi
pip install -i https://test.pypi.org/simple/ hatch-module-yorailevi
```

from github url
```
python -m pip install "git+https://github.com/YoraiLevi/pip_installable_module/#subdirectory=hatch/hatch-module-yorailevi"
```
Locally, editable
```
pip install -e .
```


configuration?
git tag v0.0.7
git push origin tag v0.0.7
