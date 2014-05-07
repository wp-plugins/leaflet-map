=== Plugin Name ===
Author: bozdoz
Author URI: http://www.twitter.com/bozdoz/
Plugin URI: http://wordpress.org/plugins/leaflet-map/
Contributors: bozdoz
Donate link: https://www.gittip.com/bozdoz/
Tags: leaflet, map, javascript, mapquest
Requires at least: 3.0.1
Tested up to: 3.8.1
Version: 1.0
Stable tag: 1.0
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A flexible plugin that adds two shortcodes: one for creating multiple leaflet maps, and one for adding multiple markers to those leaflet maps.

== Description ==

Add a map generated with <a href="http://www.leafletjs.com/" target="_blank">leaflet JS</a>: a mobile friendly map application.  Map tiles are provided by default through <a href="http://developer.mapquest.com/web/products/open/map" target="_blank">MapQuest</a>.  Can be set per map with shortcode attributes or through the dashboard settings.

Some shortcode attributes:

Height, width, latitude, longitude and zoom are the basic attributes: 

`[leaflet-map height=250 width=250 lat=44.67 lng=-63.61 zoom=5]`

The default URL requires attribution by its terms of use.  If you want to change the URL, you may remove the attribution.  Also, you can set this per map in the shortcode (1 for enabled and 0 for disabled): 

`[leaflet-map show_attr="1"]`

The zoom buttons can be large and annoying.  Enabled or disable per map in shortcode: 

`[leaflet-map zoomcontrol="0"]`

== Installation ==

1. Choose to add a new plugin, then click upload
2. Upload the leaflet-map zip
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Use the shortcodes in your pages or posts: e.g. `[leaflet-map]` and `[leaflet-marker]`

== Frequently Asked Questions ==

None yet.  Shoot me a question [@bozdoz](http://www.twitter.com/bozdoz/).

== Screenshots ==

1. Put the short code into the post.
2. See the short code play out on the front end.

== Changelog ==

= 1.0 =
* First Version. Basic map creation and marker creation.

== Upgrade Notice ==

= 1.0 =
First Version. Tested with 3.8.1.