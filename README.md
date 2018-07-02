This repository contains two Jupyter notebooks. 

# Notebook 1: Creating an SQLite Database for the Guam Forest Inventory Survey

The first notebook creates an SQLite database containing US Forest Service Forest Inventory data collected on Guam in 2003 and 2013.

## Notes

The Forest Service has kindly provided online access to data from its national forest inventory surveys on its [FIA DataMart](http://apps.fs.fed.us/fiadb-downloads/datamart.html) page. Data are available as Microsoft Access databases (\*.accx) for Windows users and as plain text tables (\*.csv) for Mac and Linux users.

Survey methods and resulting data are very thoroughly documented in PDFs stored in the Access database zip file. For Guam, this is <http://apps.fs.fed.us/fiadb-downloads/Databases/GUaccdb.zip>. 

July, 2018: The [FIA Data mart](https://apps.fs.usda.gov/fia/datamart/datamart.html) has recently been improved. Data can now be downloaded in Postgresql database format (open source) rather than in the Microsoft Access database format (proprietary). Changes to the notebook need to be made. 

# Notebook 2: Analyze Guam Forest Inventory Survey Data

The second notebook demonstrates how to use Python to analyze data in the SQLite database.  In this case, we look for significant changes in Guam tree population sizes between 2003 and 2013. The notebook generates a ![plot](plot.pdf) which clearly shows that only 3 significant changes were detected:
* *Cycas circinalis* significantly decreased
* *Hibiscus tiliaceus* significantly increased
* *Vitex parviflora* significantly increased

## Notes

The cycads observed on Guam were actually *Cycas micronesica*, not *C. circinalis*.

It appears that the FIA sampling scheme, when applied to Guam, results in sample sizes too small to measure changes such as reduction in coconut palms which died from an island-wide coconut rhinoceros beetle infestation and *Neisosperma oppositifolia* (=*Ochrosia oppositifolia*)  which were killed by a fungus.

In addition, a ten-year sampling frequency is too long to adequately monitor rapid changes occurring in Guam's forests.


