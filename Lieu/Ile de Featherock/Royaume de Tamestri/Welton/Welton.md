---
mapCalc1: NaN
---
Welton est un petit village de bergers du [[Royaume de Tamestri]], niché au milieu de vastes pâturages. Quelques maisons de pierre et de bois s’organisent autour d’une place centrale, entourées de granges et d’enclos où paissent habituellement les troupeaux. Depuis plusieurs semaines, cependant, les habitants vivent dans la peur : une meute de loups s’attaque aux moutons et s’approche de plus en plus du village. Les bergers ont renforcé les clôtures et évitent désormais de sortir seuls à la tombée de la nuit.

Le maire, [[Tillus Merrion]], avait alors fait paraître une prime pour quiconque débarrasserait le village de cette menace. Récemment, un groupe d’aventuriers est parvenu à mettre fin aux attaques et, selon les habitants, la vie reprend peu à peu son cours à Welton. Pourtant, un détail intrigue : [[Tillus Merrion]] se montre étrangement absent de nombreuses cérémonies et festivités organisées depuis le retour au calme.

> [!NOTE]- Quick Calculator  
> Map Height in Pixels: `INPUT[number:map_height_y]`  
> Map Width in Pixels: `INPUT[number:map_width_x]`  
> lat: `VIEW[{map_height_y} / 2][math]`  
> long: `VIEW[{map_width_x} / 2][math]`  
> How Many Pixels In Scale: `INPUT[number:scale_pixels]`  
> How Many Units in Scale: `INPUT[number:scale_pixels_range]`  
> Scale: `VIEW[1/({scale_pixels}/{scale_pixels_range})][math:mapCalc1]`

```leaflet  
id: welton ### Must be unique with no spaces  
image: [[Welton.jpg]] ### Link to the map image file. Do not add a ! in front of the image  
bounds: [[0,0], [1950, 1950]] ### Size of the map in px Height_y, Width_x. Ignore 0,0  
height: 850px ### Size of the leaflet embed in px on your screen  
width: 95% ### Size of the leaflet embed in your note  
lat: 975 ### To center the map, make this half of the map height.  
long: 975 ### To center the map, make this half of the map width.  
minZoom: -1.5 ### Controls how far away from the map you can zoom out. Hover over the target icon to see the current level.  
maxZoom: 1 ### Controls how far towards the map you can zoom in. Hover over the target icon to see the current level.  
defaultZoom: -1 ### Sets the default zoom level when the map loads. Hover over the target icon to see the current level.  
zoomDelta: 0.5 ### Adjust how much the zoom changes when you zoom in or out.  
unit: mi ### The value displayed when measuring so you know what type of unit is being measure.  
scale: 0.09328358208955223 ### Real units/px (resolution) of your map  
recenter: false  
darkmode: false ### marker
```
