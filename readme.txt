=== Plugins Last Updated Column ===
Contributors: Fastmover, karissa
Tags: plugins, plugins last updated, last updated, updated
Requires at least: 3.7
Tested up to: 6.5.2
Stable tag: 0.1.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin adds columns to the admin plugin's page to show when each plugin was last updated and upgraded.

== Description ==

This plugin adds a column to the plugin's page in WordPress's admin to show when each plugin was last updated. This causes the plugins page to load very slowly on the first page load due to many API calls made to wordPress.org in order to retrieve the last updated information.  This plugin makes 1 API call for each plugin installed.  This data is cached for 24 hours. The functionality of this plugin was entirely [Karissa Skirmont](http://kissaskreations.com/ "Kissa's Kreations")'s idea. [Plugin Page](http://stevenkohlmeyer.com/plugins-last-updated-column/ "Plugins Last Updated Column").  Artwork compliments of [Karissa](http://kissaskreations.com/ "Kissa's Kreations")

== Installation ==

1. Install this plugin either via the WordPress.org plugin directory, or by uploading the files to your server
2. Activate the plugin through the 'Plugins' menu in WordPress
3. That's it. You're ready to go!

== Screenshots ==

1. As you can see, the plugins table now has 2 columns on the right side labeled: Last Updated and Last Upgraded.
2. A page dedicated to clearing cache on the Last Updated Column.
3. Shows a WordPress MultiSite Network Plugin page with last updated / last upgraded columns.

== Changelog ==

= 0.1.3 =
* Fixed debug warnings

= 0.1.2 =
* Version bump - Plugin still works as expected with Wordpress 6.5.2

= 0.1.1 =
* Version bump - Plugin still works as expected with Wordpress 6.0.1

= 0.1.0 =
* Version number bump - Plugin still works as expected with WordPress 5.6

= 0.0.9 =
* Version number bump - This plugin still works as expected with the new WordPress 5.2

= 0.0.8 =
* Version number bump

= 0.0.7 =
* Added support for multisite

= 0.0.6 =
* PHP 5.2 Compliance - Calculated months may be just a bit off if you're running PHP 5.2
* Changed caching from 24 hours to 30 minutes.
* Added a cache clearing option in Admin Menu > Plugins > Plugin Columns
* Fixed screen options not hiding columns or saving
* Added background color to whole column instead of just text
* Fixed errors outputting if WordPress's API cannot be reached

= 0.0.5 =
* New column to show when the plugin was last upgraded - shows not available until each plugin is upgraded at least once.

= 0.0.4 =
* Now outputs how long it's been since the last update
* Background of this text is colored based on how long it's been: (over 2 years is red, over 1 year is orange, over 6 months is yellow and less than 6 months is green)

= 0.0.3 =
* Updated plugin description and tags

= 0.0.2 =
* Column is now responsive and disabled white-space wrapping for easier reading.

= 0.0.1 =
* Plugin adds a last updated column to the plugins page of the admin.
