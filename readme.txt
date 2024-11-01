=== Plugin Name ===
Contributors: bloutch
Tags: geo, location, geolocation, geotag, radius, latitude, longitude, distance, miles, km, geoloc, range, plugin, widget, url, GET
Requires at least: 3.8
Tested up to: 4.4.1
Stable tag: 1.0.2

Search for posts around a location with a specific distance.

== Description ==

This plugin adds geolocation functionnalities to your wordpress, it allows you to find posts around you or a location with a specific distance radius.
You can select a specific location with the widget or you can make a request with URL by providing latitude, longitude and distance as GET parameters.
The widget and the shortocode consists of a Google Autocomplete and a distance range slider.

<h4>Widget :</h4>

Go in widget area, then place the widget in a zone.
Have fun !

<h4>Shortcode :</h4>

Simply add this code where you want to place the search box : [wpgeoloc]

<h4>Play with URL:</h4>

For example : on an archive page, you are looking restaurants located in a 10 miles radius from this latitude [50.8385607] and this longitude [4.37526040] :

* http://www.example.com/category/restaurant?latitude=50.8385607&longitude=4.37526040&distance=10

You can do it on the search page with the keyword "super" :

* http://www.example.com/?s=super&latitude=50.8385607&longitude=4.37526040&distance=10


<h4>Requirement :</h4>

If you want to use the widget and the Google place autocomplete, then you need a Google Places API KEY.
How to get a Google Places API key :
* https://developers.google.com/places/web-service/get-api-key

== Contributions ==

* github : https://github.com/NicolasBlois/wp-geoloc

= Special Features =
* URL : search with latitude, longitude, distance provided as GET parameters in URL.
* Widget : the widget consists of a Google Autocomplete and a distance range slider.
* Shortcode : the shortcode generates a Google Autocomplete and a distance range slider. Usage : [wpgeoloc]

== Translations ==
* English - default, always included
* French

== Installation ==
<h4>Installation instructions :</h4>
* Upload to plugins dir
* Activate plugin

<h4>Configuration instructions :</h4>
* If you want to use the widget and the Google place autocomplete, then you need a Google Places API KEY. Get your Google Places API key here : https://developers.google.com/places/web-service/get-api-key
* Add a location for each post you wish to geotag. A box is provided for this purpose in post edit mode.
* Enjoy the geolocated requests.

== Frequently Asked Questions ==

= How to get a Google Places API KEY? =
* Simply follow instructions here : https://developers.google.com/places/web-service/get-api-key

== Changelog ==
= 1.0.2 =
* standardization of code

= 1.0.1 =
* New : widget to search geolocated content.
* New : shortcode to include the geolocated search form in any post.
* New : translations in French
* Fix : Prevent XSS and other attacks

= 1.0.0 =
* Initial release
