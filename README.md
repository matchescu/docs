# matchescu-docs

Currently used to host jupyter notebooks that showcase the rest of the
components of the matchescu suite.

# Running the Notebooks

1. Install [`pyenv`](https://github.com/pyenv/pyenv).
2. Install Python 3.13: `$pyenv install 3.13`
3. Set the local version to 3.13: `$ pyenv local 3.13`
4. Create a virtual environment: `$ python -m venv .venv`
5. Activate it: `$ source .venv/bin/activate`

Finally, install the generic requirements for running the notebooks in this
repo:

```shell
$ pip install --upgrade pip wheel setuptools
$ pip install -r requirements.txt -r requirements-local.txt
```

Verify the installation was successful by running `jupyter-notebook`, then pick
the notebook you want to run. `fellegi_sunter` and `algebraic` are nice
starters.