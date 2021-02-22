## Introduction to Machine Learning
### Computer Assignments 
#### Should you have questions or issues accessing any documents please contact me via email at jamie.meugniot@lmu.edu or via Teams. 
_________________________________________________________________________________________________________________________________________________________________________________

### CA03 Assignment - Decision Tree Algorithm

The assignment includes 2 data files for upload: 
1. census_data.csv 
2. Automation_Table.csv

Other CA03 Files:
1. CAO3_Questions.docx --> Answers to question set
2. Tree Tuning Cases.xlsx --> Output table for different hyperparameter testing

#### Opening Notebook

The google colab notebook has been set to open for anyone with the link. You also have the ability to edit the notebook. Should you see errors in code or have suggestions for optimization, please create a copy of the notebook so the original stays intact. 

#### Downloading & Accessing the Data

Please find the data file titled 'census_data.csv' to download the data files.

Download data and save in your desired google colab folder. **Note the path to these folders as you will need it when reading the data in later**

In order to access the data you have just saved to your google colab folder you need to add the following code before running the program. If you do not import the drive you will get an error saying that the file could not be found given the path you gave. Run this code and click on the link that appears. Approve google drive to access your folders and copy the access code it gives you back into the colab file and enter.

    from google.colab import drive
    drive.mount('/content/drive')

When reading in your data files from your selected google colab folder when downloaded please make adjustments to the file path as needed to access your selected folder. My folder paths are as follows: 

    census_df = "/content/drive/My Drive/MSBA_Colab_2020/ML_Algorithms/CA03/Data/census_data.csv"
    auto_df = "/content/drive/My Drive/MSBA_Colab_2020/ML_Algorithms/CA03/Data/Automation_Table.csv"

**Code Comments**

Code comments will always be before the code they are describing or in line with the code they are referencing. 
