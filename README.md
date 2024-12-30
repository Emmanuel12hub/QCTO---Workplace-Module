# PythonDev
Group project: loading, cleaning and EDA on India Agricultural Dataset
https://www.kaggle.com/datasets/vineetkukreti/indian-agriculture-dataset

## Environment Setup to use the India Agricultural Data Analysis Notebook
### Using Anaconda

1. Download and install Anaconda
   - [www.anaconda.com](https://www.anaconda.com/download/success)
  
2. Open the Anaconda Prompt
   - Create a new anaconda environment called 'data_sci', installing numpy and pandas at the same time:
     
     ```
     conda create -n data_sci numpy pandas
     ```
     
   - Activate the data_sci environment

     ```
     conda activate data_sci
     ```
     
   - Install Jupyter Notebook

     ```
     conda install jupyter notebook   
     ```
     
   - Launch Jupyter Notebook
     
     ```
     jupyter notebook
     ```

### Using Python and Pip

1. Download and Install Python
2. Download and Install Pip
3. Open Command Prompt
   - Install packages, using a pip requirements file:
     
     ```
     python3 -m venv env
     source env/bin/activate
     pip install -r requirements.txt
     ```
   - Launch Jupyter Notebook

     ```
     jupyter notebook
     ```

