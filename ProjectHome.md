# WARNING WARNING WARNING #

THIS PROJECT HAS BEEN MIGRATED TO <a href='https://github.com/MKergall/osmbonuspack'>GITHUB</a>

From now, raise and follow Issues on GitHub ONLY

---

osmdroid is a library to interact with OpenStreetMap data inside an Android application. It offers an almost full/free replacement to Android map objects: MapView, MapController, Overlays, etc.

This "OSMBonusPack" library complements osmdroid with (very) useful classes:
  * [Markers](Tutorial_0.md) with nice and flexible "cartoon-bubbles",
  * [Routes and Directions](Tutorial_1.md),
  * [Points of Interests](Tutorial_2.md) (directory services),
  * [Marker Clustering](Tutorial_3.md),
  * Polyline, [Polygon](Tutorial_5.md) and [GroundOverlay](Tutorial_5.md), similar to their Google Maps equivalents,
  * Support for [KML and GeoJSON](Tutorial_4.md) content,
  * Geocoding and Reverse Geocoding,
  * Integrated Cache Management tools for off-line maps
  * and more...

Have a look to the [Features](Features.md).

The [OSMNavigator](OSMNavigator.md) application demonstrates the use of these classes. This is a generic-purpose Map/Navigation tool, including a KML viewer and editor.

# Examples #

Geocoding, route display, bubble on the destination with the address and an image<br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmnavigator_1_1.png' width='368'><br />

Turn-by-turn instructions shown in bubbles (with instructions in the default language of the phone):<br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmbonuspackdemo_2_1.png'><br />

The same turn-by-turn instructions shown in list view:<br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmbonuspackdemo_3_1.png'><br />

Searching for fuel stations along the route:<br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmbonuspackdemo_4_1.png'>

Searching fo cinemas inside an area, with clustered markers:<br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmbonuspackdemo_4_2.png' height='530'><br />

Showing Wikipedia POIs related to the current map view. In the bubble, the "more info" button will open the full Wikipedia page: <br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmbonuspackdemo_5_3.png'><br />

Showing geolocalized Flickr photos related to the current map view:<br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmbonuspackdemo_6_1.png'><br />

Showing geolocalized Picasa photos related to the current map view: 1) on the map, and 2) as a list view<br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmnavigator_7_1.png' width='368'>
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmnavigator_8_1.png' width='368'><br />

When searching a place by name, shows its enclosing polygon<br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmbonuspackdemo_9_2.png' width='368'><br />

MapBox Satellite maps in OSMNavigator:<br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmbonuspackdemo_10_1.png' width='368'><br />

Support for KML content. Example: on the left, a Google Maps "My Places", rendered with OSMBonusPack on the right:<br />
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmbonuspackdemo_12.png' height='530'>
<img src='http://osmbonuspack.googlecode.com/svn/BonusPackDownloads/img/osmbonuspackdemo_11.png' height='530'><br />

<h1>How to use it</h1>
Start with the <a href='HowToInclude.md'>installation guide</a>, then follow the <a href='Tutorial_0.md'>Tutorials</a>.<br>
<br>
In the <a href='http://code.google.com/p/osmbonuspack/source/browse/#svn%2FBonusPackDownloads'>Downloads</a>, you will find the library (jar file), the javadoc, and the <a href='OSMNavigator.md'>OSMNavigator</a> application.