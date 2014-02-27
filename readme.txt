=== Plugin Name ===
Contributors: Artin Hovhanesian
Tags: theme options, social media, analytics
Requires at least: 3.0.0
Tested up to: 3.8.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

With Simple Theme Options plugin your can easily manage your custom theme options like social media links. You also have the option to add misc code to the header.php and footer.php files, including your analytics code.

== Description ==

The plugin adds an am din interface where you can manage custom theme options.

- Add analytics code
- Add any misc code to header.php and footer.php
- Add social media links (Facebook, Twitter, etc.)
 
Instructions:
1. Install and activate plugin
2. Within your dashboard navigation click on "Theme Options"
3. You can add your analytics code and/or any other code to the appropriate fields, and it will automatically be added to your header.php and footer.php files
4. For social media links, add the appropriate url in each one of the fields, then add the following code to you theme files, where ever you want to call the values of the field: $themeOptions = get_option( 'chrs_theme_options' ); echo $themeOptions['fburl']

Support
Please submit your support requests through the WordPress forums for [Simple Theme Options](http://wordpress.org/plugins/simple-theme-options/).

== Installation ==

1. Upload the folder 'chrs-simple-options' to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Within your dashboard navigation click on 'Theme Options'
4. Place '<?php $themeOptions = get_option( 'chrs_theme_options' ); echo $themeOptions['fburl'] ?>' in your templates
5. change '[fburl]' to the appropriate code for each of the social media links

== Frequently Asked Questions ==

= A question that someone might have =

An answer to that question.

== Screenshots ==

1. screenshot-1.png

== Changelog ==

== Upgrade notice ==