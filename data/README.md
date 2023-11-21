Merged data for this project

- Main data sourse: connecticut data of data sold at a particular time and with housing attributes (https://catalog.data.gov/dataset/real-estate-sales-2001-2018)
- Combined data1: Monthly Household Estimates  (https://www.google.com/url?q=https://www.census.gov/housing/hvs/data/hist_tab_13a_v2022.xlsx&sa=D&source=docs&ust=1698092254293436&usg=AOvVaw1SoWREp1sWILZohhXWbMOG)
- Combined data2: Quarterly Estimates of the Housing Inventory by Region (https://www.google.com/url?q=https://www.census.gov/housing/hvs/data/hist_tab_10a_v2022.xlsx&sa=D&source=docs&ust=1698092296208887&usg=AOvVaw38t-27_EUMmIzClYA-kEGh)
- Combined data3: No. of New Construction (https://www.census.gov/econ/currentdata/?programCode=RESCONST&startYear=1959&endYear=2023&categories[]=APERMITS&dataType=TOTAL&geoLevel=US&adjusted=1&notAdjusted=0&errorData=0)
- Combined data4: No. of New House sales (https://www.census.gov/econ/currentdata/?programCode=RESSALES&startYear=1963&endYear=2023&categories[]=ASOLD&dataType=TOTAL&geoLevel=US&adjusted=1&notAdjusted=0&errorData=0)
* All of the combined data are combined with (Year, Month) key.
* The quarterly data (i.e., data2) is duplicated for the corresponding month before the merge

Data link: [https://drive.google.com/file/d/1_G3JtSxUf7bR0MzjRkGUQdgFTTRqQOVS/view?usp=drive_link](https://drive.google.com/drive/folders/1LbaQ7vQbNT5nlsfKEDWxtC3G8rBmLnlG)

Data Description
Year: Year the house was sold
Month: Month the house was sold
Town: Town of the house
Address: Address of the house
Assessed Value: Assessed price of the house
Sales Amount: Actual price of the house (Target column)
Sales ratio: Assessed Value/Sales Amount
Property type: Property type of the house (e.g., Residential, Commercial, etc.)
Residential type: Residential type of the house (e.g., Single Family, etc.)
Non Use Code:
Assessor Remarks:
OPM remarks:
Location:
Val_monthly_household_est: monthly estimation of house hold (Combined from data1)
Val_new_construction: Number of new construction (Combined from data3)
Val_new_home_sales: Number of new home in sales (Combined from data3)
Vacant: Number of vacant house inventory in eastwest area (Combined from data2)
Occupied: Number of occupied house inventory in eastwest area (Combined from data2)
