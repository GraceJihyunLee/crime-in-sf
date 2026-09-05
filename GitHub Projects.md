### **Data Visualization Project \- 2018 San Francisco Crime Analysis** 

### **San Francisco Crime Analysis (2018)**  
Exploring 2018 crime patterns across San Francisco (SF) to provide insights and inform public safety recommendations

### **1\. Project Overview**:

Crime report data is a powerful lens for understanding how a city functions day-to-day — where risk concentrates, when it spikes, and how effectively it's addressed. As a mid-cycle project for the COOP Careers Data Analyst Fellowship, I worked in a team of four to explore crime patterns across San Francisco in 2018 through exploratory analysis and data visualization. Using Excel for data cleaning and preparation and Tableau for visualization, we investigated how crime varied by neighborhood, time of day/year, and offense type, along with consistency of case resolution — producing a set of dashboards that make these patterns easy to explore and interpret at a glance.

### **2\. Objective**

Our objective was to analyze 2018 San Francisco crime data to understand underlying patterns — spatially, temporally, and by offense type — to inform recommendations on resource allocation and public safety planning.

### **3\. Dataset:**

*Source*: \[link\]

Originally sourced from the [City of San Francisco's public open data portal](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783/data_preview), the dataset was provided to us by COOP Careers as a consolidated version filtered to 2018 crime records only.

*Size/Scope*: The raw dataset contained 27 columns and 153,000+ rows. After data cleaning, this was refined to 120,000+ unique incident reports used for analysis.

### **4\. Methodology**

**Process Overview:** We first defined the business problem, then cleaned and transformed the data before moving into analysis and interpretation. From there, we developed possible recommendations based on our findings and presented them to conclude the project.

**Analysis Type & Techniques**  
 Exploratory Data Analysis (EDA) and data visualization, covering:

* **Crime type prominence** — ranking and comparing frequency of different offense categories *(team)*  
* **Spatial analysis** — mapping crime distribution across SF neighborhoods/districts *(my focus)*  
* **Temporal analysis** — identifying trends by time of day, day of week, and month *(my focus)*  
* **Case resolution analysis** — examining resolution/closure rates across crime types and areas *(team)*

**Data Considerations & Caveats**

While working with the dataset, we noted several limitations that shaped how we interpreted the results:

* **Location accuracy:** The reported location of an incident may not reflect the exact point or district where it occurred.  
* **Police district assignment:** District information is entered by the reporting officer and reflects where the officer is stationed, not necessarily the actual district in which the incident took place.  
* **Incomplete records:** Some reports are removed from the dataset in compliance with court orders sealing records, or for administrative reasons. As a result, not all incidents are represented in the dataset, in order to protect privacy.  
* **Duplicate incident IDs:** Incident ID/Incident Number is unique to a given report but can appear more than once in the dataset to represent one-to-many relationships.

**Tools Used:** Excel (data cleaning & preparation), Tableau (visualization)

### **5\. My Role**

I led the spatial and temporal analysis — mapping crime distribution across SF neighborhoods and police districts, and identifying trends by time of day, day of week, and month. I also helped oversee the project more broadly, staying closely involved in the crime-type and case-resolution work to support the team and fully grasp every part of the analysis.

### **6\. Key Findings**

Our analysis surfaced several clear patterns across crime type, timing, and location:

* **Larceny theft dominates:** Larceny theft accounted for 38.5% of all reported incidents — far exceeding every other crime category — with "Larceny Theft – From Vehicles" making up the largest share within that category.  
* **Seasonal and weekly patterns:** Incidents peaked during the summer months, with August recording the highest volume, and Fridays consistently seeing the most activity.  
* **Time-of-day patterns:** Crime was most frequent during midday (12–1 PM) and early evening (6–7 PM).  
* **Geographic concentration:** Mission and Financial/South Beach neighborhoods emerged as major hotspots. Mission alone accounted for 13,916 incidents, the highest of any neighborhood. Additionally, Northern SF neighborhoods showed a disproportionately high rate of larceny theft relative to the rest of the city.  
* **Reporting concentration:** The Central Police District recorded the highest share of incidents.  
* **Low resolution rate:** 84% of cases remained open or unresolved, with only 15% resolved through citation or arrest, highlighting a gap between reported incidents and enforcement outcomes.

#### **6a. Possible Explanations *(interpretation, not directly tested by the data)***

While the dataset shows clear patterns in crime type, timing, and location, it doesn't tell us *why* those patterns exist. The following are reasonable hypotheses based on outside context about SF, rather than conclusions drawn directly from the data.

* Larceny theft's dominance, particularly theft from vehicles, may be tied to SF's high number of total on-street parking spaces relative to its small geographic size, which leaves vehicles more exposed and accessible to theft.   
* Friday's spike in incidents may reflect the start of the weekend, when social activity, nightlife, and foot traffic typically increase across the city.   
* High crime frequency during midday and early evening aligns with typical lunch and dinner hours, which tend to bring higher foot traffic.   
* Geographically, the Mission's status as the top hotspot is consistent with its high population density and status as one of SF's active nightlife and commercial corridors — conditions that tend to bring more people, transactions, and property into a concentrated area, and with that, more opportunity for crime.

### **7\. Visuals**

### **8\. Conclusion / Recommendations**

Larceny theft emerged as the dominant crime category in this dataset, confirming that property-related crime is the primary public safety concern in San Francisco. Incidents peaked in August, with Fridays being the most active day of the week, and activity concentrated around 12–1 PM and 6–7 PM. Geographically, the Mission neighborhood stood out as the top hotspot, while Northern SF neighborhoods showed a disproportionate rate of larceny theft. Lastly, with 84% of cases still open or unresolved, the data also points to a meaningful gap in enforcement capacity.

Based on these findings, we recommended:

* Increasing police presence in high-crime neighborhoods, particularly in Northern San Francisco  
* Strengthening community watch programs in high-volume crime areas  
* Scaling penalties to match crime severity to improve fairness and discourage repeat offenses  
* Collecting more detailed data on victims and offenders to better identify patterns and support systematic crime prevention

### **9\. Links**

