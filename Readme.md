### You need to setup a virtual machine with python==3.8 and install rasa==3.1
### Create a venv on Ubuntu: 

  - `ìnstall anaconda`
  
  - `conda install -y jupyter`
  
  - `conda create --name my_virtual_env python=3.8`
  
  - `conda install -c conda-forge nb_conda`
  
  - `conda install -c anaconda tensorflow`
  
  - `conda activate my_virtual_env`
  
### Create a virtual env on Windows: 

  - `python3 -m venv ./venv`
  - `\venv\Scripts\activate`
  
# Intallation `Rasa` on Ubuntu and windows: 

`pip3 install -U pip && pip3 install rasa`

### Create a folder: 

  - `mkdir mychatbot`
  
### Run `rasa init`

/!\ Be careful with `rasa init` after downloading the data, domain.yml and config.yml the command will reset everything  

#### Your Turn: Try changing the tokonizer and a new use case, run a new model and compare the results. 
---------------------------------------------------------------------------------------------------
# [PSW](https://solo.to/mathspsw)
