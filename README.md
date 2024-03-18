# Final-Project-Tableau

## Project/Goals
This is my Tableau project where I have demonstrated my ability to make map diagrams, bar charts, pie charts, scatterplots, and line graphs in Tableau. I have also demonstrated my ability to organize my Tableau sheets into dashboards and my dashboards into a story.

I picked option 2 and used the World Health Organization's dataset on the Tuberculosis Burden around the world analyzed by country and region data

## Process

Step 1:
The latest year of the dataset was 2013. The first stage of my project was to prepare figures that provide country and region comparison of the tuberculosis problem around the world in this year. I prepared map figures that display the prevelence and mortality rate of tuberculosis around the world. I also prepared maps that show the total cases and deaths in absolute numbers, which unsurprisingly highlighted India as the country with the most cases and deaths. As well as bar graphs and pie graphs that show the rate of revelence and mortality from tuberculosis in the various regions of the world. I also made a scatterplot of the countries of the world which showed both the prevelence and mortality of tuberculosis in every country in the world. And I picked the two countries with the most severe tuberculosis problem to make line graphs for.

Step 2:
I made line graphs illustrating the tuberculosis problem in two countries that I judged to have the worst tuberculosis problem in 2013 based on the scatterplot data. These countries were Lesotho and Swaziland. These graphs have a blue line showing the estimate as well as a orange shaded area showing the high and low bounds of the estimates.

Step 3:
The graphics I made in step 1 clearly showed that Africa was the region of the world that had the worst tuberculosis problem. So I decided to process my data further so I could make graphs about Africa. Using Python in VSCode I made edited versions of my CSV files that had data on the continent of Africa as a whole, including tuberculosis prevelence and mortality. This data was weighted appropriately by the various populations of the countries so that it could be applied to the entire continent. While making these CSV files I included several countries that the World Health Organization Dataset catagorized as "Eastern Mediterranean" as opposed to "African". This  included the countries of Egypt, Djibouti, Libya, Morocco, Sudan, Somalia, and Tunisia.

I also made a separate CSV specifically for Subsaharan Africa which excluded the North African countries of Morocco, Algeria, Tunisia, Libya, and Egypt, as this region of Africa is often considered more developed than the rest of Africa so I considered it worth examining if excluding this region would reveal a worse tuberculosis problem when this region was included.

Step 4:
I made line graphs illustrating the prevelence and mortality of Africa and Subsaharan Africa as a whole similar for how I did with Lesotho and Swaziland individually.

Step 5:
I organized all the pages I made into a Tableau Story.


## Results
It was found that most tuberculosis cases and death occur in Africa and India, which Africa having the highest tuberculosis deaths and prevelence overall. I judged Swaziland and Lesotho, two small, poor, countries near each other, to have the world's worst tuberculosis problem due to their exceptionally high tuberculosis mortality rate. Other countries with very bad tuberculosis problems include Dijibouti, Timor-Leste, Kiribati, Cambodia, South Africa, Namibia, and Mozambique. Timor-Leste appears to have the worst tuberculosis outside of Africa. The prevelence and mortality of tuberculosis appeared to increase in Swaziland from 1990 to 2013. The tuberculosis mortality rate in Lesotho increased from 1990 to 2005 but has been decreasing ever since. Overall there was a slow but noteworthy decrease in the prevelence and mortality rate of tuberculosis in Africa and Subsaharan Africa from 1990 to 2013. However these estimates have wide bounds so there's no way to make a statistically confident conclusion.

## Challenges 
I had trouble making forcasts in the line graphs for the prevelence and mortality of tuberculosis in Lesotho and Swaziland, as well as for Africa and Subsaharan Africa. Trying to add forcasts always broke my colour scheme. I was unable to find a way to fix it so I left the forcasts off.

I was unable to find a way to include a pie chart on tuberculosis deaths by region by simple adding in the relevant sheet without the formatting becoming buggy. I ended up copy pasting the chart into powerpoint, inserting a new title above it, and saving the image, and importing that image.

## Future Goals
I would like to find a way to fix forcasts in my line chart so I could include them.

If I could get data on tuberculosis in India that breaks it down by state and territories I would like to analyze regional disparties in the prevelence and mortality of tuberculosis in India.
