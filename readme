# Refugee crisis visualisation With D3
#### Mohd Hassaan

### **Summary**

Refugee Crisis is one of the biggest cirsis in the current times. In this visualisation I tried to show the story of Refugees from every part of the world from 1975 to 2016. In this project I covered both the aspects, the influx of refugees to the countries also the fleeing rate of people from their home lands. I tried to explain how serious the problem is and it get worse and worse in the successive years.

**NOTE:** The data is huge So it is taking a while to get processed, I have tried a lot to make it as faster as possible but data may take atmost a minute to process.

### **Data**

  * Data for the refugees are taken from [UN Website](http://data.un.org/Data.aspx?d=UNHCR&f=indID%3AType-Ref)
  * Data for the world Map is taken from the Udacity World Cup example file **world_countries.json**

### **Design**

**Visualisation Type:** Initially in the first two iteration of my development I used the Pure **Martini Glass Visualisation**. But In the final piece of the project I enable the viewer to manipulate(or not) the visualisation right from the starting. If not then it works as the **martini glass visualisation**. Other wise it is a **viewer driven martini glass visualisation**. 

#### First Iteration (Refugee_1.html):  
  * Showing the refugees fleeing from their home land(home country) for each year in the form of a circle over each country.
  * The bigger the size of circle the more refugees fleeing from that country.
  * You can see the actual no people fleeing as refugee by hovering over the circle. 
  * After all the refugees fleeing from 1975 to 2016 has been shown, the viewer can select the years of his/her choice to navigate.
  
#### Second Iteration (Refugee_2.html):  
  * **Mode**: these are of two types. In one mode we can see the people fleeing the country. In other we can see the people arriving in a country as a refugee.
  * Two buttons is bieng added allowing user to change the mode(Fleeing or Arriving). Different colors is being assigned to both modes to make the differnce.
  * Most of the countries in the **Refugee Data** not matches with the **geo json** data due to different name of the same countries. A dictionary is being created to map the name of countries of the **refugee data** to the **geo json** data.  
  * Rest unmatched countries circles is being removed as they were appearing at the upper left corner of the SVG.

#### Third(Final) Iteration (Index.html):

  * A play Pause Button is added to start the story from 1975 which will end at 2016 and then reset.
  * Functionality of Zooming in to a country is being added which can be enabled/disabled by the button which is being added at top right corner of the page.
  * To select the country by mouse which are completely covered by Bubbles, we set the fill property of color to **none** which converts the bubbles in to a ring like structure which enable us to select the countries.
  * A new fucntionaly of showing the migration path between the countries on selecting a country is added.
  * How many people flee to particular country, or how many taking refuge from a particular country(depends on in which mode you are in) can be seen on a tool tip on hovering over the migration path.
  * Color combination is beign changed to give a better look. 
  * As data is taking too much time to shape, a loading icon is being added. 

### **Feedbacks**

The following list of feedbacks is based on the four people I have shown this project to.

 * Along with the fleeing data, it should also show the data of arriving of refugees.
 * Buttons should be added to choose which type of data viewer wanna see.
 * Majority of the countries are not appearing because of the name mismatch. A mapping dictionary should be drawn to fix that.
 * Zooming fnunctionality should be added as most of the bubbles are too small to get the tooltip.
 * Migration Path should be drawn between countries on selecting a country in both modes which on hover can show the information like for eg. how many countries fleeing to which country or how many are taking refuge from which country.
 * A play pause button should be added to make the story a little viewer specific.
 * As data is taking too much time to shape, attach a loading icon.
 * Change the color combination into an attractive one.
 
 ### **Resources**
 
 * Udacity Data visualisation World cup attendance example.
 * [Zooming Functionality](https://bl.ocks.org/mbostock/4699541)
 * [Differrent shapes in css](https://www.codeproject.com/Tips/1022374/Square-Circle-Ring-Oh-and-That-Smiley)
 * [Loading spinner](https://spin.js.org/)
 * [The Refugee Project](http://www.therefugeeproject.org/#/2009/CHN)
 * [How to make a line](https://gis.stackexchange.com/questions/26190/how-we-create-line-between-two-cordinates-on-polymap)
 
