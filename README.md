# datapreperation

## installation
This repository is part of the course data preparation. To run the notebooks several libraries are needed. 
Best is to create a new environment 

  #create new environment
  conda update conda
  conda create --name ITANN python
  
  #activate and install required libraries
  conda activate ITANN
  conda config --env --add channels conda-forge
  conda config --env --set channel_priority strict
  conda install python=3
  conda update python
  conda install numpy
  conda install pandas
  conda install bokeh
  conda install matplotlib
  conda install geopandas
  conda install panel
  conda install hvplot
  
  #create the kernel
  conda install ipykernel
  python -m ipykernel install --user --name=ITANN
  
  #install notebook or lab
  conda install notebook
  conda install jupyterlab
  
  
 You are now ready to launch the notebook or lab. Make sure that you select the kernel ITANN and run the notebooks
 
 
 
 contact: f.feenstra@pl.hanze.nl
