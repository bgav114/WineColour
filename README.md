# WineColour

ML-Classification, Python-JupyterNB

Name: Mitchell Susa, Bhargav Rele

1. The datasets for our analysis is the ‘Wine Quality' dataset that is available in the following link:
https://archive.ics.uci.edu/ml/datasets/Wine+Quality
The 'Wine Quality' dataset is comprised of two parts; ‘winequality-red.csv’ and ‘winequality-white.csv' .The 'additional(data and decision tree's)' folder provided in zip file consists of the two datasets.

2. The codes to import the dataset is contained in the IPython Jupyter Notebook file, that has been provided in the same zip file as this ‘readme.txt’ file. The name of this notebook is "Assignment2.ipynb" . Assignment2.ipynb should be opened within the same folder/should have the same directory as the aforementioned csv files. The datasets were then imported into the notebook using the read_csv() function in Pandas. 

3. On completing the exploration phase of the individual attributes, a new csv file was created. The name of this file is 'allWine.csv' and it is provided in the data folder of this zip file. The 'allWine.csv' file is simply a combination of ‘winequality-red.csv’ and ‘winequality-white.csv' where, ‘winequality-red.csv’ was added to the end of ‘winequality-white.csv'. The codes to create the 'allWine.csv' file is provided in Assignment2.ipynb. On ensuring that 'allWine.csv' shared the same directory as Assignment2.ipynb, read_csv() was used to import the file. 

4. The graphviz codes for each machine learning model (that utilises a Decision Tree Classification technique) is also provided in the codes that are in the jupyter notebook. The execution of these codes will initiate the creation of three files (one for each split) consisting of graphviz codes. Each individual code can be copy-pasted into graphviz (online). This will provide a decision tree image of the Decision Tree Classification model for the respective split. The trees are not presented in the report as our final model (most preferred model) is a K-Nearest Neighbour model and, not a Decision Tree model. The codes for each split is provided in the 'additional(data and decision tree's)' folder.


Thank You.

