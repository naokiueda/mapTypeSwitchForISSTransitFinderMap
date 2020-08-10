This is a bookmarklet to add Switch RoadMap<--->SatelliteMap on [ISS Transit Finder](https://transit-finder.com)
 
Please bookmark following link, and open it on ISS Transit Finder result Map.

javascript:(function(){if(document.getElementById('map_type_switch')==null){var mapmenu = document.getElementById('map_menu');var togglecenterlines = document.getElementById('toggle_center_lines');var typesw = document.createElement('input');typesw.id='map_type_switch';typesw.type='button';typesw.value='To SATELLITE';typesw.onclick=function (event) {if(typesw.value=='To SATELLITE'){typesw.value='To ROADMAP';__map.setMapTypeId( google.maps.MapTypeId.SATELLITE );}else{typesw.value='To SATELLITE';__map.setMapTypeId( google.maps.MapTypeId.ROADMAP );}};mapmenu.insertBefore(typesw, togglecenterlines.nextSibling);}})();

(c) 2020 Naoki Ueda 
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.</body>

