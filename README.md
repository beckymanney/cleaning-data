### **Cleaning-Data**

 **1 - New York NYPD Complaint Data**
 
 FROM https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Current-Year-To-Date-/5uac-w243
 
This data set was made public on 11/1/2018.  It is updated quarterly but is not automated.

This is a subset of the data.

There are 109,544 rows of complaints with 36 columns describing the complaints.
I trimmed down to 65,000 rows for uploading.

In the cleaning,

- the blanks were switched to NULLS for easier importing to SQL  
- the dates were standardized  
- the offense descriptions were condensed since there was another column describing more detail of the offense  
- the misspellings corrected  
- spaces removed from text
- ages normalized

![This is an image](https://
