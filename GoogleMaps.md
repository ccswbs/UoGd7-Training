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
  - Directions to a place: Provide text alternatives of routs from specific land marks that lead to the place.
  - Location of Buildings/Objects around campus: Provide a chart which references what item/building can be found where.
  
  ## How to Embed a Google Map
  1. Navigate to the location on the map that you would like to embed normally via google maps.
  2. Click "Share" on the side menu.
  3. Click "Embed Map".
  4. Copy that code and paste it into the plain text editor.
  5. Find the < iframe> attribute and put a title attribute. Eg: < iframe title="Title of Map" ... >
  6. Provide text alternative for the map below detailing the important information.
