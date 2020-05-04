# conda-envs

This repo contains Anaconda environment yml files.

Create `environment.yml` file from an env:

```console
$ conda activate myenv
$ conda env export > environment.yml
```

Create an env from the `environment.yml` file:

```console
$ conda env create -f environment.yml
```
