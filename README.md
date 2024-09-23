# Northwestern ORCID Review Reports

1. Create folder for the data needed for the quarterly report: /data/YYYY_MM 
2. Export data from various systems:
  * a. **Export data from the ORCID Public API** using the "ORCID_API_Data_Review.ipynb" and save in the folder "/output/YYYY_MM/YYYY_MM_DD_orcid_merged.csv"
  * b. **Export data from Northwestern Elements** using the Elements Reporting Database and the SQL query "Northwestern_Elements_Reporting_SQL_Query.txt" and sve in the folder "/data/YYYY_MM/YYYY_MM_DD_Elements_AuthorID_NU.csv"
  * c. **Use the latest email from the nuit-iso-iam-am@northwestern.edu** distribution list from NU IT regarding connections between NetID and ORCID. Create a .csv file in the folder "/data/YYYY_MM/YYYY_MM_DD_ORCID_at_NU_Root.csv"
  * d. **Request the latest data from Sponsored Research** regarding investigators with sponsored research projects from 01/01/2021 to present. Create a .csv file in the folder "/data/YYYY_MM/YYYY_MM_DD_Personnel_Sponsored_Projects_since_2021_01-01.csv" 
3. Open and run the notebook for "ORID_Data_Analysis_Quarterly_Report.ipynb" but be sure to change the folders for opening and saving data as needed before running (should be "/output or /data/YYYY_MM/YYYY_MM-DD_FILENAME"). 
