# Changelog

## Version 3.1.0 - 2023/02/23 - Android+532 - iOS+532 - Web+532

Release files [here](https://github.com/androidseb/mapmarker/releases/tag/map_marker_v3.1.0).

* Android only:
	* Changed location update interval from 5 seconds to 0.5 seconds
	* Fixed premium logic not correctly granting premium to users with donation badges
	* Fixed an issue with the "send email" functionality, not working on some email apps
	* Fixed Android V2 to V3 migration migrating Dropbox cloud maps to limited access
* Updated Google Authentication flow to use the latest recommended standards (Google Identity Services) (Web only)
* Improved text-to-coordinates logic: for example, the coordinates dialog now handles degree-minutes-seconds coordinates as a paste input
* Coordinates dialog using preferred coordinates format vs always decimal degrees
* Fixed "polyline" and "polygon" buttons incorrectly displaying when moving a marker
* Added the option to disable the "max drawn POIs" option completely
* Fixed text capitalization for text fields: first letter is now automatically capitalized
* Fixed implementation of the HERE search source, and updated help center setup steps
* Improved UX around handling cloud sync errors

## Version 3.0.2 - 2023/02/13 - Android+526 - iOS+526 - Web+526

Release files [here](https://github.com/androidseb/mapmarker/releases/tag/map_marker_v3.0.2).

* Fixed old data migration failing on corrupted coordinates (Android only)
* Fixed alternative coordinates format displaying incorrectly
* Improved handling for multi cloud accounts setups
* Fixed search-result-created markers not having a creation date
* Fixed creation date of a marker not being editable
* Fixed in-app contact email address being the same for all platforms
* Added the "Default navigation action" setting to allow better control on how to start navigation
* Fixed CSV file import bug when produced from Windows

## Version 3.0.1 - 2023/02/04 - Android+520 - iOS+519 - Web+520

Release files [here](https://github.com/androidseb/mapmarker/releases/tag/map_marker_v3.0.1).

* Fixed old map data migration not finding all map files (iOS only)
* Fixed image sharing not working if no export has ever been made (Android only)
* Made the troubleshooting log file easier to extract
* Fixed retry for cloud sync with device conflict not giving up after 5 attempts
* Fixed a rare case where cloud data being rolled back when two devices sync at exactly the same second with exactly the same number of folders + markers
* Cloud sync history now displays change details with number folders and markers added/modified/deleted

## Version 3.0.0 - 2023/01/31 - Android+513 - iOS+513 - Web+513

Release files [here](https://github.com/androidseb/mapmarker/releases/tag/map_marker_v3.0.0).

The first Flutter Map Marker app release:

* Much faster app start time
* Smart markers display: limit the number of markers visible at a given time
	* Regardless of the number of markers the map view should remain smooth
	* You can now have thousands of markers in your map without slowdowns
* Almost all features from Android (except offline maps) are now available on iOS and web:
	* Dropbox cloud sync
	* Floating titles
	* Sub-folders
	* Custom folder colors
	* Image quality settings
	* Share map snapshot
	* Manage map files
	* Jump to coordinates
	* Delete duplicates
* No longer depending on Google Play Services to work (easier to run on alternative Android distributions)
* Cloud sync no longer blocks the app with a loading screen, it is performed in the background while using the app
* Reduced problems with large files on the Web version
* Overall better performance and usability
* More efficient app development, so more frequent features in the future, on all platforms

## Version 2.24.0 - 2022/10/24 - Android

Release files [here](https://github.com/androidseb/mapmarker/releases/tag/map_marker_v2).

The last non-Flutter Map Marker Android app version:

* Added in-app prompt about V3 upgrade
* Updated translations

## Version 2.14 - 2021/03/07 - iOS

Release files [here](https://github.com/androidseb/mapmarker/releases/tag/map_marker_v2).

The last non-Flutter Map Marker iOS app version:

* Removed Algolia search from third-party search sources
* Fixed "My Location" button not working for location changes smaller than 100 meters
