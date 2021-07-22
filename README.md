# Bicycle Project Crowd Evaluation
This repository contains a code that analyzes a bicycle project dataset to evaluate the quality and the
performance of a crowd of annotators. The repository contains two python files. The first python file is DataSet_JSON_to_CSV.ipynb which converts the used dataset from .json to .csv file to be more simple. As the dataset consists of two files which are the annotator responses file and the reference dataset file, the program converts the annotator responses file to the results.csv file and converts the reference dataset file to the references_dataset.csv file. The second python file is crowd_evaluation.ipynb which uses the given files for the dataset to evaluate the quality of annotators.
# Steps for node running
1. Download the repository on your computer
2. create a conda environment from the 'environment.yml' file:<br/>
`conda env create -f environment.yml`
3. Verify that the new environment was installed correctly:<br/>
`conda env list`<br/>
Note: enviroment called 'crowd_evaluation' shall be found
4. Run the Jupyter Notebook called DataSet_JSON_to_CSV.ipynb cell by cell to create the results.csv file and the references_dataset.csv file
5. Run the Jupyter Notebook called crowd_evaluation.ipynb cell by cell to evaluate the quality of the crowd


