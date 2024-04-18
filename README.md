## Client Segmentation Clustering ML

We have a dataset about the invoices of a company. The dataset contiains data about orders, quantities customers etc. We will try to 
cluster the customers of this company based on their spending behaviour

To install the project you need to install miniconda locally than you need to do the following actions:

minicoda source: https://docs.anaconda.com/free/miniconda/miniconda-install

1. Create the conda environment - this will create an environment based on what you have in 'environment.yml' file
   command:  conda env create -f environment.yml

2. Activate the environement 
   command: conda activate 'env-name'

3. Optionally you can export your denendencies to an external requirements.txt file
   command: conda list --export > requirements.txt     

4. To update dependencies use the update command and --prune flag to remove all other dependencies that are not longer defined in the .yml file
   command: conda env update -f environment.yml --prune


For this project I named my env:  **client-segmentation-env**  and I use conda to activate it using the following command:
   command: conda activate client-segmentation-env
   