Please read this AIHW_MBS_1314_1819_README.txt file before using the AIHW_MBS_1314_1819_CSV.csv file.

This AIHW_MBS_1314_1819_README.txt accompanies the AIHW_MBS_1314_1819_CSV.csv file for the 'Medicare-subsidised GP, allied health and specialist health care across local areas: 2013–14 to 2018–19' report. 

The file is intended for loading into analytical software for further analysis. It can be imported into a number of statistical software packages including SAS, R, or read by text editors including Notepad++. 

Tips for analysing the AIHW_MBS_1314_1819_CSV.csv file:
- For more information on the reported services, please see the Technical Information: https://aihw.gov.au/reports/primary-health-care/medicare-subsidised-health-local-areas-2019/contents/technical-information
- For detailed measure specifications, please see the Technical Note: https://aihw.gov.au/reports/primary-health-care/medicare-subsidised-health-local-areas-2019/contents/technical-note/about-the-data-and-measures
- When opening CSV files in Excel, rows of information may be cut off due to Excel's limited capacity of displaying a maximum of 1,048,576 rows.
- The estimated resident population by PHN, SA3 and state/territory geographies are provided as separate CSV files in the zip folder. The files can be merged using the variables ‘Year’, ‘GeographicUnit’, and ‘DemographicGroup’.
- Excludes national data for the SA3 worksheet to avoid duplication. However, the data are available in the Excel tables.

The AIHW_MBS_1314_1819_CSV.csv contains the following variables:
Code: Identifier for AIHW release
DataSource: Data source 
Name: Name of AIHW release
Worksheet: Identifier relating back to Excel download worksheet
Year: Reporting period
StateTerritory: State or Territory
GeographicUnit: Geographic area (i.e. NAT, PHN or SA3)
GeographicCode: Code for geographic unit (i.e. PHN101, or 11101, etc.)
GeographicAreaName: Name of geographic area
GeographicGroup: AIHW group variable (PHN group or SA3 group)
ServiceLevel: Aggregation level (Level 1 = totals)
Service: Type of service
DemographicGroup: Disaggregation (Male, Female, 0-24 years, etc.)
MeasureName: Name of measure
MeasureValue: Value of measure
Flag: Symbol used to flag a measure result
FlagExplanation: Explanation of the flag

The data source for this report includes:

- AIHW analysis of Department of Health, Medicare Benefits claims data, 2013–14 to 2018–19
- AIHW analysis of Australian Prudential Regulation Authority 2019
- Australian Bureau of Statistics, Estimated Resident Population (ERP) 30 June 2001 (age standardisation) and 30 June 2013 to 2018. See accompanying ERP CSV files for
reference.

See AIHW_MBS_1314_1819_metadata.xlsx, Technical Note and Technical Information for full details.


