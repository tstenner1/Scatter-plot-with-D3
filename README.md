# Data Journalism using D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

In this repository I am tasked with analyzing the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand my findings.

I execute this analysis with data from the [US Census Bureau](https://data.census.gov/cedsci/) and the Behavioral Risk Factor Surveillance Systemrelates to find the health risks facing particular demographics.  These risks include rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error.").

### Core Assignment: D3 Dabbler 

![4-scatter](Images/4-scatter.jpg)

First I create a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

Then using the D3 techniques, I then create a scatter plot that represents each state with circle elements.  Including: 

* State abbreviations in the circles.

* Create and situate axes and labels to the left and bottom of the chart.

### Bonus

Instead of just a static graphic I use D3 to make a graph that lets you interact with the data. (See gif below)

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Dynamics

I include more demographics and more risk factors. Placing additional labels in my scatter plot and giving them click events so that the users can decide which data to display. Animating the transitions for my circles' locations as well as the range of my axes is another dimension added to the graph. 

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to your circles and display each tooltip with the data that the user has selected. Use the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)—we've already included this plugin in your assignment directory.

![8-tooltip](Images/8-tooltip.gif)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
