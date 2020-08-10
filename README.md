# mapTypeSwitchForISSTransitFinderMap
Bookmarklet for [ISS Transit Finder Map](https://transit-finder.com/)

Please bookmark this link.
Open this link when ISS Transit Finder Map is open.
It gives you another menu to switch Sattelite Map to help your location search.

[Map Type Switch for ISS Transit FInder Map](javascript:(function(){if(document.getElementById('map_type_switch')==null){var mapmenu = document.getElementById('map_menu');var togglecenterlines = document.getElementById('toggle_center_lines');var typesw = document.createElement('input');typesw.id="map_type_switch";typesw.type="button";typesw.value="To SATELLITE";typesw.onclick=function (event) {if(typesw.value=="To SATELLITE"){typesw.value="To ROADMAP";__map.setMapTypeId( google.maps.MapTypeId.SATELLITE );}else{typesw.value="To SATELLITE";__map.setMapTypeId( google.maps.MapTypeId.ROADMAP );}};mapmenu.insertBefore(typesw, togglecenterlines.nextSibling);}})();)
