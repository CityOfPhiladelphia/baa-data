# Parking Violations

Source: Bureau of Adminsitrative Adjudication

Summary
--------------------------
Records of parking violations in the City of Philadelphia, issued by the Philadelphia Parking Authority, Police Department, and more. Information includes ticket number, license plate number, state of registration (PA, NJ, etc), date and time the violation was written, along with the type of violation, and hundred block of location.


Details
-----------------

| Attribute | Details |
| ---------- |--------------|
| Title | Parking Violations |
| Department | Bureau of Administrative Adjudication |
| Contact Name | Jeremiah Connors |
| Contact E-mail | jeremiah.connors@phila.gov |
| Contents | Records of parking violations in the City of Philadelphia, issued by the Philadelphia Parking Authority, Police Department, and more. Information includes ticket number, license plate number, state of registration (PA, NJ, etc), date and time the violation was written, along with the type of violation, and hundred block of location.|
| Date Range | 2011-2015 |
| System of Record | BAA Xerox Database |
| Format | DB |
| Contains Sensitive Data	| Yes |
| Sensitive Data Comments	| License plate numbers are sensitive information. |
| Update Frequency | Other |
| Coordinate System	| GCS_WGS_1984, Decimal Degree |
| Data Hygiene | 5 - Very High |
| Data Accuracy | 5 - Very High |
| Demand | 5 |
| Complexity | 5 |


Representations
---------------------

|Name|Description|Development Process|Thematic Mapping|Coordinate System|Date Range|ETL File Name|Update Frequency|Classification|Status|Endpoints|Details|
|:----|:-------------------|:------------|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Parking Violations |	Locations, date/time, and more regarding parking violations issued in the City of Philadelphia with license plate information anonymized for privacy | Locations are provided at the hundred block level | Extract provided from Xerox. | License plate information anonymized by Andrey Mun. Locations geocoded by Robert Martin. |	GCS_WGS_1984, Decimal Degree | January 2012 through March 2015 | Archive | Public	| In Development | [view](https://phl.knackhq.com/inventory#home/datasetdetails/5543865c20583086178c4eda/representationdetails/5565fec41e1c191b0dbd5684)

Fields
--------------------------

|Alias|Sensitive|Description|Type|
|:----|:-------------------|:------------|:------------|
Division|	No | Police district of issuing police officer (empty when issued by PPA) | Text |
Fine|	No | Fine amount for the violation. |	Text |
Issue Date and Time	|No	|Date and time the violation was written.	|Date/Time	|
Issuing Agency|	No|	The agency that issued the violation.	|Text	|
State	|No	|State in which the vehicle is registered.	|Text	|
Location|	No|	Location at which the violation was written.	|Text	|
Location Standardized|	No|	Parsed and standardized location	|Text	|
Plate ID|	No|	Anonymized identifier for the license plate number.	|Number	|
Violation Description|	No|	Short description of the type of violation that occurred.	|Text |

