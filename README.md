# Executable Notebook Template

This template contains a GitHub action to automate and scheduling execution of Jupyter notebooks. It only works with conda-environment. 

## Steps

* Upload a single notebook `*.ipynb` file. For instance, you can use the templates by theme (Exploration, Preprocessing, Modelling, Postprocessing)  provided by the Environmental Data Science book repository.
* Modify the config file with the notebook file name.
* Upload a conda environment.yml file containing the libraries to run the executable notebook.

After the above steps, the GitHub actions will succesfully generate notebook output cells in the `render` branch.
