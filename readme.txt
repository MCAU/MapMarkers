MapMarkers
------------------------------------------------------------
 Adds markers to Minecraft Overviewer Google Maps interface
------------------------------------------------------------

Commands:
/newlabel [name]
/dellabel [name]



Features added:
  *Labels spawn (configurable)
  *Create labels ingame
  *Delete labels ingame
  *Labels player location
  *Players location is updated every 3seconds (default, can be configured)
  *Player locations are removed on logout
  
Features Planned:
  -Hashtags for custom CSS/icons

Icons IDs: (yet to be fully implemented)
  0: Origin, Default
  1: Homes
  2: Towns
  3: Points of Interest
  4: Player Location
  5: Capitals

Plugin Installation:
  !Apologies for the mess, will clean up deployment procedure soon!
  *Copy MapMarkers.jar to plugins/ folder.
  *Add "MapMarkers" (without quotes) to the plugins line of server.properties
  *Insert /newlabel and/or /dellabel into groups.txt for any usergroups you wish to have acces to making labels.
  *Edit mapmarkers.properties to set output directory of markers file to Minecraft-Overviewer map root
     markers=path/to/map/markers.json
  *Add map.js from Minecraft-Overviewer(see my fork) to index.html
  *See forums.hey0.net for more information