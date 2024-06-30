# ndi-ds-tha

To run the Jupyter notebook, use the `conda` package manager and the included `environment.yml` file to create a new virtual environment:

```cmd
conda env create -f environment.yml -n NEW_ENV_NAME
```

Afterwards, activate the environment and register it as a Jupyter kernel:

```cmd
conda activate NEW_ENV_NAME

python -m ipykernel install --user --name=NEW_ENV_NAME
```