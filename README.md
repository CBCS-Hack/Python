# Python

## Prep 
Create a virtual environment in Anaconda (Prompt or terminal, depending on operating system), using `conda create --name environment_name` (to create an environment with a specific Python version, run `conda create --name environment_name python=3.4)`. 
You can see a list of all your environment with `conda info --envs`. 
Activate your environment using `conda activate environment_name`. 
To install packages into your environment, run conda install numpy pandas matplotlib seaborn scikit-learn spyder notebook and any other packages you want to install. 
You can also do this directly when creating the environment and specify version of packages you want to work with, e.g. conda create -n environment_name scipy=0.15.0 (-nis just the short version of --name). conda list -n environment_name gives you a list of all packages installed in the current environment. 
You can deactivate your environment with conda deactivate. 


Hint: sometimes you will have to install packages with pip instead of conda. It might be useful to install pip into your base by running conda install pip (for Windows users: you might have to open your Anaconda Prompt as an administrator to be able to install to base but please look this up first to see what it means to run prompt as an administrator). 


For more info on Anaconda see https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf.



To open a notebook, either launch Jupyter Notebook from your environment directly in Anaconda or navigate into your environment (conda activate environment_name) and run jupyter notebook in the Prompt/terminal.
