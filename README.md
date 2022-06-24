# RL-AKI - v0.1 (June 2022)
Train a Q-Learning agent on AmsterdamUMCdb to optimize treatment policies for AKI prevention in patients with a Sepsis condition. 

- 1_Data_Extraction.ipynb, contains SQL queries to extract desired State and Action spaces from AmsterdamUMCdb
- 2_Data_Aggregation.ipynb, contains aggregation of variables in State and Action spaces, outlier analysis, missing values imputation, and merging of the two spaces
- 3_Data_Preparation.ipynb, contains clustering of State space, binning of Actions to prepare dataset to be fed to the Q-Learning agent
- 4_Modeling.ipynb, contains definition and training of the Q-Learning agent, parameter tuning
- 5_Evaluation, tba

Code by Enrico Calleris, Axel Damen, Ameet Jagesar, Romy Vos. Pieces of code from other sources have been properly acknowledged and referenced.
