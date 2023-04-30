# Tableau-Sample

![DISTRICT DASHBOARD](https://user-images.githubusercontent.com/33337655/235364906-d47fa869-b8ac-4c05-88d2-8bb7b06f310b.png)

EVENT COUNT BY TDEM DISTRICT/COUNTY
Initial page shows grand totals for map chart, district bar chart, and county chart

DRILL DOWN OPTIONS
Select desired district from total events scroll bar, bar chart, or district/county chart.  Districts/counties can be selected directly from the chart as well.

Sheet details
Description of "DISTRICT MAP"
Map based on Longitude (generated) and Latitude (generated). Color shows details about DISTRICT. Size shows count of STORM TYPE. Details are shown for STATE and COUNTY. The data is filtered on Action (COUNTY,DISTRICT) and Action (DISTRICT). The Action (COUNTY,DISTRICT) filter keeps 269 members. The Action (DISTRICT) filter keeps 23 members.
Marks

The mark type is Circle (Automatic).
Stacked marks is off.
Shelves

Rows:	Latitude (generated)
Columns:	Longitude (generated)
Filters:	Action (COUNTY,DISTRICT), Action (DISTRICT)
Level of detail:	STATE, COUNTY
Color:	DISTRICT
Size:	Count of STORM TYPE
Dimensions
COUNTY has 269 members on this sheet
Members: DALLAS; DE WITT; DEAF SMITH; GRAY; KNOX; ...
DISTRICT has 23 members on this sheet
Members: DISTRICT 1 - AMARILLO; DISTRICT 17 - VICTORIA; DISTRICT 4 - HURST/GARLAND; DISTRICT 5 - MT PLEASANT; DISTRICT 7 - ABILENE; ...
STATE has 1 members on this sheet
Members: TEXAS
Measures
Latitude (generated) ranges from 26.11 to 36.28 on this sheet.
Longitude (generated) ranges from -106.30 to -93.71 on this sheet.
Count of STORM TYPE ranges from 1 to 194 on this sheet.
Sets
Action (COUNTY,DISTRICT) has 269 members on this sheet
Members: ANDERSON, DISTRICT 6 - TYLER; ANDREWS, DISTRICT 9 - MIDLAND/FT STOCKTON; ANGELINA, DISTRICT 14 - LUFKIN; ARANSAS, DISTRICT 20 - CORPUS CHRISTI; ARCHER, DISTRICT 3 - WICHITA FALLS; ...
Action (DISTRICT) has 23 members on this sheet
Members: DISTRICT 1 - AMARILLO; DISTRICT 10 - SAN ANGELO; DISTRICT 11 - WACO; DISTRICT 12 - AUSTIN; DISTRICT 13 - BRYAN; 

Description of "EVENT COUNT BY DISTRICT"
Count of STORM TYPE for each DISTRICT. Color shows details about DISTRICT.
Marks

The mark type is Bar (Automatic).
Stacked marks is on.
Shelves

Rows:	Count of STORM TYPE
Columns:	DISTRICT
Color:	DISTRICT
Dimensions
DISTRICT has 23 members on this sheet
Members: DISTRICT 15 - BEAUMONT; DISTRICT 16 - HOUSTON; DISTRICT 18 - SAN ANTONIO; DISTRICT 20 - CORPUS CHRISTI; DISTRICT 21 - WESLACO; ...
Measures
Count of STORM TYPE ranges from 66 to 1,214 on this sheet.
Description of "EVENT COUNT BY COUNTY "
Count of STORM MEASURE broken down by DISTRICT and COUNTY. The data is filtered on Action (DISTRICT), which keeps 23 members.
Marks

The mark type is Text (Automatic).
Stacked marks is on.
Shelves

Rows:	DISTRICT, COUNTY
Filters:	Action (DISTRICT)
Text:	Count of STORM MEASURE
Dimensions
COUNTY has 269 members on this sheet
Members: GRIMES; HARTLEY; HENDERSON; Rusk; VAN HORN & HWY 54 CORRIDOR; ...
DISTRICT has 23 members on this sheet
Members: DISTRICT 1 - AMARILLO; DISTRICT 13 - BRYAN; DISTRICT 18 - SAN ANTONIO; DISTRICT 6 - TYLER; DISTRICT 9 - MIDLAND/FT STOCKTON; ...
Measures
Count of STORM MEASURE ranges from 1 to 194 on this sheet.
Sets
Action (DISTRICT) has 23 members on this sheet
Members: DISTRICT 1 - AMARILLO; DISTRICT 10 - SAN ANGELO; DISTRICT 11 - WACO; DISTRICT 12 - AUSTIN; DISTRICT 13 - BRYAN; ...
Data Source Details

Data Source:	STORMCSV
Type:	federated
Table:	STORMCSV#csv

![COUNT BY MONTHYEAR](https://user-images.githubusercontent.com/33337655/235365520-2b50c598-75f7-4116-9df0-acdb336b4905.png)

![COST DASHBOARD](https://user-images.githubusercontent.com/33337655/235365349-3b3d9348-fa0f-4425-94c9-28dedae0d9dd.png)

![AFFECT BY DISTRICTCOUNTY](https://user-images.githubusercontent.com/33337655/235365350-3e95014b-2ec8-469b-8950-3c389b10ef0b.png)

