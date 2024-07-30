# ETL from OLTP to DWH and Data Visualization
This repository contains a project that performs the ETL (Extract, Transform, Load) process from OLTP (Online Transaction Processing) to DWH (Data Warehouse), then creates Data Marts based on given business requirements. The Data Marts are uploaded to a spreadsheet through a Jupyter Notebook, and subsequently visualized using Looker Studio.

This project compiled by my group Pipeline Wizard in Fast Track Data Engineer program Digital Skola 

## Project Objectives
The project aims to:

- Extract data from the OLTP system.
- Transform the data according to business needs.
- Load the data into the Data Warehouse.
- Create Data Marts based on business requirements.
- Upload the Data Marts to a spreadsheet via Jupyter Notebook.
- Visualize the data using Looker Studio.

## Repository Structure
notebooks/: This file contains the Jupyter Notebook used for the ETL process and uploading Data Marts to the spreadsheet.<br>
config/: This file is used in jupyter notebook<br>
data/: This file contains sample data used in this project.<br>
reports/: This folder contains the visualization reports created with Looker Studio.

Steps

- Data Extraction: Extract data from the OLTP system using the scripts in the scripts/ folder.
- Data Transformation: Transform the extracted data according to business needs. This process also uses the scripts in the scripts/ folder.
- Load to DWH: Load the transformed data into the Data Warehouse.
- Create Data Marts: Create Data Marts based on the business requirements and save them in a format ready for analysis.
- Upload to Spreadsheet: Upload the created Data Marts to a spreadsheet using the Jupyter Notebook in the notebooks/ folder.
- Visualize with Looker Studio: Visualize the data from the spreadsheet using Looker Studio.

## Usage Guide
All necessary files have been uploaded to this repository. To follow the ETL process and see the final visualization:

- Open the jupyter notebook: etl.ipynb
- Follow the steps in the notebook to perform the ETL process and upload the Data Marts to a spreadsheet.
- Open Looker Studio and use the following link to view the data visualization:


## Visualization Results
You can view the data visualization results on Looker Studio using the following link:
https://lookerstudio.google.com/u/0/reporting/a4fe89ab-0caa-4cf3-89b1-957fa865dc7f/page/4aI1D
