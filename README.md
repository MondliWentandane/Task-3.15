# Task-3.15 : The Five V's



============================= Task 1  ===============

JSON data sample demonstrate data variety by have different kinds of data which are structured data according to the data we’ve ben give but you can also get unstructured data in some cases which can make it hard to handle that kind of data.
           Eg: Data values come in different formats:


 “16.6 C” (string with unit inside value) vs 17.1 (numeric).


  “False” (string instead of boolean).


The systems may experience overload of data and start to be slow as there would be jemed on the  accesspoint as they can’t fit in all at once.
The field represents the importance of data like how reliable or valuable it could be
            With s low score it has, it means that data is not really reliable.                         
            A record with  -10 under type: “Air quality” is the one that might be a problem in this                     case
The processing can be very slow and company might be having low storage devices.
This data enables real-time decision making for the city:
Use case: Detecting traffic congestion to dynamically reroute vehicles and adjust traffic lights, reducing travel time and emissions for Germiston citizens.

====================  Task 2  ===================

Data quality refers to how accurate, consistent, complete, and reliable data is for its intended purpose.

b) Identified Issues
Issue
Description
Why It’s a Problem
 Inconsistent timestamp formats
Some timestamps use "29/07/2025" or "July 29 2025"
Breaks sorting, time-series analysis, and parsing logic
 Missing/Null values
e.g., value: null, type: null, veracity: null
Reduces trust and usefulness; may crash systems
 Invalid values
e.g., "value": -10 for AQI, or "16.2C" as string
Out-of-range or wrong type leads to misleading analytics



==================== Task 3  ===================

 {
 "sensor_id": "AQ-01-GER",
  "timestamp": "2025-07-29T08:45:10Z",
  "location": { "latitude": -26.2253, "longitude": 28.1613 },
  "data": { "type": "air_quality", "value": 45.5, "unit": "AQI" },
  "data_source_veracity": 0.95,
  "access_level": "Public"
}



b) Data Breach Implications
Loss of Competitive Advantage
 A rival logistics firm can optimize delivery routes better using your traffic data—hurting your clients or revenue.


Public Distrust & Legal Action
 Citizens and businesses may lose trust in the city’s ability to protect sensitive data, leading to lawsuits or regulatory penalties.

 3) 
The Data Governance Officer or Chief Data Officer (CDO) should be the one defining the      access   levels of the organisations now because Developers or project managers may implement rules, but defining who gets what access is a policy and compliance issue, not just a technical task. Another reason is because the governance requires accountability, privacy compliance (e.g., POPIA), and ethical use of data.

