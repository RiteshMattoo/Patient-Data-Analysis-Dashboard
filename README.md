#Patient Data Analysis using PowerBi Dashboard

##Prject Overview
This Power BI dashboard provides an interactive analysis of patient visits across various hospital departments. It helps visualize total patients, busiest departments, age distribution, and patient visit trends over time.

##Key Features
 Total Patients – Displays the total number of patient visits.
 
  1 Busiest Department – Identifies which department receives the most patients.
  
  2 Patient Visits Over Time – Tracks visits using a line chart.
  
  3 Age Distribution – Analyzes patient age groups using a pie chart.
  
  4 Department-wise Analysis – Shows patient distribution per department using a bar chart.
  
  5 Slicers & Filters – Allows filtering by department and date range.

##Dataset Used

1 Patient Data (Contains patient name, visit date & time, department ID, and age).

2 Department Data (Maps department ID to department name and Head of Department).

##Data Processing Steps

1 Merged Patient Data and Department Data using Left Outer Join.

2 Renamed columns (deptt → Department ID, dt → DateTime).

3 Created a relationship between tables using Department ID.

4 Added calculated columns to format DateTime into hh:mm AM/PM.

##Visuals Used

1 Card Visual → Total Patients

2 Bar Chart → Patients by Department

3 Pie Chart → Age Distribution

4 Line Chart → Patient Visits Over Time

5 Slicers → Department filter and Date range filter

##Final Conclusion

The Patient Data Analysis Dashboard provides key insights into hospital operations, helping in resource allocation, staff management, and patient care optimization. It identifies the busiest department, tracks patient visit trends, and analyzes age distribution for better healthcare planning. Interactive filters and slicers make data exploration easier, enabling data-driven decision-making for hospital

