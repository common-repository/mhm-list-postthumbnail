=== Add post thumbnail to wp-admin list view ===
Contributors: markhowellsmead
Donate link: https://www.paypal.me/mhmli
Tags: admin, thumbnail, post thumbnail, sayhellogmbh
Requires at least: 4.0
Tested up to: 6.6.1
Stable tag: trunk
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Adds a new column to the WordPress admin post list view, containing a preview of the post's featured image (where available).

== Description ==

Adds a new column to the WordPress admin post list view, containing a preview of the post's featured image (where available).

===Hooks===

Developers can use the `mhm-list-postthumbnail/exclude_posttype` filter to exclude the post thumbnail column from certain post types as required. The filter accepts and returns an array.

== Installation ==

1. Upload the plugin folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Changelog ==

= 1.3.4 =
* Remove manual version checking: version compatibility is now confirmed by WordPress Core, using the `Requires at least` and `Tested up to` headers in the plugin header.
* Update "Tested up to" to 6.5.4.

= 1.3.3 =
* Updating plugin meta. No functional changes.

= 1.3.2 =
* Updating plugin meta. No functional changes.

= 1.3.1 =
* Confirm support in in WordPress 6.5.3.

= 1.3.0 =
* Require PHP 5.6.
* Add `mhm-list-postthumbnail/exclude_posttype` filter to allow developers to disable the column programatically.
* Confirm support in in WordPress 5.7.

= 1.2.7 =
* Confirm support in in WordPress 5.6.
* Add plugin icon and header image for repository

= 1.2.6 =
* Fixes erroneous gettext function calls.
* Adds plugin icon file.

= 1.2.5 =
* Confirmation of compatibility up to WordPress 5.2.0.
* Re-layout PHP code per PSR2 conditions (no functional changes).
* Add plugin icon.
* Modify credit link to Say Hello GmbH.

= 1.2.4 =
* Confirmation of compatibility up to WordPress 5.0.2.

= 1.2.3 =
* Confirmation of compatibility up to WordPress 4.9.8.

= 1.2.2.1 =
* Confirmation of compatibility with WordPress 4.7.4.

= 1.2.2 =
* Confirmation of compatibility with WordPress 4.7.
* Swap out “key” variable for inline text domain keys, as recommended by the WordPress Translation team.
* No functional changes.

= 1.2.1 =
* Confirmation of compatibility with WordPress 4.6.

= 1.2.0 =
* Add WordPress version check.
* Improve localisation implementation.

= 1.1.1 =
* Improve localisation implementation.

= 1.1.0 =
* Add localisation.

= 1.0.1 =
* Confirmation of compatibility with WordPress 4.5.

= 1.0 =
* Initial public version.
