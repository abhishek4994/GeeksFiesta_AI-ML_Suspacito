# GeeksFiesta_AI-ML_Suspacito

DAY 1:
A dataset is given with file name "train.csv"<br />
Task is to perform data cleaning and describe the dataset.<br />
(Descriptions/explainations provided in the ipynb file with markdown cells)
-Found the no. of empty cells in each column and removed the rows containing the empty cells.  <br />
-Removed the rows containg non numeric values in fields where the data should be numeric  <br />
-Described each field (column) seperately and found outliers<br />
-Dropped all rows containing the outliers<br />
-Dropped the row containing the outlier of the field "pressure" seperately due to datatype issue<br />

DAY 2:
(Descriptions/explainations provided in the ipynb file with markdown cells)
-Analysed every combination of 2 columns in scatter plot and kept only those which were relevant and provided a description as to why they are relevant
-Found correlation of PM2.5 with the other columns and provided descriptions of how PM2.5 is getting affected by other columns
-Visualized the correlation matrix found using heatmap
-Boxplots were plotted for each column in the dataset, and the findings were presented
