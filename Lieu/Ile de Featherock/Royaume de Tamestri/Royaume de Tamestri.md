Le royaume de Tamestri est le plus petit royaume de l'ile de [[Featherock]]. Dirigé par [[Henrik le Brave]], le royaume tente de grandir et de prospérer malgré la pression exercée par ses puissants voisins.

Récemment, plusieurs escarmouches ont éclaté le long de la frontière avec le [[Royaume de Li'ite]], à l'est. Afin d'éviter une escalade du conflit, plusieurs détachements diplomatiques sont partis de Tamestri.

Au sud-est du royaume, le [[Passage des Forçats]] mène au [[Cratère des Faveurs]]. Ce lieu dangereux est toujours gardé par de nombreux prisonniers, condamnés à cette tâche et ayant choisi cette peine plutôt que la mort. Malgré les légendes entourant cet endroit, le cratère est toujours la source de violent vent de magie qui déforme le ciel et la terre.

```leaflet  
id: tamestri ### Must be unique with no spaces  
image: [[Tamestri.jpg]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [1312, 1199]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 850px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 656 ### To center the map, make this half of the map height.  
long: 599 ### To center the map, make this half of the map width.  
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```