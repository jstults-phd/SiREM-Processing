# SiREM-Processing
A short jupyter notebook for processing SiREM passive sampler data. SiREM passive samplers work by adsorbing organic contaminants to polyetylene films. 
The concentration measured on the film must be convered to the environmental concentration using PCB calibration standards embedded in the sampler.
This process is highly labor intesive and error prone.
This simple jupyter notebook is intended to automate the process and make data processing faster in the future.

Python 3 is required for this program. Python can be installed using the anaconda distribution or using an independent installation. The anaconda distribution of Python is recommended unless the user has a specific reason for avoiding the anaconda distrubtion.
https://docs.anaconda.com/anaconda/install/index.html

Once anaconda/python installed, the user can clone or the repository if familiar with github, or download as a zip file and extract to a direactory manually on their computer.

A PDF quickstart guide with instructions on how to use the jupyter notebook is included. This quickstart guide provides example data in Excel format which outlines the struture of the input and output files needed for the software.

Required packages for the anaconda distribution can be installed by navigating to the exctracted/cloned directory and using ONE of the two following commands:
If using conda distribution of python, open the 'anaconda prompt' and type in the following line, then hit enter:
conda install --yes --file requirements.txt
NOTE: Conda users may should not need to install requirements, as all requirements come with the anaconda distribtuion.

If using your own distribution of python
pip3 install -r requirements.txt

Please use the conda installer if you have downloaded the anaconda distribution of python. 
It is not recommended to use a virtual environment for the jupyter notebook as the most of the required packages come with the anaconda distribution of python.

NOTE: Jupyter notebook comes installed with the anaconda distribution of Python, no need to install via pip3.

A quick introduction to jupyter notebooks can be found here for users who are not familiar with the process.
https://www.dataquest.io/blog/jupyter-notebook-tutorial/

Please see the quickstart manual for detailed instructions on how to use the SiREM fitting data
