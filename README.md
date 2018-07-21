# The-Gender-Gap-In-College-Degrees
Leveraging the capabilities of Pandas and Matplotlib, we generate line charts to compare the gender disparities across various degrees awarded to graduates in various majors between 1968-2011. The primary focus of this project is on plotting aesthetics.

## The Dataset In Focus
The data we're working with is from [The Department of Education Statistics's](https://nces.ed.gov/programs/digest/2013menu_tables.asp) annually released dataset. It contains the percentage of bachelor's degrees granted to women from 1970 to 2012. The data set is broken up into 17 categories of degrees, with each column as a separate category.

Randal Olson, a data scientist at University of Pennsylvania, has cleaned the data set and made it available on his personal website, which can be found here [here](http://www.randalolson.com/wp-content/uploads/percent-bachelors-degrees-women-usa.csv). He compiled this data set to explore the gender gap in STEM fields, which stands for science, technology, engineering, and mathematics. You may have come across this subject as it is [reported on often in the news](https://www.google.com/search?hl=en&gl=us&tbm=nws&authuser=0&q=gender+gap+stem&oq=gender+gap+stem&gs_l=news), however, [the jury is still out on this one](https://www.pbs.org/newshour/economy/making-sense/truth-women-stem-careers).

In this project, we make a humble attempt to effectively communicate this nuanced narrative of gender gap using data visualization techniques. We are simply going to look at the number of women in various majors between 1968-2011. We will then plot our findings to see if there are majors with less women than others. 

## Python concepts explored: 
pandas, matplotlib, histograms, line plots, chart graphics

## Python functions and methods used: 
.savefig(), .text(), .axhline(), .set_yticks(), .tick_params(), .set_title(), .set_ylim(), .set_xlim(), .spines(), .tick_params()


*This project was a part of my Data Scientist Course from [Dataquest](https://www.dataquest.io/)*
