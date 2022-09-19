# i310d

The goal of your project
Links to any relevant API documentation
The license of your data and any source data
A data type and description for each attribute in your data
Any known issues or potential issues, such as sources of bias in collection

Project Objective:
The primary goal of this analysis was to determine which US state has showcased the most incidents of 'police brutality'. For the purpose of this particular study, a case of police brutality is classified as a situation where the vicitm was unarmed, considered unthreatening, was not making any attempts to escape, and did not exhibit signs of mental illness, but was still killed during the incident. 

The data collected was found at the site linked below: 
https://www.kaggle.com/datasets/ramjasmaurya/us-police-shootings-from-20152022
The following data set is licensed in the public domain.

column_a (integer):         number of the entry

name (string):                       name of the victim 

armed (string):                      indicates whether or not the victim was armed or not

gender (string):                     gender of victim

race (string):                       race of victim

city (string):                       city in the US where the incident occurred

state (string):                      state in the US where the incident occurred

signs_of_mental_illness (boolean):    indicates if the victim showed signs of mental illness at the time of the incident

threat_level (string):               level of threat of the victim as determined by the police

flee (string):                       method of which the victim used to escape

Potential issues arise with this data set as the author has not listed a specific, retraceable source that I am able to access and review. This makes trusting the data more difficult, but nonetheless, the data traces to back to 2015 and has been updated monthly ever since. Additionally, under the 'threat_level' attribute, one of the data points recorded was 'other' which has ambiguous meaning and may be interpreted differently. The assumption I chose to make was that other indicated no threat or minimal threat as there are only three data points: other, attack, and undetermined.
