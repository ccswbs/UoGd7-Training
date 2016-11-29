# Embedded Google Maps

In order to put an embedded google map into your website, you must ensire the following:
  - The map does not create a keyboard trap.
  - The map has a title attribute.
  - There is descriptive text before/after the map that details the important information relayed in the map.
  
  ## Avoiding Keyboard Traps
  To determine if your map has created a keyboard trap, you must test the map. This can be done by pressing the tab button on your keyboard and watching tab focus go town the page. If you are able to tab out of the map, the map is not a keyboard trap.
  
  ## Google Map Text Alternatives
  Allong with the map there should be explanations of the key points the map is trying to relay.
  
  General Use Cases for an Embedded Google Map:
  - Location/directions to a building: Provide routs from a couple key landmarks/intersections in the area.
  - Location of booths around campus: Provide a chart with the booth names and relative locations.
  
  ## How to Embed a Google Map
  
  1. Using Google Maps, navigate to the location you would like to embed.
  2. Click "Share" on the side menu.
  3. Click the "Embed Map" tab.
  4. Copy the given code and paste it into the plain text editor on the website. Click "Switch to plain text editor" and navigate to the part of the page you would like to place the map.
  
  ![Click Plain Text Option](images/plainTextEditor.jpg)
  
  5. In the code that you just pasted, locate the ```<iframe>``` tag and put a title attribute inside it.
  
  Eg: ```<iframe title="Title of Map" ... >```
  6. Below or Above the map, include appropriate text alternative for the key bits of information the map should relay to the user using the above guidelines.
