# CIVL575_constitutive_driver

 Term Project for CIVL575

Author: Anthony FU

Constitutive Drivers using Python

This code was created based on the Matlab constitutive driver designed by Prof. Mahdi Taiebat.

It represents the framework of a general constitutive 
driver that may be adopted for use by different constitutive models for 
different element test loadings. The program is prepared for use in the 
course of "Constitutive Models of Soil (CIVL 575)" offered in the 
Department of Civil Engineering at UBC. Loading constraints of laboratory 
experiments are linearized and linked to the constitutive relations 
in order to form a system of ODEs follwoing the proposed method by 
Bardet and Choucair (1991).

## getting started with Python

It is suggested to install Python through Anaconda as other methods of installation might lead to compatibility issues.

You can find the installation instructions here:
```
https://docs.anaconda.com/anaconda/install/
```

Next, we need to create an environment to be used in this course. To do this, open your command line/terminal (in Windows: open the 'Anaconda Prompt') and change the directory to the folder containing the code.  An example of the command would be:
```
cd ~/Documents/CIVL575_constitutive_driver
```
The relevant supplemnetary packages required for the code are listed in the file 'environment.yml'.  To install them, enter the following command:
```
conda env create -f environment.yml
```

## running the notebook 

Before running the notebook, we have to activate the environment by entering the following command:
```
conda activate env_civl575
```
To launch jupyter lab:
```
jupyter lab
```
This will open a jupyter lab instance in your web browser.  Using the directory on the left hand side, you can navigate and click on a .ipynb file to open it.
