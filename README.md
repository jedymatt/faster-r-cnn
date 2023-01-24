# Faster R-CNN

Setup Local Environment using Anaconda or Miniconda

```bash
# setup virtual env
conda create -p .venv

# activate virtual env
conda activate ./.venv

# install dependencies
conda install -c conda-forge --file requirements.txt
```

If you don't have anaconda or miniconda you can use pip instead with venv as the environment

```bash
# setup venv
python -m venv .venv

# activate vertual env
./.venv/Scripts/activate

# install dependencies
pip install -r requirements.txt
```

Run either jupyterlab or notebook

```bash
jupyter-lab 
# or
# jupyter notebook
```

You can also use vscode with [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) extension installed instead of jupyter-lab or notebook
