This repository contains two Jupyter notebooks. 

# Notebook 1: Creating an SQLite Database for the Guam Forest Inventory Survey

The first notebook creates an SQLite database containing US Forest Service Forest Inventory data collected on Guam in 2003 and 2013.

## Notes

The Forest Service has kindly provided online access to data from its national forest inventory surveys on its [FIA DataMart](http://apps.fs.fed.us/fiadb-downloads/datamart.html) page. Data are available as Microsoft Access databases (\*.accx) for Windows users and as plain text tables (\*.csv) for Mac and Linux users.

Survey methods and resulting data are very thoroughly documented in PDFs stored in the Access database zip file. For Guam, this is <http://apps.fs.fed.us/fiadb-downloads/Databases/GUaccdb.zip>. 

# Notebook 2: Analyze Guam Forest Inventory Survey Data

The second notebook demonstrates how to use Python to analyze data in the SQLite database.  In this case, we look for significant changes in Guam tree population sizes between 2003 and 2013. Only 3 significant changes were detected:

[!https://github.com/aubreymoore/SQLite-database-for-Guam-Forest-Inventory/blob/master/plot.pdf]



## Notes


