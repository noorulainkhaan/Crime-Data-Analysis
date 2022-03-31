# Crime-Data-Analysis
This notebook is made to study the crime data of Chicago.
We will attempt to observe different patterns in the data and mathe following analytical assessments:

Single Class

Model 1 - Logistic regression with Lasso-based feature selection
Model 2 - Linear SVM
Model 3 - Decision Trees
Model 4 - Naive Bayes Model
Model 5 - Random Forest
Model 6 - KNN
Multi Class Models

Model 1 - Decision Trees for Multi Class
Model 2 - Random Forest for Multi Class
Model 3 - Logistic for Multi Class with Newton
Model 4 - Logistic for Multi Class with lbfgs
Other Models

Principal Component Analysis
Neural Networks
xgBoost
Complete Visualization

Feature Importance
Crimes per Location
Boxplot grouped by Location
Crimes by Time, Day, Month
Comparison of 4 Major Crime Times
Mapping the location of Crimes
Strategy
The way we will be carrying out various analytical tasks is by performing the following:

Data Cleaning: As you will see below the Chicago dataset is huge. The file we are currently using is 1.6GB and this increases everyday. However, there are some major issues with the data, some data is missing or incomplete, other data is not complete. So we will be cleaning up the data. We will also be using data for crimes from 2017 to 2019 only. We will ignore previous crime data.

Modelling the Data: We will use Single and MUlti Class techniques to see rank crimes based on severity. We will also compare the results of all these techniques to see how they compare to each other for both test and train.

Visualizing: We will visualize the data in different methods. It will help to understand the reults

Description of Data
Chicago Crime Dataset: This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days. Data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. In order to protect the privacy of crime victims, addresses are shown at the block level only and specific locations are not identified. Data Content is as follows:

ID - Unique identifier for the record.

Case Number - The Chicago Police Department RD Number (Records Division Number), which is unique to the incident.

Date - Date when the incident occurred. this is sometimes a best estimate.

Block - The partially redacted address where the incident occurred, placing it on the same block as the actual address.

IUCR - The Illinois Unifrom Crime Reporting code. This is directly linked to the Primary Type and Description. See the list of IUCR codes at https://data.cityofchicago.org/d/c7ck-438e.

Primary Type - The primary description of the IUCR code.

Description - The secondary description of the IUCR code, a subcategory of the primary description.

Location Description - Description of the location where the incident occurred.

Arrest - Indicates whether an arrest was made.

Domestic - Indicates whether the incident was domestic-related as defined by the Illinois Domestic Violence Act.

Beat - Indicates the beat where the incident occurred. A beat is the smallest police geographic area – each beat has a dedicated police beat car. Three to five beats make up a police sector, and three sectors make up a police district. The Chicago Police Department has 22 police districts. See the beats at https://data.cityofchicago.org/d/aerh-rz74.

District - Indicates the police district where the incident occurred. See the districts at https://data.cityofchicago.org/d/fthy-xz3r.

Ward - The ward (City Council district) where the incident occurred. See the wards at https://data.cityofchicago.org/d/sp34-6z76.

Community Area - Indicates the community area where the incident occurred. Chicago has 77 community areas. See the community areas at https://data.cityofchicago.org/d/cauq-8yn6.

FBI Code - Indicates the crime classification as outlined in the FBI's National Incident-Based Reporting System (NIBRS). See the Chicago Police Department listing of these classifications at http://gis.chicagopolice.org/clearmap_crime_sums/crime_types.html.

X Coordinate - The x coordinate of the location where the incident occurred in State Plane Illinois East NAD 1983 projection. This location is shifted from the actual location for partial redaction but falls on the same block.

Y Coordinate - The y coordinate of the location where the incident occurred in State Plane Illinois East NAD 1983 projection. This location is shifted from the actual location for partial redaction but falls on the same block.

Year - Year the incident occurred.

Updated On - Date and time the record was last updated.

Latitude - The latitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.

Longitude - The longitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.

Location - The location where the incident occurred in a format that allows for creation of maps and other geographic operations on this data portal. This location is shifted from the actual location for partial redaction but falls on the same block.
