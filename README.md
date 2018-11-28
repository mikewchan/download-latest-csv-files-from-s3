# Download latest CSV files from Amazon S3 and push data to Google Sheets

This repository contains multiple Jupyter Notebooks that:

1) Downloads the most recently modified .csv files in an S3 bucket to a local destination folder (Download_data_files_from_S3-scrubbed.ipynb)
2) Takes the data from these CSV files, modifies it, and pushes the data to a Google Sheet for analysis (Product_data_from_CSV_to_GSheets-scrubbed.ipynb)
