# Life Expectancy Map Program

This program displays Life Expectancy data using Processing, and Unfolding Maps API.

It uses LifeExpectancyWorldBank data in CSV format and it can be found at http://data.worldbank.org.

The methodology to represent Life Expectancy was to color each country with high life expectancy with cool colors such as dark blue, and going towards warm colors as the expectancy drops, like red.

To underline the map and countries, a helper file [countries.geo.json](https://github.com/johan/world.geo.json/blob/master/countries.geo.json) was used.
This program also uses:
  * [Android Location](http://developer.android.com/reference/android/location/Location.html) api, and is under The [Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0). This API uses Geolocation to display data in different points of the map.
  * [Unfolding Maps](http://unfoldingmaps.org) api. It provides maps from several sources. ex. Google, Microsoft, Yahoo, etc.
  * [Processing](https://processing.org) Library. Applet to display graphics on the screen.

This is what the program displays:

<p align="center"><img src="https://cdn.rawgit.com/bruno78/life-expectancy-map/0458d1e9/data/lifeExpectancyMap.png" alt="Life Expectancy map" /></p>
