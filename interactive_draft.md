# Hate Map: An interactive study of hate crimes in the U.S.

Echo Nattinger

## What is your current goal? Has it changed since the proposal?
My goal has remained mostly the same since the proposal -- the only thing that's changed is instead of having multiple drop-down windows, I am focusing on one (for hate crime bias). I found introducing multiple drop-downs was distracting from the main purpose, which is 
studying how different forms of hate are prevalent across the U.S.

## Are there data challenges you are facing? Are you currently depending on mock data?
I am using real data from the FBI. It was difficult figuring out how to "filter" the dataset in JS, so I instead am using multiple pre-filtered .CSVs (the drop-down menu controls which .CSV is loaded). 

One thing I'm a little concerned about is how I currently create the legend. The legend always starts at 0, and ends at the maximum crime rate in the selected .csv. Originally I implemented this with a max() function in JS, but this was throwing lots of weird numbers
whenever the dataset changed. So, for now, I've hard-coded the various maximum values into a JS object. Ideally, I figure out how to implement this without magic numbers. 

## Walk us through an interaction, either in words or you can record a quick 2-3 minute video.
Under the text box "Select Type of Hate Crime", there is a dropdown box that allows you to filter the dataset by hate crime bias (e.g., Anti-Black crime). Select one of the options in the dropdown box to choose which type of crime you'd like to learn about. Once a hate crime bias 
is selected, the map will update to show the prevalence of that type of crime across the U.S. You can click on a state to learn about that state's rate of the selected crime; information will populate in the "Description of Data" box to the right of the map. 

Note that the map includes information for all years (1991-2023).

## Include a _numbered_ list of questions for us to respond to.
Questions included in 30239 Interactive Critique Google form. 
