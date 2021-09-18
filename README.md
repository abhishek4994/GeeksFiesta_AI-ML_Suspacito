# GeeksFiesta_AI-ML_Suspacito

DAY 1:<br />
A dataset is given with file name "train.csv"<br />
Task is to perform data cleaning and describe the dataset.<br />
(Markdown cells in the ipynb file contain descriptions/explanations)<br />
-Found the no. of empty cells in each column and removed the rows containing the empty cells.  <br />
-Removed the rows containg non numeric values in fields where the data should be numeric  <br />
-Described each field (column) seperately and found outliers<br />
-Dropped all rows containing the outliers<br />
-Dropped the row containing the outlier of the field "pressure" seperately due to datatype issue<br />
<br />
DAY 2:<br />
(Markdown cells in the ipynb file contain descriptions/explanations)<br />
-Analysed every combination of 2 columns in scatter plot and kept only those that were relevant, along with a description of why they were relevant.<br />
-Found correlation of PM2.5 with the other columns and provided descriptions of how PM2.5 is getting affected by other columns<br />
-Visualized the correlation matrix found using heatmap<br />
-Boxplots were plotted for each column in the dataset, and the findings were presented<br />
<br />
DAY 3:<br />
(Markdown cells in the ipynb file contain descriptions/explanations)<br />
-Tried using a simple multivariate liner regression to make a model for prediction of PM2.5 ,it gave low accuracy as expected.<br />
-Tried implementing ANN using keras to make a model but failed<br />
