Theme-Independent Stylesheets
=============================

## Description ##
This plugin allows you to use uploaded CSS files that can be used across themes without having to edit any theme files or use FTP.

For example, if you wanted to use Font Awesome on your site but your current theme doesn't include it (or you know you want to use Font Awesome regardless of what theme you're using), you can simply upload the `font-awesome.css` (or `font-awesome.min.css`) file using the WordPress Media Uploader then activate said stylesheet in the Theme-Independent Stylsheets (TISS) settings. That CSS file will then automatically be included on your site no matter what theme you're using. Even if you switch themes, the CSS file will still be called in your site's `<head>` (as long as the theme is coded to properly use `wp_head()`, which most themes are).

## Installation ##

1. Install TISS either via the [WordPress.org plugin directory](https://wordpress.org/plugins/theme-independent-stylesheets/) or by uploading the plugin folder ( `theme-independent-stylesheets` ) to your server's WordPress plugins directory.
1. Activate the plugin through the 'Plugins' menu in WordPress

## Changelog ##

### 1.0.3 - Released 2016/08/15 ###
*	Changed plugin text domain to fall in line with WordPress's internationalization standards (as per https://developer.wordpress.org/plugins/internationalization/how-to-internationalize-your-plugin/#text-domains) and fixed a small typo in the plugin name definition of the TISSHEETS_PLUGIN_NAME constant

### 1.0.2 - Released 2015/11/23 ###
*	Updated settings-page headings to match WordPress 4.4's new heading structure on admin pages

### 1.0.1 - Released 2015/03/06 ###
*	Small change to make `require_once` for plugin definitions more specific to avoid possible `require_once` conflicts

### 1.0.0 - Released 2015/02/08 ###
*	Initial release.
