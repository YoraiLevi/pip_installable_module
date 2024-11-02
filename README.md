Github actions locally with act
https://nektosact.com/installation/gh.html
```
gh act
```

```
gh act --secret-file .env -W .github/workflows/publish-pypi.yml
```
`.env`
```
TEST_PYPI_API_TOKEN=pypi-******
```