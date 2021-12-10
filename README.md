This is Call Analysis Project

General Information

New York City publishes a number of open datasets for public consumption or use. Amongst them is a dataset consisting of calls to the 311 phone number for non-emergency services. Each call to 311 has a number of datapoints tracked and aggregated.

Implementation

We used pandas.DataFrame to read this dataset firstly. In order to get what top 10 incident types in our living place, we set zip code to 11101 and then filtered top 10 causes of calls to 311 with their total number of incidents in the year 2020. Presented results in the form of pandas.Series at the end. A pie chart graph with top incidents plotted as well, for easily visualizing. In our result, the top 10 incidents surround us are Illegal Parking (2982), Noise-Residential (2030), Noise-Street/Side Walk (1220), Blocked Driveway (1034), Non-Emergency Police Matter (904), Street Condition (670), NonCompliance with Phased Reopening (649), Noise (608), Noise-Commercial (512), and Noise-Vehicle (374).
In the second Jupyter notebook called Parking.ipynb, we analyzed whether illegal parking incidents are a larger fraction of total 311 incidents in our living place than they are in general. Based on some data processings, We kept 11101 as our zip and then calculated the number of illegal parking incidents under ‘complaint type’, which there were 2982 illegal parking incidents. By comparing with total incidents, 17817 cases, in our place, the fraction we got was approximate 17%. Then, we looked at the global parking incident rate was around 7%. We concluded that illegal parking incidents are a larger fraction of total 311 incidents in our zip code than they are in general. 

Group 

Group 34 section 002

Uni: fl2595 gg2797ß
