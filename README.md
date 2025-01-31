Aaron Graff, Trevor Chartier, and Jackson Patrick

Our team decided to investigate avalanche data in Colorado for a few reasons. We all enjoy skiing and spending time in the mountains, and unfortunately, avalanches are an inherent risk involved. As a result, we all found the topic of analyzing avalanche frequencies and trends to be interesting. Avalanches are a complex phenomenon and their causes are numerous. Experts and snow scientists spend many years of their lives learning what conditions correlate to high avalanche dangers, and what conditions and areas are relatively safe. We want to dig into the data and figure out for ourselves what factors and regions correlate to high avalanche danger in Colorado. The public availability of avalanche and weather data additionally encouraged our pursuit of this analysis.

The Colorado Avalanche Information Center (CAIC) keeps detailed public records regarding avalanche reports going back to 2010. The dataset can be found at (https://avalanche.state.co.us/observations/avalanches). Given user-specified parameters such as date range and area, the website generates avalanche report data that can be downloaded as a csv file. The data includes a row for every avalanche report, and relevant columns to our analysis include date, area, elevation (relative to tree-line), slope aspect (N ,NE, E,etc.), and trigger. Additional features are included in the dataset regarding avalanche type and size, but we are unlikely to focus on these factors in the current work. This dataset will allow us to extract frequencies of avalanches over time, across different areas, and for various geographic features. Additionally, we will add Colorado weather data to inform our findings about avalanche frequencies.
 
In addition to the main avalanche dataset that we will be analyzing, we are also going to include SNOTEL weather data from the USDA Natural Resource Conservation Service (NWCC Report Generator (usda.gov). Around the country, there are over 900 SNOTEL stations in 11 states that track snow-water content, air temperature, and accumulated precipitation in areas that are generally remote and mountainous. Specifically in Colorado, there are many stations throughout the Rocky Mountain region that record this data, going back several decades depending on the station being observed.  As we work through our exploratory analysis of the avalanche data, our goal is to pick one region that has a curiously large number of avalanches in the last few years, and another region that has very few avalanche incidents during that time.  Once we have identified these patterns, we will generate a report (as a CSV file) of the SNOTEL data from stations near these avalanche zones to see if there is any correlation in air temperature, snow depth, snow-water equivalent percentage of average, or some other factor from the dataset that might be influencing these patterns. The data that is represented as a percentage of the average will be particularly interesting because it allows us to examine snowpack levels relative to the norm. For example, in a year of extreme drought, one might expect avalanche frequency to be lower because that year was so much of an anomaly.

 
Questions to be Addressed

What are the trends of naturally and artificially triggered avalanche frequencies over the last 14 years?

How do these trends compare with weather trends in CO?

To what extent are natural processes responsible for causing avalanches?

How do different geographical features impact avalanche frequency and danger?

What are the most, and least dangerous avalanche areas in Colorado?

Are there characteristics about the weather patterns in these areas that make them more or less susceptible to avalanches?

