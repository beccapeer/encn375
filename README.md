# ENCN375 Workshop Notebook
Jupyter notebook for ENCN375 Lecture A

## Cloud access: 

Use the button below to access the notebook in your browser (no installations required!)

2023: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/beccapeer/encn375/HEAD?labpath=2023_tutorial.ipynb)

## Local Installation:

If you're feeling adventurous, try a local installation. Ensure you have Anaconda Python (minimum version 3.6) installed. Then:

1. Clone the repo

```bash
git clone https://github.com/beccapeer/encn375
```

2. CD into the repo and create a conda environment

```bash
cd encn375
conda env create -f environment.yml
conda activate encn375
```

3. Add the conda environment so it is accessible from the Jupyter Notebook

```bash
python -m ipykernel install --user --name=encn375
```

## Local Updates:

If you have cloned the github repo to your local machine, you can update the contents by:

```bash
cd encn375
git pull
```

## Use:

If you are a local user, open a Jupyter Notebook server from the terminal:

```bash
jupyter notebook
```

In the local server, or via the binder link, open the notebook for this week. In the local server, select the `encn375` environment in `Kernel > Change kernel`.

Write code and run the notebook cells.



## Author

Rebecca Peer (Civil and Natural Resource Engineering, University of Canterbury)
