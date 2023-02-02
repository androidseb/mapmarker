# Changelog

## Version 3.0.0 (Android / iOS / Web - 2023/01/31)

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

## Version 2.24.0 (Android - 2022/10/24)

Release files [here](https://github.com/androidseb/mapmarker/releases/tag/map_marker_v2).

The last non-Flutter Map Marker Android app version:

* Added in-app prompt about V3 upgrade
* Updated translations

## Version 2.14 (iOS - 2021/03/07)

Release files [here](https://github.com/androidseb/mapmarker/releases/tag/map_marker_v2).

The last non-Flutter Map Marker iOS app version:

* Removed Algolia search from third-party search sources
* Fixed "My Location" button not working for location changes smaller than 100 meters
