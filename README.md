# PhoneGap/Cordova iOS MapKit Plugin #

## Requirements ##

The plugin works with PhoneGap (Cordova) versions 2.8, 2.9 and 3.0.

## Adding the Plugin to your 3.0 project ##

1. run 'cordova plugin add https://github.com/RonaldPK/MapKit-iOS.git'
(replace 'cordova' by 'phonegap local' if that's your cli)
2. copy map-close-button.png from plugins/com.contentecontent.cordova.plugins.mapKit to platforms/ios/www 

## Adding the Plugin to your 2.8/2.9 project ##

1. Add the "MapKit" framework to your Xcode project (different in Xcode 3 and 4/5, search for instructions)
2. Add the .h and .m files to your Plugins folder in your project
3. Add MapKit.js file to your "www" folder on disk, and add reference(s) to the .js file as &lt;script&gt; tags in your html file(s)
4. Add map-close-button.png to your "www" folder on disk.
5. In your app's config.xml, add a feature entry. Set feature name to "MapKitView", and param value to "MapKitView".

## Example ##

There is an example project in the example folder.

## License ##

MIT licensed