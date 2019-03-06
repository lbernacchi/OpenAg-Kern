READ_ME

Compiled monthly landuse and AW data from DWR for DAU regions in the Central Valley in 2011-2015.

Data from the Department of Water Resources for monthly time steps of applied water (AW) and land use for 20 standardized crop groups were downloaded as csv files. However, thousands of these files existed for  each year downloaded, with a total of 5 years accumulating to over 25,000 individual files to be scraped for relevant values.

The files in this repository document the processes to consolidate and sort this data as well as the resultant values of interest for this project.

DAU level data from DWR came in a format wherein the csv file name contained information regarding the DAU code, county code, year and crop for the information in the csv file. Within each csv file, the monthly applied water, landuse and evapotranspirations for the specified crop in the specified region and year were given in units of milimeters. 

"python_compiling_script_V0" and other variations of python_compiling_script are the Python scripts used to compile data by each year. "python_compiling_script_V0" contains detailed annotations of the procedures taken to retrieve necessary data from the provided csv files.

Once compiled to their respective Excel workbooks, each water year of data was organized via the use of pviot tables. These tables were used to compile the data into CVPM level data by averaging AW and summing landuse data for each crop group utilizing the "DAU Reference" workbook in this repository as a guideline.

Final values at the CVPM level are given in the file "CAAPM_District_AW_ICA_02202019_valsonly.xlsx" in this repository.
