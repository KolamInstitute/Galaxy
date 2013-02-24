![logo](http://www.kolam-institute.org/images/galaxy1logo.jpg)

An HTML5 Framework for Knowledge Database Visualization based on Geographic coordinates - Community Edition

> This project is intended to provide a dedicated template for open source GIS mapping solution. 
> It is based on Leaflet.js, a lightweight library and its plugins. Just add this code to your HTML5 document header:

```html
    <link rel="stylesheet" type="text/css" href="app/galaxy-ui.css" />
    <link rel="stylesheet" type="text/css" href="app/galaxy-map.css" />
```

```html
    <script type="text/javascript" src="app/galaxy-core.js"></script>
    <script type="text/javascript" src="app/galaxy-conf.js"></script>
    <script type="text/javascript" src="app/galaxy-mod.js"></script>
```

***

![gowiki](http://www.vpul.upenn.edu/gic/images/arrow2.gif)   See documentation: https://github.com/KolamInstitute/Galaxy/wiki

====================================================

### Browsers Tested ###

![browsers](http://www.webapptesting.com/wp-content/uploads/2012/12/Mobile-Browsers.jpg)

====================================================

THIS DOCUMENTATION IS IN PROGRESS !!!
* * *
[**DATA STRUCTURE**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan) | [**LAYERING**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan) | [**STORAGE**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan) | [**CORE**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan) | [**UI**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan) | [**MODULES**](https://github.com/KolamInstitute/Galaxy-/wiki/Development-plan)

![gowiki](http://www.vpul.upenn.edu/gic/images/arrow2.gif)   Demo app 0.6: http://www.kolam-institute.org/dev/package%20061/index.html

![gowiki](http://www.vpul.upenn.edu/gic/images/arrow2.gif)   Demo app 0.8: http://www.kolam-institute.org/galaxy/map.html

![gowiki](http://www.vpul.upenn.edu/gic/images/arrow2.gif)   Demo app 0.9: Coming soon !
* * *
**Goals (V1):**
* **Data vizualisation**: JSON/CSV ([See more details](https://github.com/KolamInstitute/Galaxy-/wiki/GeoJson-specifications))
* **Views**: Map/table/charts/timeline
* **Screens**: desktop/tablet/smartphone
* **Templates**: CSS themes and iconset

***

Dependencies 
------------

**Validator:** 
`Implemented` ![checked](http://www.digium.com/sites/digium/files/icon-green-check.png)
`Testing` ![testing](http://www.onlinecjc.ca/webfiles/images/icons/cog_add.png)
`Not yet compatible` ![notyet](http://www.whosarrested.com/images/error.png)

> The Core application includes several external libraries, 
this add new features like data searching and sorting, visualization and charting...

| Core Packages| Release | Status  | Link | Comments |
|:-------------|:-------:|:-------:|:-----|:---------|
| `Galaxy.js`  |0.9.3    |![check](http://www.digium.com/sites/digium/files/icon-green-check.png) | https://github.com/Kolaminstitute/Galaxy | UI engine |
| `Leaflet.js` |0.5.1    |![check](http://www.digium.com/sites/digium/files/icon-green-check.png) | https://github.com/Leaflet/Leaflet| Map view engine |
| `Recline.js` |0.7.0    |![testing](http://www.onlinecjc.ca/webfiles/images/icons/cog_add.png)   | https://github.com/okfn/recline | Data bind engine |
| `D3.js`      |3.0.6    |![testing](http://www.onlinecjc.ca/webfiles/images/icons/cog_add.png)   | https://github.com/mbostock/d3 | Data view engine |

> The UI is adapted to various plateforms, from desktop to mobile devices. In case of non-supported devices, it goes
to pure html template

| UI Packages  | Release | Status  | Link | Comments |
|:-------------|:-------:|:-------:|:-----|:---------|
| `JQuery.js` |0.5.1     |![check](http://www.digium.com/sites/digium/files/icon-green-check.png) | https://github.com/jquery/jquery | no comments yet |
| `JQmobile.js` |0.7.0   |![check](http://www.digium.com/sites/digium/files/icon-green-check.png) | https://github.com/jquery/jquery-mobile | no comments yet |

***

> There is a set of plugins, mostly map related, to add some extra tools

| Plugins                    | Release | Status  | Link | Comments |
|:---------------------------|:-------:|:-------:|:-----|:---------|
| `Leaflet.markercluster.js` |0.5.1    |![check](http://www.digium.com/sites/digium/files/icon-green-check.png) | https://github.com/Leaflet/Leaflet| no comments yet |
| `Leaflet.label.js`         |0.7.0    |![check](http://www.digium.com/sites/digium/files/icon-green-check.png) | https://github.com/okfn/recline | no comments yet |
| `Leaflet.geoCSV.js`        |3.0.6    |![check](http://www.digium.com/sites/digium/files/icon-green-check.png) | https://github.com/mbostock/d3 | no comments yet |
| `Leaflet.draw.js`          |3.0.6    |![testing](http://www.onlinecjc.ca/webfiles/images/icons/cog_add.png) | https://github.com/mbostock/d3 | no comments yet |
| `Leaflet.search.js`        |3.0.6    |![testing](http://www.onlinecjc.ca/webfiles/images/icons/cog_add.png) | https://github.com/mbostock/d3 | no comments yet |
| `Leaflet.hash.js`          |3.0.6    |![check](http://www.digium.com/sites/digium/files/icon-green-check.png) | https://github.com/mbostock/d3 | no comments yet |
| `Proj4Leaflet.js`          |3.0.6    |![testing](http://www.onlinecjc.ca/webfiles/images/icons/cog_add.png) | https://github.com/mbostock/d3 | no comments yet |

