# Classifier
Classifier script which uses the trained model.PTH file to classify unclassified images 

# Overview
The classifier was originally created by Michael Stanly with Lynker Analytics and since then has been updated and modified to be more user friendly, although friendly is debatable.
This script requires a few extra steps be completed before being able to run it. It also requires directory locations for unclassified images, that you want classified, an output directory for sorted images and csv file, and the model PTH location.

# Install Anaconda
https://www.anaconda.com/download

# Create a virtual environment (venv)
Once Anaconda is installed, you will want to open the "Anaconda prompt" and set up your virtual environment. 
In the command line type: conda create --name myenv  python=3.11
To activate the venv: conda activate myenv
to deactivate the venv: conda deactivate

# Install Base packages and load requirements.txt file in your venv
Using conda install install the following: 
- conda
- conda install pytorch torchvision torchaudio -c pytorch -c conda-forge
- 
