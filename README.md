___
## Process Bulk Data Files from the EIA
___

The U.S. Energy Information Administration publishes many kinds of reports and datasets.  However, on the page https://www.eia.gov/opendata/bulkfiles.php, the EIA provides links to bulk data zip files, that contain much of the data that the EIA uses in its reports, visualizations and table presentations.

This project provides a jupyter notebook that will download, unzip and process these bulk data files so that they can be used as DataFrames for further analysis. 

The 3 example zipfiles that are processed here are the:
* eia bulk Petrolium zipfile: 'http://api.eia.gov/bulk/PET.zip'
* eia bulk Natural Gas zipfile: 'http://api.eia.gov/bulk/NG.zip'
* eia bulk Total Energy zipfile: 'http://api.eia.gov/bulk/TOTAL.zip'


