# Time Series Prediction of National Electricity Demand

## Software and Platform
- Software: Google Collab
- Packages:
  - Pandas: data analysis
  - matplotlib: visualizations
  - seaborn: visualizations
  - keras: neural networks
  - sklearn: machine learning and preprocessing
  - statsmodels: statistical models
 
## Documentation Map
- DATA folder: contains smaller data sets and final combined data set. Data appendix includes key tables and plots on review variables.
- OUTPUT folder: all key figures from EDA and the anlysis.
- SCRIPTS: combination of data cleaning and analysis code.

<img width="1174" alt="Documentation Map" src="https://github.com/user-attachments/assets/88c9b54c-7752-419d-b12a-d2e670a7f079" />


## Reproduction Instructions
1. Open Project_2 folder: this contains all documents for the text data project. 
2. Open SCRIPTS folder: contains all of the code
   - Documents are labeled steps 0-2 to indicate the order in which they were produced. 
   - Ignore cleaning documents, unless interested in seeing how data was cleaned and combined. Note: this included linear imputation of missing values, find the code in 0.1.Merge_impute_econ_data.ipynb
3. Open the analysis scripts: 2.Neural_Networks_Analysis.ipynb, 2.Random_Forests_Regressor.ipynb, 2.Time_Series_Model.ipynb
   - Each document contains a different modeling approach to predict total load on MISO grid
   - Follow the comments outlined in the document which take you through the various analyses.
