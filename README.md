# Mystery Planet
Project Introduction: Identifying a Mystery Planet Using Space Weather Data
 
As part of a NASA data simulation, this project focuses on solving a planetary mystery by analyzing real atmospheric and climate measurements collected from an unknown planet in our solar system. The dataset—planet_weather.csv—includes daily environmental observations such as temperature, atmospheric pressure, wind speed, and atmospheric opacity, recorded over several planetary years. However, the identity of the planet is concealed.
The goal is to use data science techniques to uncover which planet the dataset represents. By exploring seasonal patterns, temperature ranges, pressure cycles, and the duration of a planetary year (in Earth days), we can compare these characteristics with known planetary profiles to determine the closest match.
This kind of analysis mirrors real planetary science workflows, where researchers use remote sensing data to understand atmospheric behavior and climate cycles across different celestial bodies.
________________________________________
Project Introduction: Identifying a Mystery Planet Using Space Weather Data
As part of a NASA data internship simulation, this project focuses on solving a planetary mystery by analyzing real atmospheric and climate measurements collected from an unknown planet in our solar system. The dataset—planet_weather.csv—includes daily environmental observations such as temperature, atmospheric pressure, wind speed, and atmospheric opacity, recorded over several planetary years. However, the identity of the planet is concealed.
The goal is to use data science techniques to uncover which planet the dataset represents. By exploring seasonal patterns, temperature ranges, pressure cycles, and the duration of a planetary year (in Earth days), we can compare these characteristics with known planetary profiles to determine the closest match.
This kind of analysis mirrors real planetary science workflows, where researchers use remote sensing data to understand atmospheric behavior and climate cycles across different celestial bodies.
Methodology for Space Data Analysis
To identify the mystery planet, the project follows a structured analytical approach commonly used in planetary data science:
1. Data Loading and Inspection
•	Import the dataset using pandas to preview its structure.
•	Inspect column types, missing values, time coverage, and statistically summarize the variables.
•	Verify the date formats and ensure consistency in numeric fields.
2. Data Cleaning
•	Handle missing or erroneous values in temperature, pressure, or wind data.
•	Convert date fields into usable datetime objects.
•	Ensure correct sorting of observations by terrestrial date and by sol (planetary day).
3. Exploratory Data Analysis (EDA)
Perform descriptive analysis to understand key characteristics of the planet:
•	Count the number of planetary months recorded.
•	Calculate average minimum daily temperature, atmospheric pressure, and wind speed per month.
•	Identify seasonal patterns using the solar longitude (ls) field.
•	Evaluate atmospheric opacity to understand storm conditions.
 
4. Visualization
Use Plotly Express to generate interactive visualizations:
•	Bar charts showing average temperature and pressure per month.
•	Line charts displaying daily pressure and daily minimum temperature across time.
•	Visual identification of peaks and cycles in climate variables.
These visual patterns help estimate:
•	How long one planetary year lasts in Earth days.
•	How many months or seasonal divisions exist.
•	The behavior of atmospheric pressure cycles.
5. Planet Identification Through Comparative Analysis
Using insights from the EDA and NASA’s reference data:
•	Compare estimated planetary year length, temperature ranges, and pressure patterns with known planets.
•	Validate findings using NASA’s planetary facts (e.g., Venus = 225 Earth days per year).
•	The mystery planet: Venus. 

A day on Venus is much longer than its year, lasting about 243 Earth days because it rotates extremely slowly and in the opposite direction from most other planets.
 
 
