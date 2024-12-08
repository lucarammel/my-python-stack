# my-python-stack

This template is used to start a Python project with the tools I enjoy to use.

## VSCode Settings

Find the settings and extensions I use.

## Package dependency

I use **uv** :

```bash
uv sync
```

```bash
uv add <package>
```

## Formatter and linter

Uses `ruff` :

```bash
uv run ruff format my_project
```

```bash
uv run ruff check my_project 
```

## Testing 

```bash
uv run pytest .
```

## Packages / tools  

- DataFrames : **polars**
- API REST : **fastapi**
- Logging : **loguru**
- CLI : **typer**
- Datetime : **pendulum**
- Making html report : **quarto**
- Plotting : **plotly**, **altair**, **seaborn**
- Reactive notebook : **marimo**
- Application : **streamlit**, **shiny**
- Workflow : **snakemake**

## Running CI locally : 

Use this [tool](https://github.com/firecow/gitlab-ci-local) to run CI locally in gitlab.

```bash
gitlab-ci-local --variables-file .gitlab-ci-local-env
```





