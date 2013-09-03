# PhoneGap iOS MapKit Plugin #

## Requirements ##

Using this plugin requires [iOS PhoneGap](http://github.com/phonegap/phonegap) and the MapKit framework.

The plugin works with PhoneGap (Cordova) versions 2.8 and 2.9.

## Adding the Plugin to your project ##

1. Add the "MapKit" framework to your Xcode project (different in Xcode 3 and 4, search for instructions)
2. Add the .h and .m files to your Plugins folder in your project
3. Add the .js file to your "www" folder on disk, and add reference(s) to the .js file as &lt;script&gt; tags in your html file(s)
4. Add map-close-button.png to your "www" folder on disk.
5. In your app's config.xml, add a feature entry. Set feature name to "MapKitView", and param value to "MapKitView".

## Example ##

There is an example project in the example folder.

