# Python Project Template

A template for Python projects with predefined `pyproject.toml` and `.gitignore`.

File `pyproject.toml` includes:
- Predefined author & email
- Predifined rules for Ruff (black, flake8, and isort)
- Predefined dependency groups for UV

## Instructions

First, clone the repository:

```bash
git clone https://github.com/cmcouto-silva/py-template.git
```

You may want to rename the repository folder and update the `pyproject.toml` file, specifically:
- Author and email
- Update project name and the `tool.hatch.build` package name.

And anything else to suit your project needs.

Then, create a virtual environment and install dependencies using `UV`:

```bash
uv sync
```

&nbsp;

Happy coding 😊
