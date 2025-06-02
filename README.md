# DSE: 230 Final

# Contents 
- **Dataset/** contains the raw (.csv) and preprocessed (.arff) data that was from WISDM (Wireless Sensor Data Mining) lab dataset from UCI ML Repository. The data set was downloaded from here <https://archive.ics.uci.edu/dataset/507/wisdm+smartphone+and+smartwatch+activity+and+biometrics+dataset>
- **EDA_raw.ipynb:** Contains EDA for the raw data. 
- **EDA_arff.ipynb:** Contains EDA for of the .arff files. Ultimatly we used the raw data in lieu of this data. 
- **Generate_Features.ipynb.ipynb:** This nb cointains the similar code as EDA_raw.ipynb but without the outputs and plots and some exploration. It also creates a .csv for each sensor, features_{sensor}.csv. These files are used in the classification nb
- **features_phone_a.csv, features_phone_g.csv, features_watch_a.csv, features_watch_g.csv:** data files for classification
- **Activity_Classification(LOSO-LR).ipynb:**
- **Activity_Classification(LOSO-RF).ipynb:**
- **Activity_Classification(LOSO-RF-Sub).ipynb:**
- **Activity_Classification(LOSO-watch_a).ipynb:**

# How to run 
The EDA_raw and EDA_arff notebooks are stand alone EDA notebooks. Ensure the path to the dataset source directory of the datasets is correct after downloading. They do not need to be ran before runnning a classifier.

To run the classification models ensure the features_{sensor}.csv files have been created. If they are present run Generate_Features.ipynb. This notebook will create those 4 csv files. 

The classification notebooks will update some librarys (dask, pandas, scikit-learn) with pip to ensure the code will run.


# Authors 
Thomas Brehme, Duy Nguyen, Grant Wagener 

