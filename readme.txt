=== Inesta Send Mail Copy ===
Contributors: roelv
Donate link: https://inesta.nl
Tags: email, admin
Requires at least: 3.7
Tested up to: 4.7
Stable tag: 1.0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Sends a copy of every e-mail send via WordPress to an e-mail address.

== Description ==

This plugin adds the functionality to send a copy of every mail send by WordPress.

Note 1: Even mails which include passwords or other privacy sensitive information are send to the entered e-mail address.

Note 2: If a plugin uses there own method of the PHP mail function to send e-mails this plugin cannot send a copy.

== Installation ==

This section describes how to install the plugin and get it working.

1. Download the plugin.
1. Upload `Inesta Mail Copy` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Under `Settings` -> `Mail Copy` you can now specify an e-mail address

== Frequently Asked Questions ==

= How do I see the original to address =

You should use the BCC option. Then the original sender is shown in the TO field.


== Screenshots ==

== Changelog ==


= 1.0.2 =
* Added language support
* Added Dutch

= 1.0.1 =
* Shows the original input again.
* Addes support to send BCC

= 1.0 =
* First version!
* Handles one e-mail address to send copies to.
