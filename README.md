# jupyter-notebook-webcam-liveview
Displaying the webcam liveview in a jupyter-notebook

* Install Miniconda
    * [Download the installer](https://docs.conda.io/en/latest/miniconda.html)
    * [Conda cheat sheet](https://docs.conda.io/projects/conda/en/latest/_downloads/1f5ecf5a87b1c1a8aaf5a7ab8a7a0ff7/conda-cheatsheet.pdf)
* Operating system dependent
    * Windows: Start the "Anaconda Prompt"
    * Linux: Open a terminal window
* Create a virtual environment using the [enviroment.yml](./environment.yml) file <br>`conda env create -f environment.yml`
* Get e list of the virtual environments<br>
`conda env list` <br>
There should now be a virtual environment named `webcam-py36`
* Activate the environment <br>
`conda activate webcam-py36`
* Install Jupyter-Lab <br>
`conda install jupyterlab`
* Install Jupyter-Lab extensions <br>
`https://ipywidgets.readthedocs.io/en/stable/user_install.html`
    * nodejs and ipywidgets should be already installed
    * `jupyter labextension install @jupyter-widgets/jupyterlab-manager`
* Start Jupyter-Lab<br>
`jupyter-lab`
* Open the Jupyter notebook [WebcamLiveView.ipynb](./WebcamLiveView.ipynb)




