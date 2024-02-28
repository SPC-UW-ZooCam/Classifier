# 4. Classifier
Classifier script which uses the trained model.PTH file to classify unclassified images 

# Overview
The classifier was originally created by Michael Stanly with Lynker Analytics and since then has been updated and modified to be more user friendly, although friendly is debatable.
This script requires a few extra steps be completed before being able to run it. Download the documents 

# Install Anaconda
https://www.anaconda.com/download

# Create a virtual environment (venv) named "classenv"
Once Anaconda is installed, you will want to open the "Anaconda prompt" and set up your virtual environment.   
- In the command line type: conda create --name classenv  python=3.11  
- To activate the venv: conda activate classenv  
- To deactivate the venv: conda deactivate  

# Load requirements.txt file in your venv    
From this repository download the requirements.txt file. Once in your activated venv, change direcotories to where the file is saved     
- In the command line type: cd PATH (ex. cd C:\Users\Me\ClassifierCode)  
- Install necessary packages into your venv: pip install -r requirements.txt 

# Update and Run Image_Classification.py
Download and open Image_Classification.py in your text editor (I use PyCharm).  
- Update line 19 with direcotry of unclassified images  
- Update line 20 with output direcotry path  
- Update line 21 with location to model PTH file output from the Algorithm and save  

From your venv run Image_Classficiation.py
-  Change directories (cd) to where Image_Classfication.py is located
-  In the command line run the script: python -m Image_Classification.py
