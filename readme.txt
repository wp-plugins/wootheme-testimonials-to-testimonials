=== WooTheme Testimonials to Testimonials by Aihrus ===

Contributors: comprock
Donate link: http://aihr.us/about-aihrus/donate/
Tags: woothemes, migration, convert, testimonials, testimonials widget
Requires at least: 3.6
Tested up to: 3.9.0
Stable tag: 1.1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Migrate WooTheme Testimonials entries to Testimonials by Aihrus custom post types.


== Description ==

Migrate WooTheme Testimonials entries to Testimonials [by Aihrus](http://aihr.us/about-aihrus/) custom post types for use by the best WordPress testimonials plugin there is, [Testimonials by Aihrus](http://wordpress.org/extend/plugins/testimonials-widget/).

= Primary Features =

* API
* Ajax based processing screen
* Migrates WooTheme Testimonial fields, categories, and images to Testimonials by Aihrus format
* Settings export/import
* Settings screen

= Settings Options =

**Testing**

* Posts to Import - A CSV list of post ids to import, like '1,2,3'.
* Skip Importing Posts - A CSV list of post ids to not import, like '1,2,3'.
* Import Limit - Useful for testing import on a limited amount of posts. 0 or blank means unlimited.

**Compatibility & Reset**

* Export Settings – These are your current settings in a serialized format. Copy the contents to make a backup of your settings.
* Import Settings – Paste new serialized settings here to overwrite your current configuration.
* Remove Plugin Data on Deletion? - Delete all WooTheme Testimonials to Testimonials data and options from database on plugin deletion
* Reset to Defaults? – Check this box to reset options to their defaults


== Installation ==

= Requirements =

* PHP 5.3+ [Read notice](https://aihrus.zendesk.com/entries/30678006)
* Plugin "[Testimonials by Aihrus](http://wordpress.org/plugins/testimonials-widget/)" is required to be installed and activated prior to activating "WooTheme Testimonials to Testimonials".

= Install Methods =

* Through WordPress Admin > Plugins > Add New, Search for "WooTheme Testimonials to Testimonials"
	* Find "WooTheme Testimonials to Testimonials by Aihrus"
	* Click "Install Now" of "WooTheme Testimonials to Testimonials by Aihrus"
* Download [`wootheme-testimonials-to-testimonials.zip`](http://downloads.wordpress.org/plugin/wootheme-testimonials-to-testimonials.zip) locally
	* Through WordPress Admin > Plugins > Add New
	* Click Upload
	* "Choose File" `wootheme-testimonials-to-testimonials.zip`
	* Click "Install Now"
* Download and unzip [`wootheme-testimonials-to-testimonials.zip`](http://downloads.wordpress.org/plugin/wootheme-testimonials-to-testimonials.zip) locally
	* Using FTP, upload directory `wootheme-testimonials-to-testimonials` to your website's `/wp-content/plugins/` directory

= Activation Options =

* Activate the "WooTheme Testimonials to Testimonials" plugin after uploading
* Activate the "WooTheme Testimonials to Testimonials" plugin through WordPress Admin > Plugins

= Usage =

1. Edit options through WordPress Admin > Testimonials > WTT Settings
1. Migrate WooTheme Testimonials via WordPress Admin > Testimonials > WTT Migrator


= Upgrading =

* Through WordPress
	* Via WordPress Admin > Dashboard > Updates, click "Check Again"
	* Select plugins for update, click "Update Plugins"
* Using FTP
	* Download and unzip [`wootheme-testimonials-to-testimonials.zip`](http://downloads.wordpress.org/plugin/wootheme-testimonials-to-testimonials.zip) locally
	* Upload directory `wootheme-testimonials-to-testimonials` to your website's `/wp-content/plugins/` directory
	* Be sure to overwrite your existing `wootheme-testimonials-to-testimonials` folder contents


== Frequently Asked Questions ==

= Most Common Issues =

* Got `Parse error: syntax error, unexpected T_STATIC, expecting ')'`? Read [Most Aihrus Plugins Require PHP 5.3+](https://aihrus.zendesk.com/entries/30678006) for the fixes.
* [Debug common theme and plugin conflicts](https://aihrus.zendesk.com/entries/25119302)

= Still Stuck or Want Something Done? Get Support! =

1. [Testimonials Knowledge Base](https://aihrus.zendesk.com/categories/20104507) - read and comment upon 125+ frequently asked questions
1. [Open WooTheme Testimonials to Testimonials Issues](https://github.com/michael-cannon/wootheme-testimonials-to-testimonials/issues) - review and submit bug reports and enhancement requests
1. [WooTheme Testimonials to Testimonials Support on WordPress](http://wordpress.org/support/plugin/wootheme-testimonials-to-testimonials) - ask questions and review responses
1. [Contribute Code to WooTheme Testimonials to Testimonials](https://github.com/michael-cannon/wootheme-testimonials-to-testimonials/blob/master/CONTRIBUTING.md)
1. [Beta Testers Needed](http://aihr.us/become-beta-tester/) - get the latest WooTheme Testimonials to Testimonials version


== Screenshots ==

1. WooTheme Testimonials to Testimonials Settings
2. WooTheme Testimonials to Testimonials Migrator

[gallery]


== Changelog ==

See [CHANGELOG](https://github.com/michael-cannon/wootheme-testimonials-to-testimonials/blob/master/CHANGELOG.md)


== Upgrade Notice ==

= 1.1.1 =

* Require Testimonials by Aihrus 2.18.1

= 1.0.0 =

* Initial release


== Notes ==

TBD


== API ==

* Read the [WooTheme Testimonials to Testimonials API](https://github.com/michael-cannon/wootheme-testimonials-to-testimonials/blob/master/API.md).

== Localization ==

You can translate this plugin into your own language if it's not done so already. The localization file `wootheme-testimonials-to-testimonials.pot` can be found in the `languages` folder of this plugin. After translation, please [send the localized file](http://aihr.us/contact-aihrus/) for plugin inclusion.

**[How do I localize?](https://aihrus.zendesk.com/entries/23691557)**
