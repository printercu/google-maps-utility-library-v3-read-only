# Google Maps Utility Library v3

This is git clone of original http://google-maps-utility-library-v3.googlecode.com/svn/
repo. It's been a long time ago, when there was no google's account on github.

For now try to find libraries your looking for at https://github.com/googlemaps.
However some libraries are not available there.

There is bower package:

```
bower install google-maps-utility-library-v3
```

Some libraries has hardcoded url which were pointing to googlecode's CDN.
This urls were changed to https://cdn.rawgit.com/ after google's CDN is shut down.
However exaples and some compiled files are not updated. Please consider using
self hosted files or at least set urls manually. Check library source for config options.

```js
// Example for MarkerClustererPlus:
MarkerClusterer.IMAGE_PATH = "https://my-domain.com/assets/markerclustererplus/images/m";
```

`svn` branch will remain untouched.
