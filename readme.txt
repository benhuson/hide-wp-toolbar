=== Hide WP Toolbar ===
Contributors: jr00ck
Plugin URI: http://blog.webguysaz.com/hide-wp-toolbar-wordpress-plugin/
Donate link: http://blog.webguysaz.com/donate/
Tags: hide, toolbar, minimize, admin bar, toggle, adminbar
Requires at least: 3.8
Tested up to: 3.9
Stable tag: 2.2

Easily hide or show the front-end WordPress Admin Toolbar with a click of a button.

== Description ==

Easily hide or show the front-end WordPress Admin Toolbar with a click of a button. The plugin adds a special button to the right side of the WordPress Admin Toolbar that only displays when you are outside the admin area of WordPress on the front-end. Clicking it will make the admin bar slide off the page to the top left corner, leaving only the hide/show button visible. Clicking the button again will restore the Toolbar to its original position. The shown/hidden position is remembered between page visits so that it can be kept hidden away until you are ready to bring it back.

There are no options or configuration. Just install and activate the plugin. When you exit the admin area, you will see the button to the far right of the Toolbar. Modern, capable browsers (not IE) will use a nice transition to show and hide the Toolbar.  

I actually like the WordPress Toolbar. It's a convenient way to go back and forth from the admin area to the public website. However, when I'm doing design modifications for a theme, the Toolbar can be visually distracting. I wanted a quick way to hide the WordPress Toolbar when needed, but otherwise keep it around. I tried several plugins but they didn't work as I wanted or didn't even work at all in some cases. So I decided to build my own.

= Contributions Welcome =
This plugin is now on Github. [Submit a pull request](https://github.com/jr00ck/hide-wp-toolbar) if you'd like to contribute.

== Installation ==

1. Upload entire `hide-wp-toolbar` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Navigate to the public area of the site and click the right side button to hide/show the WP Toolbar

== Frequently Asked Questions ==

= Are there any settings for this plugin? =

Nope. No settings page is created. Just activate and start using. No configuration required.

= I don't see any of the nice transitions when the toolbar hides or shows. Why not? =

You most likely have a lousy browser, like Internet Explorer. This plugin uses nice CSS3 transitions that are supported in modern browsers, like [Chrome](http://google.com/chrome), [Firefox](http://firefox.com), and [Safari](http://apple.com/safari).

= I have the latest version of Internet Explorer. Isn't that "modern"? =

No. See above.

= Why don't you use jQuery UI for transitions instead? Then it would work in all browsers, right? =

I could. But it would be wrong.

== Screenshots ==

1. The WordPress Toolbar shown with the hide/show button on the right.
1. The WordPress Toolber hidden with only the hide/show button visible.

== Changelog ==

= 2.2 =
* Use pretty dashicon from WordPress 3.8+ for button arrow (plugin now requires WordPress 3.8+)

= 2.1 =
* Modified placement of hide/show button for better compatibility with WordPress 3.8+

= 2.0 =
* Added functionality to remember shown/hidden position of toolbar between page loads

= 1.3 =
* Initial public release