### Cleaning-Data

 1 - New York NYPD Complaint Data
 
 FROM https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Current-Year-To-Date-/5uac-w243
 
This data set was made public on 11/1/2018.  It is updated quartly but is not automated.

This is a subset of the data.

There are 109,544 rows of complaints with 36 columns describing the complaints.

In the cleaning, 

    A. the blanks were switched to NULLS for easier importing to SQL  
    B. the dates were standarized  
    C. the offense desciptions were condensed since there was another column describing more detail of the offense  
    D. the misspellings corrected  
    E. spaces removed from text
    F. ages normalized
