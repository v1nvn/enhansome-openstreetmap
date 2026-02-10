# Awesome OpenStreetMap [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

[<img src="osm-logo.svg" align="right" width="100">](https://www.openstreetmap.org/about)

> A curated list of awesome [OpenStreetMap](https://www.openstreetmap.org)-projects.

OpenStreetMap is an open map being used by millions of devices and users every day. It can both be edited and used by anyone free of charge.

This list contains projects using OpenStreetMap data for creative purposes, as well as projects dedicated to improving OpenStreetMap.

We also have a list of <a href="UNMAINTAINED.md">unmaintained projects</a>. If you are a developer, consider adopting one!

## Contents

* [Editors](#editors)
  * [Web Editors](#web-editors)
  * [Mobile Editors](#mobile-editors)
  * [Native Editors](#native-editors)
* [Tools](#tools)
  * [Web Tools](#web-tools)
  * [Mobile Tools](#mobile-tools)
  * [Native Tools](#native-tools)
  * [Browser Extensions](#browser-extensions)
* [Changeset Tools](#changeset-tools)
  * [Web Services](#web-services)
* [Tasking Managers](#tasking-managers)
* [Maps](#maps)
  * [Web Maps](#web-maps)
  * [Mobile Maps](#mobile-maps)
  * [Generators](#generators)
  * [Map Styles](#map-styles)
  * [Map Games](#map-games)
  * [Goal Tracking](#goal-tracking)
* [Libraries](#libraries)
  * [C/C++](#cc)
  * [JavaScript](#javascript)
  * [Python](#python)
  * [Java](#java)
* [Public APIs](#public-apis)
* [Miscellaneous](#miscellaneous)
* [Video](#video)
  * [Global](#global)
  * [Regional](#regional)
* [Additional Resources](#additional-resources)
  * [Websites](#websites)
  * [Wiki-Pages](#wiki-pages)
* [Articles](#articles)
* [Communities](#communities)
  * [Global Communities](#global-communities)
* [Related lists](#related-lists)

<!-- lint disable no-undefined-references -->

## Editors

### Web Editors

* [iD](http://www.openstreetmap.org/edit?editor=id) - JavaScript based editor for the web browser with a wide array of presets. ([Source Code](https://github.com/openstreetmap/iD) ⭐ 3,720 | 🐛 1,222 | 🌐 JavaScript | 📅 2026-02-06 / [Wiki](https://wiki.openstreetmap.org/wiki/ID))
* [Rapid](https://rapideditor.org/edit) - AI assisted versions of iD. ([Meta-Repo](https://github.com/facebookmicrosites/Open-Mapping-At-Facebook) ⭐ 188 | 🐛 7 | 📅 2022-07-27 / [Editor Source Code](https://github.com/facebook/Rapid) ⭐ 614 | 🐛 303 | 🌐 JavaScript | 📅 2026-02-04 / [Wiki](https://wiki.openstreetmap.org/wiki/RapiD))
* [Healthsites.io](https://healthsites.io/map) - An online editor focused on adding and improving data on global health facilities. ([Source Code](https://github.com/healthsites/healthsites/) ⭐ 162 | 🐛 218 | 🌐 JavaScript | 📅 2025-11-19 / [Wiki](https://wiki.openstreetmap.org/wiki/Healthsites.io))
* [OnOSM](https://www.onosm.org/) - Allows anyone to submit business information as a note for inclusion into OSM. ([Source Code](https://github.com/osmlab/onosm.org) ⭐ 86 | 🐛 25 | 🌐 CSS | 📅 2026-01-22 / [Wiki](https://wiki.openstreetmap.org/wiki/Onosm.org))
* [Level0](http://level0.osmz.ru/) - Text based editor that's useful in specific corner cases. ([Source Code](https://github.com/zverik/level0) ⭐ 61 | 🐛 30 | 🌐 Motoko | 📅 2026-01-15 / [Wiki](https://wiki.openstreetmap.org/wiki/Level0))
* [OSMyBiz](https://osmybiz.osm.ch) - Website for managing informations about your business. ([Source Code](https://gitlab.com/geometalab/osmybiz) / [Wiki](https://wiki.openstreetmap.org/wiki/OSMyBiz))

### Mobile Editors

<!--lint disable no-repeat-punctuation-->

* [StreetComplete](https://github.com/westnordost/StreetComplete) ⭐ 4,471 | 🐛 127 | 🌐 Kotlin | 📅 2026-02-09 - App for improving OSM by answering simple questions. ([Android](https://play.google.com/store/apps/details?id=de.westnordost.streetcomplete) / [Wiki](https://wiki.openstreetmap.org/wiki/StreetComplete))
* [Every Door](https://every-door.app) - Every Door is an Android and iOS app that lets you create and edit objects in OpenStreetMap. It supports editing node and polygon features, and creating point features like shops, benches, and building entrances. ([Android](https://play.google.com/store/apps/details?id=info.zverev.ilya.every_door) / [iOS](https://apps.apple.com/app/id1621945342) / [Source Code](https://github.com/zverik/every_door) ⭐ 527 | 🐛 180 | 🌐 Dart | 📅 2026-01-28 / [Wiki](https://wiki.openstreetmap.org/wiki/Every_Door))
* [Vespucci](https://vespucci.io/) - Advanced full-data-model editor for Android. ([Android](https://play.google.com/store/apps/details?id=de.blau.android) / [Source Code](https://github.com/MarcusWolschon/osmeditor4android) ⭐ 440 | 🐛 200 | 🌐 Java | 📅 2026-02-08 / [Wiki](https://wiki.openstreetmap.org/wiki/Vespucci))
* [GoMap!!](http://gomaposm.com) - Feature-rich mobile editor for iOS. ([iOS](https://apps.apple.com/app/id592990211) / [Source Code](https://github.com/bryceco/GoMap) ⭐ 380 | 🐛 91 | 🌐 Swift | 📅 2026-02-09 / [Wiki](https://wiki.openstreetmap.org/wiki/Go_Map!!))
* [OSM Go!](https://osmgo.com/) - OSM Go! is an Android application and a Progressive Web Applications (PWA) for contributing to OpenStreetMap. ([Android](https://play.google.com/store/apps/details?id=fr.dogeo.osmgo) / [Source Code](https://github.com/DoFabien/OsmGo) ⭐ 124 | 🐛 58 | 🌐 TypeScript | 📅 2024-07-08 / [Wiki](https://wiki.openstreetmap.org/wiki/Osm_Go!))

<!--lint enable no-repeat-punctuation-->

### Native Editors

* [Merkaartor](https://github.com/openstreetmap/merkaartor) ⭐ 331 | 🐛 68 | 🌐 C++ | 📅 2025-11-04 - An opensource OSM editor, written in C++ and Qt.
* [Potlatch 3](https://www.systemed.net/potlatch/) - Native intermediate-level editor built in Adobe AIR. ([Source Code](https://github.com/systemed/potlatch3) ⭐ 30 | 🐛 29 | 🌐 ActionScript | 📅 2024-06-05 / [Wiki](https://wiki.openstreetmap.org/wiki/Potlatch))
* [JOSM](https://josm.openstreetmap.de) - Advanced extensible desktop editor. ([Source Code](https://josm.openstreetmap.de/browser) / [Wiki](https://wiki.openstreetmap.org/wiki/JOSM))

## Tools

### Web Tools

* [overpass-turbo](http://overpass-turbo.eu) - Web based data mining tool for OpenStreetMap using Overpass API. ([Source Code](https://github.com/tyrasd/overpass-turbo) ⭐ 1,123 | 🐛 265 | 🌐 TypeScript | 📅 2026-01-28 / [Wiki](https://wiki.openstreetmap.org/wiki/Overpass_turbo))
* [OSMNames](http://osmnames.org/) - Geocoding tool ranking places according to the corresponding Wikipedia page popularity. ([Source Code](https://github.com/osmnames/osmnames) ⭐ 378 | 🐛 33 | 🌐 Python | 📅 2024-08-07 / [Wiki](https://wiki.openstreetmap.org/wiki/OSMNames))
* [opening\_hours evaluation tool](https://openingh.openstreetmap.de/evaluation_tool/) - Tool for evaluating `opening_hours` tags. ([Source Code](https://github.com/opening-hours/opening_hours.js) ⭐ 244 | 🐛 96 | 🌐 JavaScript | 📅 2026-01-31)
* [Bellingcat OpenStreetMap search](https://osm-search.bellingcat.com/) - Web based tool to find geolocation leads by searching for proximate features on OpenStreetMap. ([Source Code](https://github.com/bellingcat/osm-search) ⭐ 199 | 🐛 12 | 🌐 Vue | 📅 2025-01-29 / [Article](https://www.bellingcat.com/resources/how-tos/2023/05/08/finding-geolocation-leads-with-bellingcats-openstreetmap-search-tool/))
* [taginfo](https://taginfo.openstreetmap.org/) - Website displaying information on tags and their usage. ([Source Code](https://github.com/taginfo/taginfo/) ⭐ 134 | 🐛 75 | 🌐 Ruby | 📅 2026-02-06 / [Wiki](https://wiki.openstreetmap.org/wiki/Taginfo))
* [OpenStreetMap Welcome Tool](https://welcome.osm.be/) - Tool for finding fresh mappers in your area. ([Source Code](https://github.com/osmbe/osm-welcome-tool) ⭐ 45 | 🐛 40 | 🌐 PHP | 📅 2026-02-01)
* [Web To OSM Opening Hours](https://webmapping.cyou/WebToOSMOH/) - Tool for converting human-readable opening hours to `opening_hours` tags. ([Source Code](https://github.com/OSM-de/WebToOSMOH) ⭐ 11 | 🐛 3 | 🌐 JavaScript | 📅 2022-08-21)
* [OpenMapTiles](https://openmaptiles.org/) - Set of tools for self-hosted vector maps and map services with labels in more than 50 languages. ([Source Code](https://github.com/openmaptiles) / [Wiki](https://wiki.openstreetmap.org/wiki/OpenMapTiles))
* [hdyc](http://hdyc.neis-one.org) - Statistics viewer for contributions of any OSM user. ([Wiki](https://wiki.openstreetmap.org/wiki/How_did_you_contribute%3F)) <!-- markdown-link-check-disable-line -->
* [Osmose](https://osmose.openstreetmap.fr) - QA-tool for fixing problems detected in OpenStreetMap data. ([Source Code](https://github.com/osm-fr?q=osmose) / [Wiki](https://wiki.openstreetmap.org/wiki/Osmose))
* [Turn Restrictions](https://ahorn.lima-city.de/tr/) - Viewer for turn-restrictions and linked errors.
* [NLMaps](https://nlmaps.gorgor.de/) - Website allowing to query OSM data using plain English.
* [My Notes](https://my-notes.osm-hr.org/) - Search for finding your old unresolved notes.
* [YoHours](https://projets.pavie.info/yohours/) - Tool for generating `opening_hours` tags. ([Source Code](https://framagit.org/PanierAvide/YoHours))
* [ohsome Dashboard](https://ohsome.org/apps/dashboard/) - Tool for visualizing changes over a certain time period. ([Wiki](https://wiki.openstreetmap.org/wiki/Ohsome_Dashboard))
* [OSM Statistics](https://piebro.github.io/openstreetmap-statistics/) - Up-to-date OSM statistics about editor usage, corporate contributions and more.

### Mobile Tools

* [OSMTracker](https://github.com/labexp/osmtracker-android) ⭐ 542 | 🐛 85 | 🌐 Java | 📅 2026-02-08 - Offline GPS tracking tool for recording GPX tracks. (Android / [Wiki](https://wiki.openstreetmap.org/wiki/OSMTracker_\(Android\)))

### Native Tools

* [Baremaps](https://www.baremaps.com/) - Open source pipeline for producing Mapbox vector tiles from OpenStreetMap with Postgis and Java. ([Source Code](https://github.com/baremaps/baremaps) ⭐ 559 | 🐛 49 | 🌐 Java | 📅 2025-09-23)

### Browser Extensions

* [better-osm-org](https://github.com/deevroman/better-osm-org) ⭐ 166 | 🐛 156 | 🌐 JavaScript | 📅 2026-02-09 - Userscript that adds visualization of changesets and many other useful features to OSM website.
* [OpenSwitchMaps](https://github.com/tankaru/OpenSwitchMaps) ⭐ 61 | 🐛 24 | 🌐 JavaScript | 📅 2025-07-05 -  Map service switcher for [Firefox](https://addons.mozilla.org/firefox/addon/openswitchmaps/) and [fork](https://github.com/limex/OpenSwitchMaps-v3) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2026-01-03 with Manifest v3 support.
* [OpenStreetMap Tags Editor](https://github.com/Zverik/osmtags-editor) ⭐ 35 | 🐛 6 | 🌐 JavaScript | 📅 2025-06-30 - Adds the ability to edit OSM object tags.
* [OpenStreetMap Human-readable Wikidata](https://community.openstreetmap.org/t/announcing-human-readable-wikidata-browser-plugins-for-openstreetmap-org/108180) - Shows descriptions and illustrations for wiki tags ([Source Code](https://github.com/ZeLonewolf/osm-wikidata-greasemonkey) ⭐ 9 | 🐛 2 | 🌐 JavaScript | 📅 2024-01-27).
* [JumpToOSMChangesetAnalyzer](https://github.com/tankaru/JumpToOSMChangesetAnalyzer) ⭐ 4 | 🐛 12 | 🌐 JavaScript | 📅 2023-01-07 - Jump from OpenStreetMap changeset to changeset analyzer services.

## Changeset Tools

### Web Services

* [osmcha](https://osmcha.org) - Detector for suspicious changesets. ([Source Code](https://github.com/mapbox/osmcha-frontend) ⭐ 142 | 🐛 288 | 🌐 JavaScript | 📅 2025-08-13 / [Wiki](https://wiki.openstreetmap.org/wiki/OSMCha))
* [Who did it?](https://simon04.dev.openstreetmap.org/whodidit/) - Map highlighting recent edits per tile. Provides RSS feeds for watching changes in custom bounding boxes.  ([Source Code](https://github.com/simon04/whodidit) ⭐ 75 | 🐛 16 | 🌐 JavaScript | 📅 2025-04-20 / [Wiki](https://wiki.openstreetmap.org/wiki/Quality_assurance#WhoDidIt))
* [achavi](https://overpass-api.de/achavi/) - Augmented change viewer. ([Source Code](https://github.com/nrenner/achavi/) ⭐ 43 | 🐛 37 | 🌐 JavaScript | 📅 2023-10-11 / [Wiki](https://wiki.openstreetmap.org/wiki/Achavi))
* [changeset-map](http://osmlab.github.io/changeset-map/) - Map visualizing changes in selected changesets. Used in OsmCha. ([Source Code](https://github.com/osmlab/changeset-map) ⭐ 35 | 🐛 55 | 🌐 JavaScript | 📅 2025-10-09)
* [OSM History Viewer](https://osmhv.openstreetmap.de/) - Changeset visualization. ([Source Code](https://github.com/osmrmhv/osmrmhv) ⭐ 13 | 🐛 10 | 🌐 Java | 📅 2020-10-13)
* [Osm Change Viz](https://resultmaps.neis-one.org/osm-change-viz) - Changeset visualizer displaying information about added/modified/deleted elements in different panels.

<!--Offline, may be because of russia-ukraine-war - * [whodidit](http://zverik.osm.rambler.ru/whodidit/) - Changesets analyzer.-->

* [Analytic OSM Tracker](https://github.com/MichaelVL/osm-analytic-tracker) ⭐ 38 | 🐛 6 | 🌐 Python | 📅 2021-05-08[^selfhosted-only] - Tracker for changesets in your region.
* [latest-changes](https://rene78.github.io/latest-changes/#2/15.0/-15.0) - Visualize latest OSM changesets within a certain geographic boundary. Includes a simple vandalism checker. ([Source Code](https://github.com/rene78/latest-changes/) ⭐ 12 | 🐛 5 | 🌐 JavaScript | 📅 2026-01-16)
* [Osm Change Tiles](https://resultmaps.neis-one.org/osm-change-tiles) - Map highlighting recent edits per tile. Provides RSS feeds for watching changes in custom bounding boxes.
* [Suspicious OSM Changesets](https://resultmaps.neis-one.org/osm-suspicious) - Find suspicious OSM changesets.
* [Changeset Text Search](https://resultmaps.neis-one.org/osm-changesets) - Filter OSM changesets by comment.
* [Latest Changeset Discussions](https://resultmaps.neis-one.org/osm-discussions) - Show latest discussions on OSM changesets.
* [OSM Inspector](https://tools.geofabrik.de/osmi/?view=geometry\&lon=-12.00000\&lat=25.00000\&zoom=3\&baselayer=Geofabrik%20Standard\&overlays=long_ways%2Cways_with_long_segments%2Clong_segments%2Cself_intersection_ways%2Cself_intersection_points%2Csingle_node_in_way%2Cduplicate_node_in_way%2Clong_ways%2Cways_with_long_segments%2Clong_segments%2Cself_intersection_ways%2Cself_intersection_points%2Csingle_node_in_way%2Cduplicate_node_in_way) - The OSM Inspector (alias OSMI) is a web based debugging tool for advanced OpenStreetMap users offered by Geofabrik. On a map you can see several themed views, each with several layers, showing specific details of the OSM data, often with highlighted errors.
* [Nominatim QA](https://nominatim.org/qa/#map=1.81/0.00/0.00) - The Nominatim Data Analyser is a QA tool used to scan the nominatim database and extract suspect data from it. These data are then presented to mappers through a visual interface so that they can correct them directly.

## Tasking Managers

Tasking Managers are websites which assign small tasks to individual users to work towards a common goal.

This section is a great place to start if you want to get into improving OpenStreetMap.

* [MapRoulette](https://maproulette.org/) - Various challenges for making small edits to achive big tasks. ([Source Code](https://github.com/osmlab/maproulette3) ⭐ 161 | 🐛 107 | 🌐 JavaScript | 📅 2026-02-03 / [Wiki](https://wiki.openstreetmap.org/wiki/MapRoulette))
* [NotesReview](https://ent8r.github.io/NotesReview/) - Interface for searching and resolving OSM notes. ([Source Code](https://github.com/ENT8R/NotesReview) ⭐ 53 | 🐛 9 | 🌐 JavaScript | 📅 2025-12-16)
* [OSM Streak](http://streak.osmz.ru/) - OSM Streak makes you do small tasks for OSM every day. Tasks are small and about five minutes each, but the point is to map every day, not map as much as you can. ([Source Code](https://github.com/Zverik/osmstreak) ⭐ 25 | 🐛 28 | 🌐 Python | 📅 2024-09-24)
* [HOT Tasking Manager](https://tasks.hotosm.org/) - Mapping tasks for supporting humanitarian missions in crisis areas.
* [Pic4Review](https://pic4review.pavie.info/#/) - Tool for adding objects to OSM by reviewing images. ([Source Code](https://framagit.org/Pic4Carto/Pic4Review) / [Wiki](https://wiki.openstreetmap.org/wiki/Pic4Review))
* [Map Complete](https://mapcomplete.osm.be/) - Tool for mapping in scoped tasks. ([Wiki](https://wiki.openstreetmap.org/wiki/MapComplete))
* [Damn Project](https://www.damn-project.org/) - Project for mapping by dividing big areas into small squares mappable by humans. ([Source Code](https://git.sr.ht/~qeef/damn-deploy) / [Wiki](https://wiki.openstreetmap.org/wiki/Divide_and_map._Now.))
* [TeachOSM Tasking Manager](https://tasks.teachosm.org/) - Tasking Manager made for school classrooms to help map for humanitarian causes.

## Maps

### Web Maps

* [Streets GL](https://github.com/StrandedKitty/streets-gl) ⭐ 981 | 🐛 105 | 🌐 TypeScript | 📅 2025-08-21 - OpenStreetMap 3D renderer powered by WebGL2. ([Wiki](https://wiki.openstreetmap.org/wiki/Streets_GL))
* [FacilMap](https://facilmap.org/) - Map with easy possibility to filter for POI types. ([Source Code](https://github.com/FacilMap/facilmap) ⭐ 391 | 🐛 71 | 🌐 TypeScript | 📅 2026-01-18 / [Wiki](https://wiki.openstreetmap.org/wiki/FacilMap))
* [OsmAPP](https://osmapp.org) - A browsable map showing data and offering simple POI-editing capabilities. ([Source Code](https://github.com/zbycz/osmapp) ⭐ 343 | 🐛 171 | 🌐 TypeScript | 📅 2026-02-06)
* [Road Curvature](https://roadcurvature.com/map/) - Helps to find curvy roads for those who enjoy them. ([Source Code](https://github.com/adamfranco/curvature) ⭐ 258 | 🐛 15 | 🌐 Python | 📅 2022-01-12)
* [Show me the way](https://osmlab.github.io/show-me-the-way/) - Live map showing latest changes on aerial imagery. ([Source Code](https://github.com/osmlab/show-me-the-way/) ⭐ 142 | 🐛 9 | 🌐 JavaScript | 📅 2025-12-21 / [Wiki](https://wiki.openstreetmap.org/wiki/Show_Me_The_Way))
* [osm-livechanges](http://live.openstreetmap.fr/) - Near-real-time display of edits in the OpenStreetMap database. ([Source Code](https://github.com/cstenac/osm-livechanges) ⭐ 28 | 🐛 13 | 🌐 JavaScript | 📅 2022-05-17)
* [Baato Before-After Maps](https://beforeafter.baato.io/) - Generate before-after maps to visualize the work your local community has done. ([Source Code](https://github.com/baato/before-after) ⭐ 27 | 🐛 44 | 🌐 Vue | 📅 2025-04-23)
* [OSM In Realtime](https://osm-in-realtime.jwestman.net/) - Visualization of the changes made to OpenStreetMap as they happen. ([Source Code](https://gitlab.com/jwestman/osm-in-realtime) / [Wiki](https://wiki.openstreetmap.org/wiki/OSM-in-realtime))
* [indoor=](https://indoorequal.org) - Map for viewing indoor data from OpenStreetMap. ([Wiki](https://wiki.openstreetmap.org/wiki/Indoor%3D)) <!-- markdown-link-check-disable-line -->
* [F4map Demo](https://demo.f4map.com/) - 3D rendering demo of OpenStreetMap data. ([Wiki](https://wiki.openstreetmap.org/wiki/F4_Map))
* [Straßenraumkarte Neukölln](https://supaplexosm.github.io/strassenraumkarte-neukoelln/?map=micromap) - High-detail micromap of the district "Neukölln" of Berlin, Germany. ([Wiki](https://wiki.openstreetmap.org/wiki/Micromapping#Stra.C3.9Fenraumkarte_Neuk.C3.B6lln))
* [OpenLevelUp!](https://openlevelup.net/) - An OSM based indoor viewer.([Wiki](https://wiki.openstreetmap.org/wiki/OpenLevelUp))
* [AccessMap](https://www.accessmap.io/) - A web map project to enable accessible, safe sidewalk trip planning for people with limited mobility. Currently rendering senveral cities in Washington State. ([Source Code](https://github.com/accessmap))
* [Cycle.Travel](https://cycle.travel/map) - An OSM-based bike route-planner, together with extensive editorial content about long-distance cycle routes and city cycling. ([Wiki](https://wiki.openstreetmap.org/wiki/Cycle.travel))
* [OSM Landuse](https://osmlanduse.org) - OSM based landuse and landcover WebGIS application.
* [Tracesmap](https://tracesmap.com/) - A map allowing for planning routes on OsmCarto and OpenTopoMap-derived retina maps.
* [Visit Sights](https://visitsights.com/) - Suggestions for self-guided sightseeing tours by foot and overview of individual sights all around the world.
* [Defikarte.ch](https://www.defikarte.ch) - A Map that shows all available defibrillators in Switzerland and Liechtenstein, also used by emergency dispatch centers and rescue services. (ℹ️ German only)
* [openclimbing.org](https://openclimbing.org) - A map for rock climbers with editor for creating interactive climbing guides based on OpenStreetMap.

### Mobile Maps

* [Organic Maps](https://organicmaps.app/) - A free offline maps app based on OSM. (Android, iOS / [Source Code](https://github.com/organicmaps/organicmaps) ⭐ 13,236 | 🐛 3,196 | 🌐 C++ | 📅 2026-02-09 / [Wiki](https://wiki.openstreetmap.org/wiki/Organic_Maps))
* [OsmAnd](https://osmand.net) - Map viewing and navigation (routing) application with offline functionality available for Android and iOS. (Android, iOS / [Source Code Android](https://github.com/osmandapp/OsmAnd) ⭐ 5,536 | 🐛 3,321 | 🌐 Java | 📅 2026-02-10 / [Source Code iOS](https://github.com/osmandapp/OsmAnd-iOS) ⭐ 328 | 🐛 293 | 🌐 Objective-C++ | 📅 2026-02-10 / [Wiki](https://wiki.openstreetmap.org/wiki/OsmAnd))
* [Magic Earth](https://www.magicearth.com/) - A free turn-by-turn navigation app. (Android, iOS / [Wiki](https://wiki.openstreetmap.org/wiki/Magic_Earth))
* [Komoot](https://www.komoot.com/) - A route planner and navigation app specializing in hiking and cycling. ([Android](https://market.android.com/details?id=de.komoot.android), [iOS](https://itunes.apple.com/de/app/id447374873?mt=8) / [Wiki](https://wiki.openstreetmap.org/wiki/Komoot))

### Generators

* [Field Papers](http://fieldpapers.org/) - Generate maps for printing, annotate them, and manage your notes after. ([Source Code](https://github.com/fieldpapers/fieldpapers) ⭐ 90 | 🐛 135 | 📅 2025-02-13 / [Wiki](https://wiki.openstreetmap.org/wiki/Field_Papers))
* [MyOSMatic](https://print.get-map.org/new/) - Website for generating printable street maps from OSM data. ([Source Code](https://github.com/hholzgra/maposmatic/) ⭐ 84 | 🐛 70 | 🌐 Python | 📅 2025-10-27)

### Map Styles

* [Terrain Classic](https://github.com/stamen/terrain-classic) ⭐ 145 | 🐛 60 | 🌐 CartoCSS | 📅 2024-06-09 - World-wide CartoCSS port of Stamen's classic terrain style.

### Map Games

* [Arnis](https://github.com/louis-e/arnis) ⭐ 8,289 | 🐛 58 | 🌐 Rust | 📅 2026-02-09 - Generate cities from real life in Minecraft using Python.
* [Back Of Your Hand](https://backofyourhand.com/) - A web map game that tests your knowledge by having you find a street in a given area. ([Source Code](https://github.com/adam-lynch/back-of-your-hand) ⭐ 98 | 🐛 7 | 🌐 Svelte | 📅 2026-01-19)
* [PraxisMapper](https://github.com/drakewill-CRL/PraxisMapper) ⭐ 68 | 🐛 2 | 🌐 C# | 📅 2026-01-12 - GPS Game server, for making mobile games around exploring the real world.

### Goal Tracking

The services in this category allow you to track personal and fitness goals utilizing OpenStreetMap data.

* [CityStrides](https://citystrides.com/) - A web platform that encourages the user to run every street in their city. Based on your Strava data it shows where you have and have not run, provides challenges, a leaderboard, and a forum.

## Libraries

### C/C++

* [OSRM](https://github.com/Project-OSRM/osrm-backend) ⭐ 7,461 | 🐛 441 | 🌐 C++ | 📅 2026-02-06 -  Routing engine for use in C++ applications. ([Wiki](https://wiki.openstreetmap.org/wiki/Open_Source_Routing_Machine))
* [mapnik](https://github.com/mapnik/mapnik) ⭐ 3,903 | 🐛 724 | 🌐 C++ | 📅 2026-01-28 - Combines pixel-perfect image output with lightning-fast cartographic algorithms, and exposes interfaces in C++, Python, and Node. ([Wiki](https://wiki.openstreetmap.org/wiki/Mapnik))
* [libosmium](https://github.com/osmcode/libosmium) ⭐ 533 | 🐛 10 | 🌐 C++ | 📅 2026-01-18 - Fast and flexible C++ library for working with OpenStreetMap data. ([Wiki](https://wiki.openstreetmap.org/wiki/Osmium))

### JavaScript

* [Leaflet](https://leafletjs.com/) - An open-source JavaScript library for mobile-friendly interactive maps. ([Source Code](https://github.com/Leaflet/Leaflet) ⭐ 44,478 | 🐛 542 | 🌐 JavaScript | 📅 2026-02-09 / [Wiki](https://wiki.openstreetmap.org/wiki/Leaflet))
* [OpenLayers](https://openlayers.org/) - A high-performance library for rendering raster and vector maps. ([Source Code](https://github.com/openlayers/openlayers) ⭐ 12,319 | 🐛 872 | 🌐 JavaScript | 📅 2026-02-09 / [Wiki](https://wiki.openstreetmap.org/wiki/OpenLayers))
* [MapLibre GL JS](https://maplibre.org/projects/#js) - A map renderer with GPU-accelerated vector tile rendering. ([Source Code](https://github.com/maplibre/maplibre-gl-js) ⭐ 9,855 | 🐛 410 | 🌐 TypeScript | 📅 2026-02-09 / [See Related List](#related-awesome-maplibre))
* [node-mapnik](https://github.com/mapnik/node-mapnik) ⭐ 544 | 🐛 105 | 🌐 C++ | 📅 2026-02-01 - Node wrapper for mapnik.
* [node-osmium](https://github.com/osmcode/node-osmium) ⚠️ Archived - Node wrapper for libosmium for working with OpenStreetMap data.
* [osm-pbf-parser-node](https://github.com/borisgontar/osm-pbf-parser-node) ⭐ 18 | 🐛 0 | 🌐 JavaScript | 📅 2024-07-14 - Streaming OpenStreetMap PBF parser for Node.js.
* [openstreetmap-tag-map](https://github.com/tanrax/openstreetmap-tag-map) - Tag for Riot.js to generate iframe-map from the country and region.

### Python

* [osmnx](https://github.com/gboeing/osmnx) ⭐ 5,566 | 🐛 6 | 🌐 Python | 📅 2026-02-08 - Visualizer for street networks. ([Wiki](https://wiki.openstreetmap.org/wiki/OSMnx))
* [prettymapp](https://github.com/chrieke/prettymapp) ⭐ 2,706 | 🐛 3 | 🌐 Python | 📅 2025-12-25 - Create beautiful maps from OpenStreetMap data.
* [overpass-wrapper](https://github.com/mvexel/overpass-api-python-wrapper) ⚠️ Archived - Wrapper around the OpenStreetMap Overpass API.
* [QuackOSM](https://github.com/kraina-ai/quackosm) ⭐ 350 | 🐛 34 | 🌐 Python | 📅 2026-02-09 - A Python library for downloading, filtering and transforming `*.osm.pbf` files into `GeoParquet` files using DuckDB.
* [overpy](https://github.com/DinoTools/python-overpy) ⭐ 260 | 🐛 25 | 🌐 Python | 📅 2025-12-15 - A Python wrapper to access the Overpass API.
* [osmapi](https://github.com/metaodi/osmapi) ⭐ 225 | 🐛 18 | 🌐 Python | 📅 2025-06-10 - Python wrapper for the OpenStreetMap API. ([Wiki](https://wiki.openstreetmap.org/wiki/Osmapi_\(Python_library\)))
* [python-mapnik](https://github.com/mapnik/python-mapnik) ⭐ 174 | 🐛 154 | 🌐 Python | 📅 2026-02-09 - Python wrapper for mapnik.
* [osmcha](https://github.com/willemarcel/osmcha) ⭐ 50 | 🐛 9 | 🌐 Python | 📅 2024-08-27 - Python package to detect suspicious OSM changesets.
* [geodesk](https://github.com/clarisma/geodesk-py) ⭐ 47 | 🐛 27 | 🌐 C++ | 📅 2025-12-10 - Fast and storage-efficient database for OpenStreetMap analysis.
* [humanized\_opening\_hours](https://github.com/rezemika/humanized_opening_hours) ⭐ 28 | 🐛 7 | 🌐 Python | 📅 2021-10-21 - A package to parse the `opening_hours` tag.
* [overpassforge](https://github.com/Krafpy/Overpass-Forge) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-01-28 - A package to build Overpass queries from Python objects.

### Java

* [GraphHopper](https://github.com/graphhopper/graphhopper) ⭐ 6,260 | 🐛 256 | 🌐 Java | 📅 2026-02-05 - Open source route planning library and server using OpenStreetMap. ([Wiki](https://wiki.openstreetmap.org/wiki/GraphHopper))
* [OpenTripPlanner](https://github.com/opentripplanner/OpenTripPlanner) ⭐ 2,542 | 🐛 147 | 🌐 Java | 📅 2026-02-09 - Open source multi-modal trip planner. ([Wiki](https://wiki.openstreetmap.org/wiki/OpenTripPlanner))
* [OSM2World](http://osm2world.org) - OSM2World is a converter that creates three-dimensional models of the world from OpenStreetMap data. It can be used as a stand-alone tool, on a server or as a library in Java programs. ([Source Code](https://github.com/tordanik/OSM2World) ⭐ 689 | 🐛 101 | 🌐 Java | 📅 2025-12-22 / [Wiki](https://wiki.openstreetmap.org/wiki/OSM2World))
* [GeoDesk](https://github.com/clarisma/geodesk) ⭐ 178 | 🐛 42 | 🌐 Java | 📅 2025-09-29 - Fast and storage-efficient database for OpenStreetMap analysis.

## Public APIs

* [overpass](http://overpass-api.de) - Read-only API that serves up custom selected parts of the OSM map data. ([Source Code](https://github.com/drolbr/Overpass-API) ⭐ 847 | 🐛 197 | 🌐 C++ | 📅 2025-06-08 / [Wiki](https://wiki.openstreetmap.org/wiki/Overpass_API))
* [OSMCha API](https://osmcha.org/api-docs/) - Powerful API that allows to query and retrieve changeset information. ([Source Code](https://github.com/willemarcel/osmcha-django) ⭐ 40 | 🐛 42 | 🌐 Python | 📅 2026-01-31)
* [osm.mazdermind](https://osm.mazdermind.de/replicate-sequences/) - Maps Timestamp to replicate sequences. ([Source Code](https://github.com/MaZderMind/replicate-sequences) ⭐ 9 | 🐛 1 | 🌐 PHP | 📅 2024-03-26)
* [planet.osm](http://planet.osm.org) - Minutely/weekly/yearly/full dumps of osm data. ([Wiki](https://wiki.openstreetmap.org/wiki/Planet.osm))
* [bbbike](https://extract.bbbike.org) - Custom extracts of areas from planet.osm. ([Wiki](https://wiki.openstreetmap.org/wiki/BBBike_@_World))
* [Bunting Labs' OSM Extract API](https://buntinglabs.com/solutions/openstreetmap-extracts) - Free extracts of OSM features as GeoJSON, filtering on tags and bounding box. ([Docs](https://docs.buntinglabs.com/openstreetmap-api/extract))

## Miscellaneous

* [OpenGeofiction](https://opengeofiction.net/) - A completely fictional user-made world map, created using the OSM software platform. ([Wiki](https://wiki.openstreetmap.org/wiki/OpenGeofiction))
* [OSM Monitor](https://osm-monitor.com/) - A website to monitor and display new OSM edits. ([Source Code](https://github.com/johanmorganti/osm-datadog) ⭐ 12 | 🐛 10 | 🌐 Python | 📅 2025-12-07)
* [OpenHistoricalMap](https://www.openhistoricalmap.org/) - Mapping places throughout the world… throughout the ages, created using the OSM software platform. ([Wiki](https://wiki.openstreetmap.org/wiki/OpenHistoricalMap))

## Video

### Global

* [State of the Map](https://www.youtube.com/channel/UCLqJsr_5PfdvDFbgv1qp2aQ) - YouTube channel of the State of the Map conference containing VoDs of talks. ([Wiki](https://wiki.openstreetmap.org/wiki/State_of_the_Map))
* [Humanitarian OpenStreetMap Team (HOT)](https://www.youtube.com/user/hotosm) - YouTube channel of the HOT containing content regarding humanitarian OSM work.

### Regional

* [OpenStreetMap Indonesia YouTube Channel](https://www.youtube.com/channel/UCRqMbcsT9ummMvByc1BlsDQ)
* [OpenStreetMap Poland YouTube Channel](https://www.youtube.com/channel/UCH4PSBSafxZ-YWg8RCRbHjA)
* [OpenStreetMap US YouTube Channel](https://www.youtube.com/channel/UCQpS2iHNVR-_6nAxt87nwCw)

## Additional Resources

### Websites

* [LearnOSM.org](https://learnosm.org/en/beginner/) - Extensive beginners' guide to editing OpenStreetMap. ([Wiki](https://wiki.openstreetmap.org/wiki/LearnOSM))
* [What OSM?](https://whatosm.pavie.info/) - Tool for finding tools for contributing to OSM by answering three simple questions.
* [TeachOSM](https://teachosm.org/) - Project assisting educators at all levels to introduce open source mapping and OpenStreetMap in the classroom. ([Wiki](https://wiki.openstreetmap.org/wiki/TeachOSM))
* [WeeklyOSM](https://weeklyosm.eu/) - News and updates to inform the community about what is going on in the OSM Universe, from experienced mappers to new OSM members.

### Wiki-Pages

* [Main Page](https://wiki.openstreetmap.org/wiki/Main_Page) - An overview page with links to the most useful pages.
* [Beginners' guide](https://wiki.openstreetmap.org/wiki/Beginners'_guide) - Five-step-guide on what OpenStreetMap is and how it works.
* [Mapping projects](https://wiki.openstreetmap.org/wiki/Mapping_projects) - Mapping projects to participate in.
* [OSM Promotional Material Programme](https://wiki.openstreetmap.org/wiki/OSM_Promotional_Material_Programme) - Information on receiving promotional merch such as Stickers.

## Articles

* [Volunteer armies map ‘invisible’ communities hit by coronavirus](https://www.asahi.com/ajw/articles/13729507) - OpenStreetMap contributors map over 1,100 handwashing stations. (5 min read, 2020-10-15, The Asahi Shimbun)

## Communities

### Global Communities

* [OpenStreetMap Community](https://community.openstreetmap.org/) - Official forums hosted by the OpenStreetMap Foundation.
* [r/openstreetmap](https://www.reddit.com/r/openstreetmap) - Inofficial Reddit forum dedicated to sharing OSM related links and news.
* [“OpenStreetMap World” Discord](https://discord.gg/openstreetmap) - OSM related instant messaging and voice chat group.

## Related lists

* [awesome-maplibre](https://github.com/maplibre/awesome-maplibre#readme) ⭐ 907 | 🐛 0 | 📅 2026-01-31 - A collection of awesome things that use or support MapLibre! <span id="related-awesome-maplibre"/>

## Footnotes

OpenStreetMap and the OpenStreetMap Logo are a trademark of the OpenStreetMap Foundation, and is used with their permission. This project is not endorsed by or affiliated with the OpenStreetMap Foundation.

The OpenStreetMap Logo by Ken Vermette is used under the Creative Commons Attribution-ShareAlike 3.0 License.

[^selfhosted-only]: This project does not provide a hosted instance and has to be self-deployed. Refer to the project's website for instructions.
