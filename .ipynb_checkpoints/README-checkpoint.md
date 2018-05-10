# inpatient_payment_data

In this project I explore nationwide data on payment data by provider (provider = hospital) for inpatient stays.  We first group them by DRGs (diagnose-related groups) and examine the most expensive, most variable in cost, and most common DRGs.  We then combine the data by region and use the data in *zipcode.csv* to map zipcodes to longitude/latitude to map the average cost of an inpatient stay by region and show that it correlates with high cost-of-living areas

Data is contained in the following files located in the "data" folder
* zipcodes.csv: maps zipcodes to latitudes and longitudes
* Inpatient_Prospective_Payment_System__IPPS__Provider_Summary_for_the_Top_100_Diagnosis-Related_Groups__DRG__-_FY2011.csv: data from data.gov on payment data for inpatient stays

***Note: for overview of methodology see Medicare_Hospital_Inpatient_PUF_Methodology_2017-08-30.pdf in the data folder***