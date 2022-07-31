# cs416_data_visualization

#  Objective of the visualization:

In this Project I am aiming to provide narrative around how much of an impact does urbanization of a country have on GDP growth which is finally leading to deforestation. As result of urbanization there is a inorganic increase in cities area and hence increase in deforestation. This phenomenon if left unchecked will be very harmful on the environment and will lead to further increase in pollution in certain or all parts of the country.


# Narrative Structure:

I am following Interactive Slideshow structure by providing viewers ability to self-navigate through different pages, drill down the details if needed. And using different graphs and charts understand the influence of urbanization on different critical indexes like GDP, Population and loss of forests.

Visual Structure:
The visual structure for this article is based on web pages shown as scenes. A visual consistency is maintained by using same kind of template and layout in each page of the report. In order to set-up context for visualization title and brief description is placed above each visualization. Same type of visualization container chart is used with height 520px and breadth of 990px, a consistency in text color is maintained, though different graphs are used as per the requirement and which best suits to visualize data. Interconnected scenes are designed in story telling structure to keep the view engaged and avoid any disorientation in between pages.  

# Scenes:

I this narrative visualization I am using 4 web pages 1 for each scene.
First page is used to give the overall context of the project. On this page heading of the report is provided and paragraph is used to set the context along with a scatterplot which show urban area % vs GDP for different countries used in the dataset. Navigation URL links are provided for each page which user can click as per the curiosity. First page leads to 3 different pages. Below is the navigation details:
Page 1 urban area % vs GDP leads to next page or to the conclusion page can also be clicked.
Page 2 Answers the question set-up in the heading using the line chart which show correlation between urbanization and de-forestation. This leads to third page.
page 3 Shows the increase in urban population in past years for each of the country in the data set. A bar chart visualization is put into place for better representation of data. Start again and next page buttons are provided on this page
page 4 This is the final page of the report which shows how big is urban area in each of the country. It also acts as a conclusion page for this report. 


# Annotations:

Annotations are used to focus on tendencies in information, direct customers to discover the information further, and inspire customers to attract conclusions from the information. Annotations use a consistent font length template and bold style.
Annotation in page 1 (Scatter Plot - GDP and Cities) are text placed in the visualization container to emphasize the main results of the visualization.
"With increase of GDP there is direct increase in urban area" When the user clicks (next page) hyperlink to go to the second page containing (second scene), the annotations on the first page disappear. 
The annotation on page 2 (deforestation increases as urbanization progresses) is a text placed inside a visualization container to emphasize ("Most developed countries have higher urban areas". ). When the user clicks a button to go to Scene 1 or go to Scene 3, the Scene 2 annotation is removed.
The annotation in page 3 (Urban area population tend to increase with time) is text positioned inside the visualization container meant to highlight increase in urban population. User can mouse over the bar chart to get information like country name and percentage increase for each of the country in bar chart
If the user clicks a button to go back to scene 1 or scene 2, the annotation for scene 3 is cleared.
The final page 4 starts with header "How big is the urban land area in various countries?" annotation shows "developed countries have higher urban Area".
Each page or scene also has a tooltip-style annotation that is displayed with the mouse pointer.

# Parameters:

The parameter used in this visualization is an embedded URL for navigating between slides. Click an embedded slide to switch to another scene or slide. Hover over a data point for a specific country to see that country's data point and visualization changes in a popup. This gives the user more information about the actual values under the visualization. This forms another set of parameters. Parameters are used to draw the user into the narrative visualization and further explore the data. 

# Triggers:

There are two ways in which I am using Triggers in this visualization. One is to navigate from one scene to another by "mouse clicking" through embedded web links. Another use is to show a popup when the mouse "hovers" over the chat bar in the bar or the circle in the scatterplot.


