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

1. Install either Miniconda (https://conda.io/miniconda.html) or 
Anaconda (https://www.anaconda.com/download/).
2. Install Git (https://git-scm.com/downloads) (already installed on 
many Linux distributions!)

3. Open Terminal(Mac/Linux) or Command Prompt(Windows)

4. Create a new environment using conda:
    
    `conda create -n larva_locomotion python=3.8 -y`

5. Activate the environment in Windows by typing:

    ``activate larva_locomotion``
    
    on Mac/Linux type:
    
    ```source activate larva_locomotion```

6. Install necessary packages by typing all of the below:

    `conda install numpy -y`
    
    `conda install jupyterlab -y`
    
    `conda install matplotlib -y`
    
    `conda install pandas -y`
    
    `conda install -c anaconda pillow -y`
    
    `conda install scipy -y`
    
    `conda install -c conda-forge scikit-image -y`
    
    `conda install -c conda-forge ffmpeg -y`
    
    `conda install natsort -y`
    
    `pip install scikit-posthocs`

    `pip install imageio-ffmpeg`

    `pip install ffmpeg-python`
       
7. Change directory to where you've downloaded the data package

8. Type:
    
    `jupyter lab`
    
9. Your standard browser should open (i.e. Chrome) and one tab should
   say "Home". This is the jupyter notebook. Most scripts in this
   repository are jupyter notebooks.
   
10. Some of the scripts are pure python scripts. To run these, just
    cd to the relevant folder (e.g. "Movies") and run the script by
    typing "python Movie_1.py".
    