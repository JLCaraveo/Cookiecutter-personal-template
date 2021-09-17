# Cookiecutter Personal Template

This project will help you to create in a easy way your profesional template for your **Data Science Projects.**

## Requirements

- [Anaconda](https://www.anaconda.com/download/) >= 4.x
- [git](https://git-scm.com/) >= 2.x
- [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0:

To install Cookiecutter:

``` bash
pip install cookiecutter
```

o

``` bash
conda install -c conda-forge cookiecutter
```

## First Step

In a folder you want to create the project:

```bash
git clone git@github.com:JoseLHC1992/Cookiecutter-personal-template.git
```

## Second Step
Create the template

```bash
cookiecutter .
```

## One Files Strucure will be created as follow

```
{{ cookiecutter.project_slug }}
        ├── data
        │   ├── processed      <- The final, canonical data sets for modeling.
        │   └── raw            <- The original, immutable data dump.
        │
        ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                         the creator's initials, and a short `-` delimited description, e.g.
        │                         `1.0-jvelezmagic-initial-data-exploration`.
        │
        ├── .gitignore         <- Files to ignore by `git`.
        │
        ├── environment.yml    <- The requirements file for reproducing the analysis environment.
        │
        ├── README.md          <- The top-level README for developers using this project. 
        │
        └── LICENSE            <- One license format for your Project (MIT Format).
```


Thank you for using this Template Generator.