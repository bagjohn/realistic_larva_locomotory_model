# locomotion in larvaworld : publication scripts

This repository contains  all scripts used to prepare the
paper titled: **Realistic locomotory models of Drosophila larva**

**Note: We used a Linux computer while writing all the scripts. We haven't 
tested them in Windows!

# Experimental dataset 

To access the dataset used in the scripts, please download the zip file called 
"Naive_locomotion_Drosophila_larvae.zip" from [https://doi.gin.g-node.org/10.12751/g-node.5e1ifd/](https://doi.gin.g-node.org/10.12751/g-node.5e1ifd/). 
Unzip the container in a folder named data in this directory.

*Note: Unzipping has only been tested with 7-zip 
(https://www.7-zip.org/download.html)*

*Careful: When unzipping the files you will need 892 Mb of free
space on your harddrive!*


# Installation of necessary packages

1. Make sure python3.9 is installed along with its virtual environment module :
    `sudo apt install python3.9-venv`

2. Create a python 3.9 virtual environment and activate it: 
    `python3.9 -m venv larva_loco_venv`
    `source larva_loco_venv/bin/activate`


3. Install necessary packages :

    `pip install -r requirements.txt`

       
4. Launch jupyter lab. Your standard browser should open (i.e. Chrome) and one tab should
   say "JupyterLab". Most scripts in this
   repository are jupyter notebooks.:
    
    `jupyter lab`

5. Some of the scripts are pure python scripts. To run these, just
    cd to the relevant folder (e.g. "Movies") and run the script by
    typing "python Movie_1.py".
    