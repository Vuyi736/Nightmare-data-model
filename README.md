## Nightmare-data-model
Turning a chaotic data model into a clean star schema view that improves the workflow for better and fast analysis.

## Project Overview
This project aims to turn a nightmare data model into a clean and clear model that has a star schema view with central fact tables connected to dimension tables, dimensions that connect two or more fact tables and clear relationships between tables. The main point is emphasizing how a good data model can make work easier with low chances for outputting wrong numbers. A good data model will handle new data that is added to the database without chaos due to the rules put in place when making it and most importantly, security is guaranteed when put in place.

## Process
- Data loading and walkthrough to understand the grain and decide which data is junk and which is useful.
- Establish rules on casing (snake casing was chosen for column titles, Proper casing for cell contents), suffixes (e.g. table.key), prefixes (e.g. fact.table) and the like.
- Best practice before work begins is to make a duplicate folder containing the files to be worked on for the sake of counterchecking in case of mistakes or data loss. This we did.
- Then create other folders for fact tables and dimension tables as well as supporting tables. Please note that all these actions depend on the nature of the data.
-  We removed all the 'ill' relationships to make room for the good relationships we made.
-  The first table to be worked on was the dim.customer table. Best practice is to have one place for a type of data, e.g., customer_names should only appear in dim.customer. it must be understood that [Baraa Salkini](www.youtube.com/@DataWithBaraa) explains dimensions as definitions of events that happen in a business while facts are the events themselves. Thus, an order is an event.
-  And so, 23 table at the beginning;
  
<img width="862" height="217" alt="Nightmare shot" src="https://github.com/user-attachments/assets/d2e10e64-61f9-4aa3-b674-2c9628781c7a" />

- And the result;

  <img width="836" height="334" alt="Good model" src="https://github.com/user-attachments/assets/765f3f73-b3be-4564-8e3f-5e94e50c51b9" />

## Tools Used
Power BI (Power Query)

Many thanks to Baraa Salkini for his comprehensive teaching!

## References
Salkini, B. K.(2026). Nightmare data modelling. YouTube. Retrieved from https://www.youtube.com/@DataWithBaraa

