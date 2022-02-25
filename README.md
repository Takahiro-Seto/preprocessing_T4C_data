# preprocessing_T4C_data

These scripts and Jupyter notebook is for extracting data from individual cow data, which was exported from T4C dairy management sysyem.

1. Semi-automatic script for converting individual cow data (html format but extension is .xls) to xlsx format (1_convert_xls(html)_to_xlsx.scpt).  
  * This script is written in Applescript. So you can only use in Mac OS (Same function may be created by using VBA).  
  * Running this script, please choice the folder containing row data (this cannot read pandas directory).  
  * Next, please select the dialog button as you want.  
  
2. Jupyter notebook for extracting milk yield and rumination time from converted-individual cow data (2_extract_MY_and_RT_from_individual_cow_data.ipynb).  
  * This notebook can run with Python library Pandas (if you do not have, please install pip or so).  
  * Descriptions can be found in the notebook.  
  
3. Jupyter notebook for extracting other informations from converted-individual cow data (3_extract_other_information_from_individual_cow_data.ipynb).  
  * This notebook can run with Python library Pandas and NumPy (if you do not have, please install pip or so).  
  * Descriptions can be found in the notebook.  
  
4. Notes on Jupyter notebook.  
  * T4C system used is Japanese version, so some dataframe are written in Japanese.  
  * For English-speaking people　(The date and time are written in American or British style), the part about correcting the date and time may not be necessary.  
