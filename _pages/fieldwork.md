---
layout: archive
title: "Field Work"
permalink: /fieldwork/
author_profile: true
---

## Map of Field Research, Adacemic & Professional Positions
<iframe src="/talkmap/map.html" height="700" width="850" style="border:none;"></iframe>

## Certifications & Training
* SCUBA: AAUS Scientific Diver (2012), AAUS 100ft certification (2017); NAUI Advanced, Rescue, & Nitrox Diver (2012); over 150 total lifetime dives
* Antarctic Field Training (2018, 2019, 2021): Antarctic Field Safety, Sea Ice Safety, Field Plan Risk Assessment, Snowmobile Operations, Tracked Vehicle Operations, GPS, Communication

## Scientific Field Work

### Research Engineer & Post Doctoral Fellow
* 2021 - Antarctic Field Season, Antarctica New Zealand (Oct 2021 - Jan 2022)
	* Kamb Ice Stream, Project K862 (5 weeks, 1 Icefin ROV deployment) - Exploration of subglacial channel with ROV, genomic sampling of subglacial water, geophysical surveys, operations from remote field camp. - [The Conversation](https://theconversation.com/exploring-antarcticas-hidden-under-ice-rivers-and-their-role-in-future-sea-level-rise-176456)
	* Scott Base, Project K750 (4 weeks, 5 Icefin ROV deployments) – ROV hydrographic survey of Scott Base coast.
	* McMurdo Sound, Project K063 (3 weeks, 8 Icefin ROV deployments) - Investigation of supercooling with ROV, deployment of submersible holographic microscope, operations from containerized sea ice camp. - [ANZ](https://www.antarcticanz.govt.nz/media/news/the-hippest-supercool-science-on-earth), [NewsHub](https://www.newshub.co.nz/home/technology/2022/01/kiwi-led-antarctic-hipsmi-project-hoped-to-help-with-climate-change-understanding.html)
* 2021 - Deadhorse, Alaska (3 weeks) – Geophysical surveys of pingo ice formations using snow mobiles. 
* 2019 - Antarctic Field Season, US Antarctic Program (Oct 2019 - Feb 2020)
	* International Thwaites Glacier Collaboration, Project C444 (4 weeks, 5 Icefin ROV deployments) – Oceanographic exploration of Thwaites grounding zone, ROV deployments through 500 m deep borehole, operations from remote field camp. - [ITGC](https://thwaitesglacier.org/projects/melt), [BBC Video](https://www.youtube.com/watch?v=f0AWsJ0cmLE), [BBC Camp Tour](https://www.bbc.com/news/av/science-environment-51333191)
	* McMurdo Station, Project B041 (13 weeks, 10 Icefin ROV deployments) – ROV surveys from sea ice.
* 2018 - Antarctic Field Season, US Antarctic Program (Oct 2018 - Dec 2019)
	* McMurdo Station, Project B041 (9 weeks, 22 Icefin ROV deployments) – ROV oceanographic exploration of McMurdo Sound, testing of submersible water sample, operations from sea ice. - [Antarctic Sun](https://antarcticsun.usap.gov/science/4396/), [PBS Video](https://www.pbs.org/video/exploring-antarcticas-threatened-glaciers-with-a-robot-ovte2f/), [WSJ Video](https://www.youtube.com/watch?v=uXA0AkcrNoo)
* 2018 - Florida St. Coastal & Marine Lab (1 week) – Icefin ROV ocean testing.

### PhD Student
* 2017 - San Diego, California (winter quarter, 10 dives) – Teaching assistant for scientific dive course.
* 2017 - Cayman Islands (2 weeks, 8 dives) – Small-boat deployment of towed microscope to study fish spawning. 
* 2016 - Eilat, Israel (8 weeks, 25 dives) – SCUBA based study of coral micro-fluid dynamics using micro-PTV system, at the Inter-University Institute for Marine Science (IUI). 
* 2016 - San Diego (3 weeks, 4 dives) – Small-boat deployments of towed microscope & smart drifters.
* 2016 - Cayman Islands (2 weeks, 8 dives) – Small-boat deployments of towed microscope to study fish spawning. 
* 2015 - Maui, Hawaii (2 weeks, 11 dives) – SCUBA based study of coral bleaching using Benthic Underwater Microscope. - [Australian Broadcasting Company](https://www.abc.net.au/news/2015-11-27/global-reef-bleaching-leaving-behind-coral-graveyards/6972150)
* 2014 - San Diego, California (spring quarter, 17 dives) – SCUBA based ecology field course.
* 2013 - Eilat, Israel (9 weeks, 38 dives) – SCUBA based study of coral behavior using the Benthic Underwater Microscope, at the Inter-University Institute for Marine Science (IUI). - [The Conversation](https://theconversation.com/underwater-microscope-provides-new-views-of-ocean-floor-sea-creatures-in-their-natural-setting-62265)
* 2012 - Palau (1 week) - Deployment & recovery of ocean gliders via small-boat.
* 2011 - South China Sea (3 weeks) - Internal waves study aboard R/V Revelle using fast CTD casts.
* 2011-18 - San Diego, California (> 6 day trips) – Research & course cruises aboard ocean research vessels.

### Undergraduate
* 2010 - Barrow & Wainwright, Alaska (2 weeks) - Ocean glider and radar deployments on Arctic Ocean.
* 2010 - Death Valley, California (1 week) - Geology field course.
* 2009 - Benin, West Africa (4 weeks) – Collection of groundwater hydrology data in remote wetland field sites. 
* 2008 - Benin, West Africa (4 weeks) – Collection of groundwater hydrology data in remote wetland field sites.

<!---
<html>
<head>
	<title>Leaflet debug page</title>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.0.0-beta.2/leaflet.css" />
	<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.0.0-beta.2/leaflet.js"></script>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="leaflet_dist/screen.css" />
	<link rel="stylesheet" href="leaflet_dist/MarkerCluster.css" />
	<link rel="stylesheet" href="leaflet_dist/MarkerCluster.Default.css" />
	<script src="leaflet_dist/leaflet.markercluster-src.js"></script>
	<script src="org-locations.js"></script>
</head>
<body>
	<div id="map"></div>
	<script type="text/javascript">
		var tiles = L.tileLayer('http://server.arcgisonline.com/ArcGIS/rest/services/World_Street_Map/MapServer/tile/{z}/{y}/{x}', {
          maxZoom: 18,
          attribution: 'Tiles &copy; Esri &mdash; Source: Esri, DeLorme, NAVTEQ, USGS, Intermap, iPC, NRCAN, Esri Japan, METI, Esri China (Hong Kong), Esri (Thailand), TomTom, 2012'
                }),
			latlng = L.latLng(30, 10);
		var map = L.map('map', {center: latlng, zoom: 0.7, layers: [tiles]});
		var markers = L.markerClusterGroup({
			showCoverageOnHover: false,
			maxClusterRadius: 80
			});
		for (var i = 0; i < addressPoints.length; i++) {
			var a = addressPoints[i];
			var title = a[0];
			var marker = L.marker(new L.LatLng(a[1], a[2]), { title: title });
			marker.bindPopup(title);
			markers.addLayer(marker);
		}
		map.addLayer(markers);
		map.zoomIn();
	</script>
</body>
</html>
--->
    
