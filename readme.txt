=== jQuery Cookie Url Fix ===
Contributors: rutkoski
Donate link: 
Tags: bu, fix, 406, cookie
Requires at least: 2.6
Tested up to: 3.6.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Wordpress fix for a 406 error caused by jQuery Cookie

== Description ==

I made this plugin to fix a bug I got using a theme called Attitude, but other people had the same bug with other plugins. The problem is on some server configurations. mod_security will block the file jquery.cookie.min.js, specifically because of the "cookie" part, and return a 406 Not Acceptable http status. The plugin suplies a copy of the file with a different name.

== Installation ==

1. Upload to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. That's it!

== Changelog ==

= 1.0 =
* Initial release.
