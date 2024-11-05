## Name
Echo Nattinger

## Data Description
I plan to use the same data I used for my static visualization project.

[FBI's Hate Crime Dataset](https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/downloads)
  - Specifically found all the way under Additional Datasets>Hate Crime>Download.
  - This dataset includes all the FBI's incidences of hate crimes from 1991-2023
   - 253,777 rows/observations total (1 row = 1 crime)
   - 28 columns, each reprsenting a different piece of information about the crime (type of offense, date, state, etc.)
     
## Example Visualizations
I want to pursue project Option A, as I want to grow familiar with D3 and JavaScript. Specifically, I envision creating an interactive chloropleth map of the United States that allows users to study rates of hate crimes by state. I want to include various selection menus that will manipulate the data through user input (selecting years, types of crimes, etc.). There are a couple of example maps that demonstrate my general idea:

1) [Interactive Map: US Abortion Policies and Access After Roe](https://states.guttmacher.org/policies/)
  - This map by Gutthmacher Institute shows the current state of abortion policies in the United States.
  - In addition to the major map, a "Choose Policy" button allows the user to select specific policies of interest, at which point the page generates a new map focusing on states with(out) the selected policy.
  - Additionally, if a user selects a specific state, the page generates a text window with summary information on the state's abortion access.
  - I see myself building something similar -- a U.S. map colored by intensity of hate crimes, allowing for user manipulation through selection boxes. I also like the fact that the page generates a text box with information written in text, I might think about implementing something similar in my map.
  - I believe this approach fits best with project Option A.
2) [Interactive Crime Maps | ADT](https://www.adt.com/crime)
  - This map by ADT visualizes rates of crime across the states (it also allows for visualization by county, but I don't have that level of geographic granularity in my data).
  - There's a filter for type of crime, and upon user selection, the map updates.
  - This is a great example of what I'd like to implement. I see myself using more selection boxes -- for type of crime, type of bias, and year. I could set up a filtering script that takes the user inputs from the selection boxes, filters the underlying Pandas dataframe approriately, and then visualizes it.
  - I believe this approach fits best with project Option A.
    
## Mock-Up
![image](https://github.com/user-attachments/assets/0f57ff19-cdea-4109-b626-1541ea1be629)

This is a rough idea of what the interactive will look like -- a main map on a web page, along with drop-down select menus that allow for data manipulation by the user. I'm toying with the idea of including a text-box summary, which is included in this image.

## Questions
None at this time
