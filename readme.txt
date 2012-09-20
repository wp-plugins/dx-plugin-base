=== DX Plugin Base ===
Contributors: nofearinc
Tags: plugin, base, startup, skeleton, stub
Requires at least: 3.1
Tested up to: 3.4.2
Stable tag: 1.0
License: GPLv2 or later

Startup plugin code for new plugin, including the archetype of standard features, admin and core functions to be used in new plugins.

== Description ==

This is a sample skeleton plugin for plugin developers. 

It serves as a startup code providing reference and working codebase for custom post type and taxonomies, creating admin pages,
registration of activate/deactivate hooks and more. Use it freely as your plugin startup snippet. 

Take the code as is for test and learning or use it when creating plugins for a solid base. To be extended with 
widget and shortcode samples.

== Installation ==

Upload the DX Plugin Base plugin to your blog and activate it. It would work as is.

Extend or comment whenever appropriate based on your assignment. 

== FAQ ==

= Is it compatible with latest WordPress? =

Yes, it is, as well as with the latest PHP. 

I've removed the 'pass-by-reference' call for all array( $this, ... ) entries as it's deprecated since 5.3.0. If you happen to use 5.2.4, you can replace all $this in arrays with &$this or better update PHP version.