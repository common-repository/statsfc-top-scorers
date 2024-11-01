=== StatsFC Top Scorers ===
Contributors: willjw
Donate link:
Tags: widget, football, soccer, premier league
Requires at least: 3.3
Tested up to: 6.2.2
Stable tag: 3.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This widget will place a live football top scorers table in your website.

== Description ==

Add a football top scorers table to your WordPress website. To request a key sign up for your free trial at [statsfc.com](https://statsfc.com).

For a demo, check out [wp.statsfc.com/top-scorers](https://wp.statsfc.com/top-scorers/).

= Translations =
* Bahasa Indonesia
* Dansk
* Deutsch
* Eesti
* Español
* Français
* Hrvatski Jezik
* Italiano
* Magyar
* Norsk bokmål
* Slovenčina
* Slovenski Jezik
* Suomi
* Svenska
* Türkçe

If you're interested in translating for us, please get in touch at [hello@statsfc.com](mailto:hello@statsfc.com) or on Twitter [@StatsFC](https://twitter.com/StatsFC).

== Installation ==

1. Upload the `statsfc-top-scorers` folder and all files to the `/wp-content/plugins/` directory
2. Activate the widget through the 'Plugins' menu in WordPress
3. Drag the widget to the relevant sidebar on the 'Widgets' page in WordPress
4. Set the StatsFC key and any other options. If you don't have a key, sign up for free at [statsfc.com](https://statsfc.com)

You can also use the `[statsfc-top-scorers]` shortcode, with the following options:

* `key` (required): Your StatsFC key
* `competition` (required*): Competition key, e.g., `EPL`
* `team` (required*): Team name, e.g., `Liverpool`
* `season` (optional): Season to show top scorers for, e.g., `2016/2017`
* `date` (optional): For a back-dated top scorers list, e.g., `2013-12-31`
* `highlight` (optional): Name of the team you want to highlight, e.g., `Liverpool`
* `limit` (optional): Maximum number of top scorers to show, e.g., `5`, `10`
* `show_badges` (optional): Display team badges, `true` or `false`
* `default_css` (optional): Use the default widget styles, `true` or `false`
* `omit_errors` (optional): Omit error messages, `true` or `false`

*Only one of `competition` or `team` is required.

== Frequently asked questions ==



== Screenshots ==



== Changelog ==

= 3.0.0 =
* Refactor: Update plugin for new API

= 2.13.2 =
* Hotfix: Issue displaying the number of goals when selecting a specific team

= 2.13.1 =
* Hotfix: Possible issue loading language/CSS files

= 2.13.0 =
* Feature: Allow top scorers to be shown for a specific season via the new `season` parameter

= 2.12.4 =
* Hotfix: Check options exist before using them

= 2.12.3 =
* Hotfix: Check highlight value against short and full team names

= 2.12.2 =
* Hotfix: Check the before/after widget/title bits exist before using them

= 2.12.1 =
* Hotfix: Fixed missing team badges

= 2.12.0 =
* Feature: Added multi-language support. If you're interested in translating for us, please get in touch at [hello@statsfc.com](mailto:hello@statsfc.com)

= 2.11.2 =
* Hotfix: Added a responsive horizontal scroll if the widget is too wide for mobile

= 2.11.1 =
* Hotfix: Fixed possible `Undefined index: omit_errors` error

= 2.11.0 =
* Feature: Put CSS/JS files back into the local repo
* Feature: Enqueue style/script directly instead of registering first

= 2.10.0 =
* Feature: Added `omit_errors` parameter
* Feature: Load CSS/JS remotely

= 2.9.3 =
* Hotfix: Fixed "Invalid domain" bug caused by referal domain

= 2.9.2 =
* Hotfix: Fixed bug saving 'Show badges' option

= 2.9.1 =
* Hotfix: Fixed bug with boolean options

= 2.9.0 =
* Feature: Added `show_badges` parameter

= 2.8.0 =
* Feature: Allow more discrete ads for ad-supported accounts

= 2.7.0 =
* Feature: Enabled ad-support

= 2.6.0 =
* Feature: Use built-in WordPress HTTP API functions

= 2.5.0 =
* Feature: Added badge class for each team

= 2.4.0 =
* Feature: Default `default_css` parameter to `true`

= 2.3.0 =
* Feature: Updated team badges.

= 2.2.0 =
* Feature: Added `[statsfc-top-scorer]` shortcode.

= 2.1.0 =
* Feature: Added a `date` parameter.

= 2.0.0 =
* Feature: Updated to use new API.

= 1.6.0 =
* Feature: Tweaked error message.

= 1.5.0 =
* Feature: More reliable team icons.

= 1.4.0 =
* Feature: Added fopen fallback if cURL request fails.

= 1.3.1 =
* Hotfix: Fixed possible cURL bug.

= 1.3.0 =
* Feature: Use cURL to fetch API data if possible.

= 1.2.0 =
* Feature: Updated team badges for 2013/14.

= 1.1.0 =
* Feature: Deleted redundant images.

= 1.0.1 =
* Hotfix: Fixed bug that prevents the widget from loading.

== Upgrade notice ==

