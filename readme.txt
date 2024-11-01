=== User Meta Management ===
Contributors: wposmosys, sampathkumar0019, prasanna03, siddhartha-osmosys
Donate link: http://osmosys.asia/
Tags: user, meta, management, users, usermeta, wp_usermeta
Requires at least: 4.0
Tested up to: 4.9
Requires PHP: 5.5
Stable tag: 0.0.1
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

A WordPress plugin that allows you to view the meta keys associated with a given user.

== Description ==

* Manages the user meta information.
* User can add the new custom meta key.
* User can update the meta information.
* User can delete the custom meta information.
* User can enter the meta key and value and he can get the list of users who are having the same meta information.
* By entering the value of meta key and by omitting the meta value, user can get the list of users, containing the entered meta key.

== Installation ==

1. Upload the plugin(`user-meta-management`) files to the `/wp-content/plugins/user-meta-management` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' menu in WordPress.This section describes how to install the plugin and get it working.

== Frequently Asked Questions ==

= How to view usermeta of a user? =

1. Go to settings page of the plugin. Users -> User Meta Management. 
2. Click on the user id of that user to whom you want to see usermeta.
3. A popup will be opened which shows all the user metas of that user.

= Why some meta keys are disabled? =

Some usermeta keys are disabled because those are the default usermetas used by WordPress. We shouldn't change those meta keys.

= How to add a usermeta to user? =

1. Go to settings page of the plugin. Users -> User Meta Management. 
2. Click on the user id of the user to whom you want to add usermeta.
3. A popup will be opened which shows all the user metas of that user.
4. On top right corner of the popup, there will be a Add Meta Key button. Click on it to add a meta key.
5. Enter your meta key and meta value. Click on Save.

= How to delete a usermeta(s) of a user? =

1. Go to settings page of the plugin. Users -> User Meta Management. 
2. Click on the user id of the user to whom you want to delete usermeta.
3. A popup will be opened which shows all the user metas of that user.
4. Click on the checkbox in that row of the meta key.
5. Click on Delete button to delete the checked meta keys.

= Why there is no checkbox next to nickname, first_name and last_name meta keys? =

These usermetas are used by WordPress by default. These meta keys are neither be deleted nor be updated (meta values can be updated). So, there is no checkbox to delete these meta keys.

== Screenshots ==

1. Starting screen of the user meta manager 
`/assets/frontscreen.png`

2. Screenshot showing results of meta search.
`/assets/metasearch.png`

3. Screenshot for opening user meta information dialog box
`/assets/open-dialog.png`

4. Screenshot showing adding of meta keys to the user.
`/assets/addusermeta.png`

5. Screenshot showing update of meta keys to the user
`/assets/updateusermeta.png`

6. Screen showing the deleting of meta keys.
`/assets/preventdelete.png`

== Changelog ==

= 0.0.1 =
* Initial release.

== Upgrade Notice ==

= 0.1 =
* Initial release.
