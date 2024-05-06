# BigThinkAI (UMD)  - *Data Science Lessons*

Created by: **Hevander Da Costa**

## Table of Contents

1. [Overview](#Overview)
2. [Contents](#Contents)
3. [Video Walkthrough](#Video-Walkthrough)
4. [Note](#Note)
5  [Example](#Example)

## Overview
This repository contains the data science lession I designed for the the University of Maryland Club, BigThinkAI, as the data science lead.
The lessons represent an beginner to intermediate course in data science using Pandas,Matplotlib, Seaborn, and Numpy.


## Contents

The following **subjects** are covered:

- [X] Week1DS: Pandas , Data Manipulation , QQ-Plot Histogram Filtering and Indexing Grouping Pivot Tables  
- [X] Week2NB:  Data Cleaning  
- [X] WeeK4DS:  Analytics base tables, Data Quality Report, Imputation Data Transformation



## Video Walkthrough

https://github.com/Hevander27/BigThinkAi/assets/45948489/ecca6f01-88c9-4b7c-a089-15461ffe95e1


**Other Videos**

[BigThinkAI Lesson 1](https://www.youtube.com/watch?v=5gPmyA63o7k&t=1970s)
[BigThinkAI Lesson 2](https://www.youtube.com/watch?v=OPm83_gtqFI)
[BigThinkAI Lesson 3](https://www.youtube.com/watch?v=2A4NMiveKhI)


## Note
The repository contains duplicate files, DS refers to the instructors copy and NB refers to the student copy. 
The three notebooks above cover all the subjects described and show full implementation.


## Example

DataTableSchema Team45

Dataset:airq\_34\_all

Containsdataabouttheaverageamountsoftoxins: ineparticulatematter,nitrogen dioxide,andozone.ThedataiscategorizedbyUHF34neighborhoodforyears2009to 2018.Thereare330rowsand6columns. https://data.cityofnewyork.us/Environment/Air-Quality/c3uy-2p5r



|**Field**|**Type** |**Description**|
| - | - | - |
|**name\_of\_column**|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|**year**|STRING|Year|
|**Borough**|STRING|NYC Borough Name associated with UHF 34 neighborhood|
|**geo\_place\_name**|STRING|UHF 34 Neighborhood name|
|**mean\_fpm**|Float|Average yearly amount of fine particulate matter|
|**mean\_no**|Float|Average yearly amount of nitrogen dioxide|
|**Ozone mean (ppb)**|Float|Average yearly amount of ozone|
||||
Dataset:airq\_42\_all

Containsdataabouttheaverageamountsoftoxins: ineparticulatematter,nitrogen dioxide,andozone.ThedataiscategorizedbyUHF42neighborhoodforyears2009to 2018.Thereare420rowsand6columns. https://data.cityofnewyork.us/Environment/Air-Quality/c3uy-2p5r



|**Field**|**Type** |**Description**|
| - | - | - |
|**name\_of\_column**|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|**year**|STRING|Year|
|**Borough**|STRING|NYC Borough Name associated with UHF 42 neighborhood|
|**geo\_place\_name**|STRING|UHF 42 Neighborhood name|
|**mean\_fpm**|Float|Average yearly amount of fine particulate matter|
|**mean\_no**|Float|Average yearly amount of nitrogen dioxide|
|**Ozone mean (ppb)**|Float|Average yearly amount of ozone|
||||
Dataset:benzene\_42 Containsdataabouttheaverageconcentrationofbenzeneintheair.Thedataiscategorized byUHF42neighborhoodforyears2005and2011.Thereare84rowsand3columns. https://data.cityofnewyork.us/Environment/Air-Quality/fyf4-hrcu



|**Field**|**Type** |**Description**|
| - | - | - |
|**name\_of\_column**|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|**year**|STRING|Year|
|**geo\_place\_name**|STRING|UHF 34 Neighborhood name|
|**mean\_benzene**|Float|Average yearly concentration of benzene in the air|

Dataset:formaldehyde\_42 Containsdataabouttheaverageconcentrationofformaldehydeintheair.Thedatais categorizedbyUHF42neighborhoodforyears2005and2011.Thereare84rowsand3 columns.

https://data.cityofnewyork.us/Environment/Air-Quality/fyf4-hrcu



|**Field**|**Type** |**Description**|
| - | - | - |
|**name\_of\_column**|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|**year**|STRING|Year|
|**geo\_place\_name**|STRING|UHF 34 Neighborhood name|
|**mean\_formaldehyde**|Float|Average yearly concentration of benzene in the air|

Dataset:boiler\_emissions

Containsdataabouttheaverageboileremissionsoftoxinsnitrogendioxide,sulfurdioxide and ineparticulatematter.ThedataiscategorizedbyUHF42neighborhoodforyears2013 and2015.Thereare84rowsand5columns. https://data.cityofnewyork.us/Environment/Air-Quality/fyf4-hrcu



|**Field**|**Type** |**Description**|
| - | - | - |
|**name\_of\_column**|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|**year**|STRING|Year|
|**geo\_place\_name**|STRING|UHF 42 Neighborhood name|
|**nox\_num\_per\_km2**|Float|Number of emissions per kilometer squared|
|**so2\_num\_per\_km2**|Float|Number of emissions per kilometer squared|
|**pm2\_num\_per\_km2**|Float|Number of emissions per kilometer squared|

Dataset:sulfur\_34 Containsdataabouttheaverageamountofsulfurdioxideintheair.Thedataiscategorized byUHF34neighborhoodforyears2008-2015.Thereare272rowsand3columns. https://data.cityofnewyork.us/Environment/Air-Quality/fyf4-hrcu



|**Field**|**Type** |**Description**|
| - | - | - |
|**name\_of\_column**|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|**year**|STRING|Year|
|**geo\_place\_name**|STRING|UHF 34 Neighborhood name|
|**mean\_so2**|Float|Average yearly amount of sulfur|

Dataset:sulfur\_42 Containsdataabouttheaverageamountofsulfurdioxideintheair.Thedataiscategorized byUHF42neighborhoodforyears2008and2015.Thereare336rowsand3columns. https://data.cityofnewyork.us/Environment/Air-Quality/fyf4-hrcu



|**Field**|**Type** |**Description**|
| - | - | - |
|**name\_of\_column**|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|**year**|STRING|Year|
|**geo\_place\_name**|STRING|UHF 42 Neighborhood name|
|**mean\_so2**|Float|Average yearly amount of sulfur|

Dataset:o3\_pm2\_attributable\_hospital\_visits

Containsdataaboutthenumberofemergencydepartmentvisitsandhospitalizationsfor asthmaattributedto ineparticulatematterandozonetoxins.Thedataiscategorizedby UHF42neighborhood.Thedataiscategorizedinthefollowingtimeperiods:2005-2007, 2009-2011,2012-2014,2015-2017.Thereare168rowsand9columns. https://data.cityofnewyork.us/Environment/Air-Quality/fyf4-hrcu



|**Field**|**Type** |**Description**|
| - | - | - |
|**name\_of\_column**|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|**Time Period**|STRING|Two year range|
|**Start\_Date**|STRING|Start date for time period|
|**geo\_place\_name**|STRING|UHF 42 Neighborhood name|
|**child\_o3\_asthma\_hos pital\_per\_100k**|Float|Rate of hospitalizations for asthma in children attributed to ozone out of 100,000|
|**adult\_o3\_asthma\_ho spital\_per\_100k**|Float|Rate of hospitalizations for asthma in adults attributed to ozone out of 100,000|
|**adult\_pm2\_asthma\_e d\_visits\_per\_100k**|Float|Rate of emergency department visits for asthma in adults attributed to fine particulate matter out of 100,000|
|**child\_pm2\_asthma\_e d\_visits\_per\_100k**|Float|Rate of emergency department visits for asthma in children attributed to fine particulate matter out of 100,000|
|**adult\_o3\_asthma\_ed\_ visits\_per\_100k**|Float|Rate of emergency department visits for asthma in adults attributed to ozone out of 100,000|
|**child\_o3\_asthma\_ed\_ visits\_per\_100k** |Float|Rate of emergency department visits for asthma in children attributed to ozone out of 100,001|

Dataset:traf ic\_merged ContainsdataaboutthenumberofmilesdrivenbycarsandtrucksinUHF42 neighborhoods.Thedatacoversyears2005and2016.Thereare84rowsand5columns.

https://data.cityofnewyork.us/Environment/Air-Quality/fyf4-hrcu



|**Field**|**Type** |**Description**|
| - | - | - |
|**name\_of\_column**|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|**year**|STRING|Year|
|**geo\_place\_name**|STRING|UHF 42 Neighborhood name|
|**cars\_million\_miles**|Float|Number of miles traveled by cars in millions|
|**trucks\_million\_miles**|Float|Number of miles traveled by trucks in millions|
|**total\_million\_miles**|Float|Sum of miles traveled by cars and trucks in millions|

**Dataset: adult\_smoking\_joined\_UHF34\_CLEAN**

Thisisdatarelatedtoadultssmokingandbeinginsmokingenvironments.Additionalmetadatawasdropped. Datawasconvertedtonumericvaluestoallowforappropriateusage. [https://a816-dohbesp.nyc.gov/ IndicatorPublic/Subtopic.aspx?theme_code=2,3&subtopic_id=3](https://a816-dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx?theme_code=2,3&subtopic_id=3)

|Field|Type |Description|
| - | - | - |
|**Year**|Category|Year of data, in format yyyy|
|**geo\_type\_name**|Category|Granularity level of geography category|
|**borough**|Category|Borough for data|
|**secondhand\_smoke\_home \_adult\_count**|FLOAT|Count of adults reporting secondhand smoke at home|
|**secondhand\_smoke\_home \_adult\_percent**|FLOAT|Percent of adults reporting secondhand smoke at home|
|**smoking\_adults\_count**|FLOAT|Count of adults reporting smoking|
|**smoking\_adults\_percent**|FLOAT|Percent of adults reporting smoking|
|**secondhand\_smoke\_work\_ adult\_count**|FLOAT|Count of adults reporting secondhand smoke at work|
|secondhand\_smoke\_wor k\_adult\_percent|FLOAT|Percent of adults reporting secondhand smoke at work|

Dataset:NYC\_SDOH Thesocialdeterminantsofhealth(SDH)arethenon-medicalfactorsthatin luencehealth outcomes.Theyaretheconditionsinwhichpeopleareborn,grow,work,live,andage,and thewidersetofforcesandsystemsshapingtheconditionsofdailylife. Variablesinthe SDOHdatabasecorrespondtothe5keydomainsidenti iedbyAHRQ:socialcontext,economic context,education,physicalinfrastructure,andhealthcarecontext.Inadditiontothese domains,thereisacategoryforGeography,whichincludesIDvariables(County,FIPScode, ZCTA,State,andYear)aswellas14countyadjacencyvariablesandurban/ruralcodes. Datawascleanedbasedonthevaluesavailableforthe5 ivecountiesofNewYorkCityfor 2009-2018.Counties:BrooklynCounty-TheBronx,KingsCounty-Brooklyn,NewYork County-Manhattan,QueensCounty-Queens,RichmondCounty-StatenIsland.

*51 rows & 231 columns.* Size:69.7KBSource: [AgencyofHealthcareResearchandQuality](https://www.ahrq.gov/sdoh/data-analytics/sdoh-data.html)



|Field|Type |Description|
| - | - | - |
|**COUNTY**|STRING|County name|
|**FIPSCODE**|INTEGER|State-county FIPS code, 5 digits (County only)|
|**YEAR**|DATE|The year the data is from|
|**ACS\_PCT\_AGE\_65UP**|FLOAT|Percentage of population age 65 and over|
|**ACS\_PCT\_AGE\_0\_17**|FLOAT|Percentage of population age 0-17|
|**ACS\_PCT\_AGE\_15\_17**|FLOAT|Percentage of population age 15-17|
|**ACS\_PCT\_AGE\_0\_4**|FLOAT|Percentage of population age 0-4|
|**etc. - full descrip on in NYC\_SDOH\_dic onary**|||
**NYC\_SDOH\_dictionary**

Detaileddescriptionofeachofthe ields.

*236 rows & 4 columns.* Size:29.5KBSource: [AgencyofHealthcareResearchandQuality](https://www.ahrq.gov/sdoh/data-analytics/sdoh-data.html)

**Asthma\_ED\_Visits**

AsthmaemergencyroomvisitsforNYCresidents. Datacleanedbasedon“lowestcommon denominator”orbasedontheleastdetaileddatasetwhichwastheSDOHdatasetthat containedmoregeneraldatagatheredbasedoncountyratherthanindividualUHF42 neighbourhood. TheaverageofthetotalEDvisitsfromallneighborhoodsineachcountywastakenand organizedbyyear.Theage-adjustedrate(foradultsonly,per10000residents)and estimatedannualrate(per10000residents)fromallcountieswastakenandorganizedby year.AsthmaEDVisitdatawasonlytaken/availablefortheyears2009-2016withnodata availablepercountyfortheyear2015.

*106 rows & 6 columns.* Size:approximatesizeasappearsonyour ileexplorer.Source: [NYC Environment&HealthDataPortal](https://a816-dohbesp.nyc.gov/IndicatorPublic/VisualizationData.aspx?id=2380,4466a0,11,Summarize)



|Field|Type |Description|
| - | - | - |
|**COUNTY**|STRING|County name|
|**YEAR**|DATE|Year of data collection|
|**INDICATOR\_NAME**|STRING|Population name by age. i.e. Adults (18+), Children (0-4), Children (5-17)|
|**NUMBER**|INTEGER|Average  of  the  total  ED  visits  from  all neighborhoods in each county.|
|**AGE\_ADJUSTED\_RA TE**|FLOAT|Number of ED visits per country adjusted for population older than 18 years (adults), per 10,000 residents.|
|**ESTIMATED\_ANNUA L\_RATE**|FLOAT|Number of ED visits per country adjusted for population older than 18 years, per 10,000 residents for that year.|

**Dataset: Indoor\_air\_quality\_all** Datasetcontainsresidentreportedcomplaintsonindoorairquality. Complaintsaretabulatedindividuallyperreport;reportdatesrangefrom2010to2021. Theincludedcolumns:Borough,geo\_place\_name,zipcode,longitudeandlatitude,areused toidentifylocation.

*Rows: 65050*

*Columns: 7*

Size:3,601KB

Source: https://data.cityofnewyork.us/Health/DOHMH-Indoor-Environmental-Complaints/9jgj- bmct/data



|Field|Type |Description|
| - | - | - |
|name\_of\_column|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|Year|STRING|Year|
|Borough|STRING|NYC Borough Name associated with UHF 42 neighborhood|
|geo\_place\_name|STRING|UHF 42 Neighborhood name|



|Zip code|STRING|Zip code of complaint address|
| - | - | - |
|Complaint type|STRING|Type of complaint reported by residents|
|Longitude|FLOAT|Longitude of complaint location|
|Latitude |FLOAT|Latitude of complaint location|

**Dataset: Adultswith Asthma in the Past 12 Months.csv** Description:Prevelanceofadultswithasthmainthepast12months.ListedbyNYCUHF Neighborhoodsandyear.Iremovedmetadata,removedcommas,changedcolumnnames, madeeverythinglowercase,andchangedthedatatypestotheappropriatedatatypesfor eachcolumn.

Rows:521

Columns:8

Size:140kb

Source:NYCEnvironment&HealthDataPortal [https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx? theme_code=2,3&subtopic_id=11](https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx?theme_code=2,3&subtopic_id=11)



|Field|**Type** |Description|
| - | - | - |
|**year** |category|The year of that data point|
|**geo\_type\_name** |cateogry|The type of geography for that data point (ex. Citywide, Neighborhood, Borough)|
|**borough** |category|Name of borough in NYC |
|**geography** |category|The most specific geographical location |
|**geography\_id** |category|Unique geographical ID for every geographical location|
|**adults\_12mo\_asthma\_ag e\_adjusted\_percent** |float|Percentage of adults with asthma adjusted for age|
|**adults\_12mo\_asthma\_nu mber** |float|Number of adults with asthma|
|**adults\_12mo\_asthma\_pe rcent** |float|Percentage of adults with asthma|

**Dataset: Public School Children (5-14 YrsOld) with Asthma.csv** Description:Prevelanceofpublicschoolchildrenfromages5-14withasthma.Listedby NYCUHFNeighborhoodsandyear.Iremovedmetadata,removedcommas,changedcolumn names,madeeverythinglowercase,andchangedthedatatypestotheappropriate datatypesforeachcolumn

Rows:193

Columns:7

Size:25kb

Source:NYCEnvironment&HealthDataPortal [https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx? theme_code=2,3&subtopic_id=11](https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx?theme_code=2,3&subtopic_id=11)



|**Field**|**Type** |**Description**|
| - | - | - |
|**year** |category|The year of that data point|
|**geo\_type\_name** |cateogry|The type of geography for that data point (ex. Citywide, Neighborhood, Borough)|
|**borough** |category|Name of borough in NYC |
|**geography** |category|The most specific geographical location |
|**geography\_id** |category|Unique geographical ID for every geographical location|
|**children\_5\_14\_estimated \_annual\_rate\_per\_1000**|float|Rate of children age 5-14 with asthma (per 1000)|
|**children\_5\_14\_number**|float|Number of children age 5-14 with asthma|
||||
**Dataset: Asthma Emergency Department Visits(Adults).csv** Description:Asthmarelatedemergencydepartmentvisitsforadults.ListedbyNYCUHF Neighborhoodsandyear.Iremovedmetadata,removedcommas,changedcolumnnames, madeeverythinglowercase,andchangedthedatatypestotheappropriatedatatypesfor eachcolumn.

Rows:530

Columns:8

Size:65kb

Source:NYCEnvironment&HealthDataPortal [https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx? theme_code=2,3&subtopic_id=11](https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx?theme_code=2,3&subtopic_id=11)



|**Field** |**Type**|**Description**|
| - | - | - |
|**geo\_type\_name** |cateogry|The type of geography for that data point (ex. Citywide, Neighborhood, Borough)|
|**borough** |category|Name of borough in NYC |
|**geography** |category|The most specific geographical location |
|**geography\_id** |category|Unique geographical ID for every geographical location|
|**ed\_annual\_adult\_estima ted\_age\_adjusted\_rate\_ per10k**|float|Age adjusted rate of adults (per10,000) that visited the emergency department for asthma|
|**ed\_annual\_adult\_rate\_p er10k**|float|Rate of adults (per10,000) that visited the emergency department for asthma|
|**ed\_annual\_adult\_numbe r**|float|Number of adults that visited the emergency department for asthma|
|**year** |category|The year of that data point|

**Dataset: Asthma Emergency Department Visits(Children 5 to 17 YrsOld) .csv** Description:Description:Asthmarelatedemergencydepartmentvisitsforchildren5-17 yearsold.ListedbyNYCUHFNeighborhoodsandyear.Iremovedmetadata,removed commas,changedcolumnnames,madeeverythinglowercase,andchangedthedatatypesto theappropriatedatatypesforeachcolumn.

Rows:577

Columns:7

Size:78kb

Source:NYCEnvironment&HealthDataPortal [https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx? theme_code=2,3&subtopic_id=11](https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx?theme_code=2,3&subtopic_id=11)



|**Field** |**Type**|**Description**|
| - | - | - |
|**geo\_type\_name** |cateogry|The type of geography for that data point (ex. Citywide, Neighborhood, Borough)|
|**borough** |category|Name of borough in NYC |
|**geography** |category|The most specific geographical location |
|**geography\_id** |category|Unique geographical ID for every geographical location|
|**ed\_annual\_5\_17\_rate\_pe r10k**|float|Rate of children 5-17 years old (per10,000) that visited the emergency department for asthma|
|**ed\_5\_17\_number**|float|Number of children 5-17 years old that visited the emergency department for asthma|
|**year** |category|The year of that data point|

**Dataset: Asthma Hospitalizations(Adults).csv** Description:Numberofadultshospitalizedforasthma.ListedbyNYCUHFNeighborhoods andyear.Iremovedmetadata,removedcommas,changedcolumnnames,madeeverything lowercase,andchangedthedatatypestotheappropriatedatatypesforeachcolumn. Rows:530

Columns:8

Size:59kb

Source:NYCEnvironment&HealthDataPortal [https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx? theme_code=2,3&subtopic_id=11](https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx?theme_code=2,3&subtopic_id=11)



|**Field** |**Type**|**Description**|
| - | - | - |
|**geo\_type\_name** |cateogry|The type of geography for that data point (ex. Citywide, Neighborhood, Borough)|
|**borough** |category|Name of borough in NYC |
|**geography** |category|The most specific geographical location |
|**geography\_id** |category|Unique geographical ID for every geographical location|
|**asthma\_hosp\_adult\_esti mated\_\_age\_adjusted\_r ate\_per10k**|float|Age adjusted rate of adults (per10,000) that were hospitalized for asthma|
|**asthma\_hosp\_adult\_esti mated\_\_rate\_per10k**|float|Rate of adults (per10,000) that were hospitalized for asthma|
|**asthma\_hosp\_adult\_nu mber**|float|Number of adults that were hospitalized for asthma|
|**year** |category|The year of that data point|

Dataset:AsthmaHospitalizations(Children5to17YrsOld).csv Description:Numberofchildren5-17yearsoldhospitalizedforasthma.ListedbyNYCUHF Neighborhoodsandyear.Iremovedmetadata,removedcommas,changedcolumnnames, madeeverythinglowercase,andchangedthedatatypestotheappropriatedatatypesfor eachcolumn.

Rows:577

Columns:7

Size:71kb

Source:NYCEnvironment&HealthDataPortal [https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx? theme_code=2,3&subtopic_id=11](https://a816dohbesp.nyc.gov/IndicatorPublic/Subtopic.aspx?theme_code=2,3&subtopic_id=11)



|**Field** |**Type**|**Description**|
| - | - | - |
|**geo\_type\_name** |cateogry|The type of geography for that data point (ex. Citywide, Neighborhood, Borough)|
|**borough** |category|Name of borough in NYC |
|**geography** |category|The most specific geographical location |
|**geography\_id** |category|Unique geographical ID for every geographical location|
|**asthma\_hosp\_5\_17\_esti mated\_annual\_rate\_per \_10000**|float|Rate of children 5-17 years old (per10,000) that were hospitalized for asthma|
|**asthma\_hosp\_5\_17\_num ber**|float|Number of children 5-17 years old hospitalized for asthma|
|**year** |category|The year of that data point|

MedianHouseholdIncomeByRacebyTract,2012-2016 Containsdataabouttheaveragehouseholdincomeorganizedbyraceindifferentstateand

regionallevelsthedataisorganizebyyearfrom2012to2016

Having over 30 ields I will be organizing and cleaning up including below what seems morerelevanttoourresearch

*Rounded number of rows:*72730 *& speci ic number of columns: 33.* Size:72728records [Source: https://racialequity.maps.arcgis.com/apps/mapviewer/index.html? webmap=7ea542ec16364bd58c7d073443a35967](https://racialequity.maps.arcgis.com/apps/mapviewer/index.html?webmap=7ea542ec16364bd58c7d073443a35967)



|**Field**|**Type** |**Description**|
| - | - | - |
|**name\_of\_column**|The python consumable format|Brief description of the field. If the field follows a specific format (e.g. a specific date format) include that here too.|
|**STATE\_NAME** |STRING|Ex: Maryland or New York|
|**ST\_ABBREV** |STRING|EX: MD or NY|
|**Median Household Income in Past 12 Months, Some Other Race Householder - Estimate** |FLOAT|Calculates the median income over a year for a specific group – these are estimates from public census data|
|**Median Household Income in Past 12 Months - Estimate** |FLOAT|Calculates the median income over a year for a specific group – these are estimates from public census data|
|**Median Household Income in Past 12 Months, 2 or More Races Householder - Estimate** |FLOAT|Calculates the median income over a year for a specific group – these are estimates from public census data|



|**Median Household Income in Past 12 Months, American Indian and Alaska Native Householder - Estimate** |FLOAT|Calculates the median income over a year for a specific group – these are estimates from public census data|
| :- | - | :- |
|**Median Household Income in Past 12 Months, Asian Householder - Estimate** |FLOAT|Calculates the median income over a year for a specific group – these are estimates from public census data|
|**Median Household Income in Past 12 Months, Black or African American Householder - Estimate** |FLOAT|Calculates the median income over a year for a specific group – these are estimates from public census data|
|**Median Household Income in Past 12 Months, Hispanic or Latino Householder - Estimate** |FLOAT|Calculates the median income over a year for a specific group – these are estimates from public census data|
|**Median Household Income in Past 12 Months, Native Hawaiian and Other Pacific Islander Householder - Estimate** |FLOAT|Calculates the median income over a year for a specific group – these are estimates from public census data|
|**Median Household Income in Past 12 Months, Non-Hispanic White Householder – Estimate** |FLOAT|Calculates the median income over a year for a specific group – these are estimates from public census data|








