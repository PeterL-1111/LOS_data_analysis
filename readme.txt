Introduction:
This GitHub repository contains a collection of Jupyter notebooks that execute various data manipulation and preparation tasks for a level-of-service(LOS) analysis project. 


Key Highlights:
Data Cleaning: This notebook contains code to filter and clean traffic data from multiple sources. This includes removing duplicate entries, filling in missing values, and subsetting the data to relevant time frames or geographical areas.

Data Joining: Various sets of data, including speed, volume, and road attributes, are joined together in this notebook. The final output is a comprehensive DataFrame that incorporates all relevant attributes for each road segment.

Data Summary: This notebook calculates summary statistics, like the number of road segments with missing data, and performs some basic checks to ensure data quality. It also outputs summary CSV files which can be used for a quick overview of the dataset.

Attribute Checking and Refinement: Road attributes such as lane capacity, speed limits, and road type are refined and filled in this notebook. It ensures that the traffic data is contextually relevant and ready for the next steps of analysis.

Code Workflow:
Data Import: Data is imported from multiple CSV files, which contain raw traffic data and road attributes.
Data Cleaning: Unnecessary columns are dropped, and data is filtered to only include relevant road segments.
Data Merging: DataFrames are merged on common keys like 'LINKID' to create a unified dataset.
Data Summary: Various checks are performed to identify road segments with missing data or attributes.
Export: The cleaned and merged DataFrame is exported to a new CSV file for further analysis.

Disclaimer - Data Security and Sources:
Data Sources:
The traffic volume data is sourced from the Virginia Department of Transportation (VDOT) traffic monitoring system.
Additional attributes and speed data are supplemented from INRIX API and local shapefiles.
Data Access:
Due to data integrity and privacy concerns, the actual data is not provided in this repository. You may request access to the data from the Travel Demand Modeling Group at the Virginia Department of Transportation.