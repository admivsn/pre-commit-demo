# [pre-commit-demo](https://pre-commit.com/)

Pre-commit is python tool for managing pre-commit hooks so that issues are fixed before they get committed, it helps to ensure your code is of the correct standard before it gets reviewed. `pre-commit` should be installed as part of dev requirements using pip or poetry.

Below code quality checks are implemented:
- Flake8: basic code quality checks
- Pylint: ensures PEP8 compliance and finds various code issues
- etc

Run the following command in the repo directory:
```
pre-commit install
```

Now, it will run automatically on staged changes as you commit, and it can also be ran manually (include `--all-files` to run against all files in the repo):
```
pre-commit run --all-files
```