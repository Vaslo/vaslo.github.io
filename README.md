# CS498 - Final Project Writeup
## Purpose of Visualization
This visualization project is meant to show the viewer information about Imports/Exports of major trading countries around the globe.  The visualization begins with a view of the world with highlights on the trade volume (total imports + exports) in 2016.  Gradually is pulled through a narrative where they are shown how few countries control the volume of trade.  They are next shown Net exports, and see that some heavy trade companies are Trade Surplus or Deficit.  At the end, they are able to pull down bars to see the top 5 items that each country exports

## Hybrid Structure
This visualizaton tries best to follow a Martini glass structure.  The first few slides take the viewer through a story where they are taught about the structure of the import/export business across the globe.  After following the story, they can click on a dropdown which allows them to see what the top 5 exports for each country are.  

## Scenes
As discussed, the scenes utilize several methods. First, the majority of the story of the visualization uses different views of the same world map to convey how concentrated global trade is in less than a dozen countries.  Then, the user can choose a selection by country to see the value of the top trade items for those individual countries.  To not go too crazy on scope, we only use 10 countries for the individual export choices.  The users are walked through the choices via the links at the bottom of the page - one to return to the previous slide, the second to take them to the next step in the story by posing a question.

## Use of Annotations
Annotations are used quite extensively in the map tabs.  Each annotation draws the reader's view to the countries being discussed as well as the values which correspond to that country. The final slide labels the tabs to show the amount in billions of the top traded items.

## Parameters
The Visualization uses several parameters.  A simple Forward button drives the user to complete the visualization.  The final slide uses a dropdown to change the country to observe the exports of the given country of choice by the user.

## Future work
In future versions I'd like to:
* Make the countries clickable with a bunch of information available upon click.  I simply couldn't figure out how to do something that advanced despite looking at dozens of examples.
* I'd like to add ALL country exports and imports.
* Add additional years as a choice.
* Better transitions between the global slides showing the change more seamless.
