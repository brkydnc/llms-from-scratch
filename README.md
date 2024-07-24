# Setup
First of all, install `jupyter` system-wide,
```sh
pip install jupyter
```
Then, create a virtual environment in this repository,

```sh
python -m venv venv
```
And activate it,
```sh
source ./venv/bin/activate
```
Then, install kernels, and setup virtual environment for jupyter notebooks,
```sh
pip install ipykernel
python -m ipykernel install --user --name=llms-from-scratch-venv
```
# After the setup
Just run the following command, and select a notebook to edit,
```
jupyter notebook
```
After that, go to `Kernel > Change Kernel...` in the notebook toolbar, and
select `llms-from-scratch-venv`.

Happy hacking!
